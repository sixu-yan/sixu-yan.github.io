# Website Maintenance Notes

This repository contains the source code for [Sixu Yan's personal academic website](https://sixu-yan.github.io/). It is based on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template.

## Repository Structure

- `_pages/about.md`: Main page content, including the biography, news, publications, education, internships, academic service, and honors.
- `_config.yml`: Site title, description, author profile, avatar, contact information, analytics, and build settings.
- `_data/navigation.yml`: Top navigation links.
- `images/person/`: Avatar, WeChat QR code, and favicon.
- `images/papers/`: Publication images, organized by paper.
- `assets/videos/`: Video highlights displayed below the biography.
- `assets/`, `_sass/`, `_includes/`, and `_layouts/`: Theme styles, scripts, reusable components, and layouts.
- `google_scholar_crawler/`: Optional Google Scholar citation crawler.
- `.github/workflows/google_scholar_crawler.yaml`: Scheduled citation update workflow.

## Local Setup

Install Ruby 3.2 or later, RubyGems, Bundler, GCC, and Make. The system Ruby included with macOS may be too old for this project, so a Ruby version manager or Homebrew installation is recommended.

Install the dependencies from the repository root:

```bash
bundle install
```

Start the local development server:

```bash
bundle exec jekyll serve --livereload
```

The helper script provides the same command:

```bash
sh run_server.sh
```

Open <http://127.0.0.1:4000/> in a browser. Changes to Markdown, HTML, and style files are rebuilt automatically. Restart the server after changing `_config.yml`.

To verify a production build without starting the server, run:

```bash
bundle exec jekyll build
```

The default build output is `_site/`. It is generated automatically, ignored by Git, and must not be edited or committed.

## Updating the Website

### Profile and Contact Information

Edit the `author` section in `_config.yml` to update the name, biography, avatar, location, email address, WeChat QR code, GitHub account, or Google Scholar profile.

Edit the introductory paragraphs near the top of `_pages/about.md` to update the research summary, degree status, advisors, or collaborators.

### News, Education, Internships, Service, and Honors

These sections are maintained directly in `_pages/about.md`:

- Keep News entries in reverse chronological order.
- Use `YYYY/MM` for News dates and emphasize the venue or award consistently.
- Keep Education, Internships, Academic Service, and Honors in reverse chronological order.
- Use the official English names of institutions, conferences, journals, and awards.

### Navigation

Edit `_data/navigation.yml` to change the top navigation. Each link must match an existing section anchor in `_pages/about.md`, for example:

```yaml
- title: "Publications"
  url: "/#publications"
```

### Adding a Publication

In the `Selected Publications` section of `_pages/about.md`, copy an existing complete `<div class="paper-box">...</div>` block and update:

1. The conference, journal, or arXiv label.
2. The publication image and alternative text.
3. The title and official paper or project link.
4. The author list and verified author homepage links.
5. Paper, arXiv, project, code, model, dataset, and video links as applicable.
6. The short description.
7. The complete BibTeX entry inside the collapsible `BibTeX` block.

Bold `Sixu Yan` in the author list. Add an equal-contribution note only when Sixu Yan is an equal-contribution author.

Store the publication image in a dedicated directory:

```text
images/papers/paper-name/
```

Use a short lowercase English directory name when adding a new paper. Existing published paths may remain unchanged to avoid broken links.

### Images and Videos

- Store profile assets in `images/person/`.
- Store each paper's images in its own directory under `images/papers/`.
- Store published videos in `assets/videos/`.
- Use short, descriptive, lowercase English filenames separated by hyphens.
- Do not reference files outside this repository, including `temp/`, `references/`, or `current-site/`.
- Remove an asset only after confirming that no Markdown, HTML, CSS, JavaScript, or configuration file references it.

## Google Scholar Citation Updates

The optional citation crawler is retained in this repository. To enable it, add a GitHub Actions repository secret:

```text
Name: GOOGLE_SCHOLAR_ID
Value: vVU-oVMAAAAJ
```

Enable the `Get Citation Data` workflow in the repository's Actions settings. The workflow runs after a GitHub Pages build and on its daily schedule, then updates the `google-scholar-stats` branch.

The main website does not require citation statistics to render. If the crawler is disabled, the rest of the site remains available.

## Publishing with GitHub Pages

1. Run `bundle exec jekyll build` and resolve every build error.
2. Preview the site locally and check desktop and mobile layouts.
3. Confirm that every publication, author, project, code, video, and contact link is correct.
4. Confirm that `_site/`, `.sass-cache/`, `.DS_Store`, AppleDouble files, temporary assets, and local dependency directories are not committed.
5. Commit the contents of this repository to the default branch of `sixu-yan/sixu-yan.github.io`.
6. In **Settings → Pages**, confirm that GitHub Pages builds from the default branch.
7. After deployment finishes, verify <https://sixu-yan.github.io/>.

## Pre-Publication Checklist

- The README profile and News match the live page.
- The degree year and research description are current.
- All visible content and maintenance documentation use English, except for the Chinese personal name.
- Images and videos load from repository-relative paths.
- No generated output, caches, temporary files, or unused assets are included.
- The Jekyll build completes successfully.
- The deployed homepage works on desktop and mobile browsers.
