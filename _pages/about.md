---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

I am **Sixu Yan (鄢思旭)**, a **third-year Ph.D. student** at the [HUST Vision Lab (HUSTVL)](https://github.com/hustvl/), Artificial Intelligence Institute, [School of Electronic Information and Communications](http://english.eic.hust.edu.cn/), [Huazhong University of Science and Technology (HUST)](https://english.hust.edu.cn/), advised by Prof. [Xinggang Wang](https://xwcv.github.io/).

Prior to that, I received my M.S. degree from the [School of Mechanical Engineering](https://me.sjtu.edu.cn/en/) at [Shanghai Jiao Tong University (SJTU)](https://en.sjtu.edu.cn/), where I conducted research in the [Robot Control and Machine Vision Lab (RCMVL)](http://www.rcmvl.com/) at the Institute of Robotics, under the supervision of Prof. [Han Ding](https://me.sjtu.edu.cn/zmxy/57361.html/) and Prof. [Zhenhua Xiong](https://me.sjtu.edu.cn/teacher_directory1/xiongzhenhua.html/).

My research goal is to develop **general-purpose cognitive robots**. Currently, I focus on scaling up robotic dexterous manipulation through large-scale synthetic data generation and sim-to-real transfer. My prior work includes motion planning and imitation learning. During my Ph.D., I have been fortunate to collaborate closely with Dr. [Hangxin Liu](https://liuhx111.github.io/), Dr. [Zeyu Zhang](https://zeyuzhang.com/), and Prof. [Song-Chun Zhu](https://zhusongchun.net/) from the [Beijing Institute for General Artificial Intelligence (BIGAI)](https://www.bigai.ai/).

> “Stay curious. Stay humble. Keep building.”

<div class="video-gallery" aria-label="Robotics video highlights" tabindex="0">
  <figure class="video-card">
    <video autoplay muted loop playsinline controls preload="metadata" aria-label="Vision-Language Grasping">
      <source src="{{ '/assets/videos/dexterous-hand-grasping.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <figcaption>Vision-Language Grasping</figcaption>
  </figure>
  <figure class="video-card">
    <video autoplay muted loop playsinline controls preload="metadata" aria-label="Bimanual Sorting">
      <source src="{{ '/assets/videos/bimanual-sorting.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <figcaption>Bimanual Sorting</figcaption>
  </figure>
  <figure class="video-card">
    <video autoplay muted loop playsinline controls preload="metadata" aria-label="Humanoid Whole-body Control">
      <source src="{{ '/assets/videos/humanoid-whole-body-control.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <figcaption>Humanoid Whole-body Control</figcaption>
  </figure>
  <figure class="video-card">
    <video autoplay muted loop playsinline controls preload="metadata" aria-label="Mobile Manipulation">
      <source src="{{ '/assets/videos/bimanual-coordination.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <figcaption>Mobile Manipulation</figcaption>
  </figure>
  <figure class="video-card video-card--cover">
    <video autoplay muted loop playsinline controls preload="metadata" aria-label="Bimanual Coordination">
      <source src="{{ '/assets/videos/mobile-manipulation.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <figcaption>Bimanual Coordination</figcaption>
  </figure>
</div>

<script>
  document.querySelectorAll('.video-gallery video').forEach((video) => {
    video.muted = true;
    video.defaultMuted = true;
    video.volume = 0;
    video.addEventListener('volumechange', () => {
      video.muted = true;
      video.volume = 0;
    });
  });
</script>

<span class="anchor" id="news"></span>

# 🔥 News

- **[2026/01]** 🎉 [ReCogDrive](https://xiaomi-research.github.io/recogdrive/) was accepted to <strong style="color: red;">ICLR 2026</strong>!
- **[2025/05]** 🎉 [M<sup>3</sup>Bench](https://zeyuzhang.com/papers/m3bench/) was accepted to <strong style="color: red;">RA-L 2025</strong>!
- **[2025/04]** 🎉 [DiffusionDrive](https://github.com/hustvl/DiffusionDrive/) was awarded as a <strong style="color: red;">CVPR 2025 Highlight</strong>!
- **[2025/03]** 🎉 [M<sup>2</sup>Diffuser](https://m2diffuser.github.io/) was accepted to <strong style="color: red;">T-PAMI 2025</strong>!
- **[2025/02]** 🎉 [DiffusionDrive](https://github.com/hustvl/DiffusionDrive/) was accepted to <strong style="color: red;">CVPR 2025</strong>!

<span class="anchor" id="publications"></span>

# 📝 Selected Publications

My research is broadly in **Robotics** and **Computer Vision**, with a particular focus on generalizable perception and dexterous manipulation in complex environments. For a complete publication list, please visit my [Google Scholar profile](https://scholar.google.com/citations?user=vVU-oVMAAAAJ&hl=en).

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">arXiv 2026</div>
      <img src="images/papers/AdaRoboVLG/framework.png" alt="AdaRoboVLG framework overview" width="100%">
    </div>
  </div>
  <div class="paper-box-text" markdown="1">

## [Adaptive Vision-Language Grasping via Composable Foundation Priors and Generalizable Grasp Synthesis](https://adarobovlg.github.io/)

**Sixu Yan<sup>\*</sup>**, Shikang Wang<sup>\*</sup>, Binhua Huang, Xuanlai Tang, Guohua Fan, Fan Huang, [Haoxuan Li](https://github.com/RogerRafa), [Yongkang Li](https://owl-10.github.io/yongkangli/), Yuhan Li, [Bencheng Liao](https://github.com/LegendBC), [Zeyu Zhang](https://zeyuzhang.com/), [Wenyu Liu](https://eic.hust.edu.cn/professor/liuwenyu/), [Hangxin Liu](https://liuhx111.github.io/), [Xinggang Wang](https://xwcv.github.io/)

***\* denotes equal contribution***

[Paper](https://arxiv.org/pdf/2609.04096) · [arXiv](https://arxiv.org/abs/2609.04096) · [Project](https://adarobovlg.github.io/) · [Code](https://github.com/AdaRoboVLG/AdaRoboVLG) · [Simulation](https://github.com/AdaRoboVLG/AdaRoboVLG-Playground) · [YouTube](https://www.youtube.com/watch?v=U5pP5MMkoxg) · [Bilibili](https://b23.tv/a20ZiTn) · [RedNote](https://www.xiaohongshu.com/discovery/item/6aa8b71c0000000029019c42?source=webshare&xhsshare=pc_web&xsec_token=ABUTqBUabNzVzggSzg46xrOtcGAVpGDJN7iiONhEuE7Vc=&xsec_source=pc_share)

We propose **AdaRoboVLG**, a task-adaptive vision-language-grasping framework that composes specialized foundation-model priors with a generalizable base policy, enabling physically feasible and context-aware grasp synthesis across different robotic hands.

<details markdown="1">
<summary>BibTeX</summary>

```bibtex
@article{yan2026adarobovlg,
  title   = {Adaptive Vision-Language Grasping via Composable Foundation Priors and Generalizable Grasp Synthesis},
  author  = {Yan, Sixu and Wang, Shikang and Huang, Binhua and Tang, Xuanlai and Fan, Guohua and Huang, Fan and Li, Haoxuan and Li, Yongkang and Li, Yuhan and Liao, Bencheng and Zhang, Zeyu and Liu, Wenyu and Liu, Hangxin and Wang, Xinggang},
  journal = {arXiv preprint arXiv:2609.04096},
  year    = {2026}
}
```
</details>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">arXiv 2026</div>
      <img src="images/papers/UniDriveVLA/framework.png" alt="UniDriveVLA framework overview" width="100%">
    </div>
  </div>
  <div class="paper-box-text" markdown="1">

## [UniDriveVLA: Unifying Understanding, Perception, and Action Planning for Autonomous Driving](https://xiaomi-research.github.io/unidrivevla/)

[Yongkang Li](https://owl-10.github.io/yongkangli/), [Lijun Zhou](https://scholar.google.com/citations?hl=en&user=RYIXvAoAAAAJ), **Sixu Yan**, [Bencheng Liao](https://github.com/LegendBC), [Tianyi Yan](https://scholar.google.com/citations?user=0JmbnNQAAAAJ&hl=en&oi=ao), [Kaixin Xiong](https://scholar.google.com/citations?user=Kh01ChoAAAAJ&hl=en&oi=ao), [Long Chen](https://long.ooo/), [Hongwei Xie](https://scholar.google.com/citations?user=kRvS9KAAAAAJ&hl=en&oi=ao), [Bing Wang](https://scholar.google.com/citations?user=uwTzb6IAAAAJ&hl=en&oi=sra), [Guang Chen](https://scholar.google.com/citations?user=yO82m38AAAAJ&hl=en), [Hangjun Ye](https://scholar.google.com/citations?user=68tXhe8AAAAJ), [Wenyu Liu](https://eic.hust.edu.cn/professor/liuwenyu/), [Haiyang Sun](https://scholar.google.com/citations?hl=en&user=SYbFNsIAAAAJ), [Xinggang Wang](https://xwcv.github.io/)

[Paper](https://arxiv.org/pdf/2604.02190) · [arXiv](https://arxiv.org/abs/2604.02190) · [Project](https://xiaomi-research.github.io/unidrivevla/) · [Code](https://github.com/xiaomi-research/unidrivevla) · [Hugging Face](https://huggingface.co/collections/owl10/unidrivevla) · [Dataset](https://huggingface.co/datasets/owl10/UniDriveVLA_Data)

We propose **UniDriveVLA**, a unified driving vision-language-action model that decouples understanding, spatial perception, and action planning through specialized experts, achieving strong performance across open-loop and closed-loop autonomous-driving benchmarks.

<details markdown="1">
<summary>BibTeX</summary>

```bibtex
{% raw %}
@article{li2026unidrivevla,
  title   = {{UniDriveVLA}: Unifying Understanding, Perception, and Action Planning for Autonomous Driving},
  author  = {Li, Yongkang and Zhou, Lijun and Yan, Sixu and Liao, Bencheng and Yan, Tianyi and Xiong, Kaixin and Chen, Long and Xie, Hongwei and Wang, Bing and Chen, Guang and Ye, Hangjun and Liu, Wenyu and Sun, Haiyang and Wang, Xinggang},
  journal = {arXiv preprint arXiv:2604.02190},
  year    = {2026}
}
{% endraw %}
```
</details>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">arXiv 2026</div>
      <img src="images/papers/OmniTrack/framework.png" alt="OmniTrack framework overview" width="100%">
    </div>
  </div>
  <div class="paper-box-text" markdown="1">

## [OmniTrack: General Motion Tracking via Physics-Consistent Reference](https://omnitrack-humanoid.github.io/)

Yuhan Li, Peiyuan Zhi, [Yunshen Wang](https://perkins729.github.io/), [Tengyu Liu](https://tengyu.ai/), **Sixu Yan**, [Wenyu Liu](https://eic.hust.edu.cn/professor/liuwenyu/), [Xinggang Wang](https://xwcv.github.io/), [Baoxiong Jia](https://buzz-beater.github.io/), [Siyuan Huang](https://siyuanhuang.com/)

[Paper](https://arxiv.org/pdf/2602.23832) · [arXiv](https://arxiv.org/abs/2602.23832) · [Project](https://omnitrack-humanoid.github.io/) · [Code](https://github.com/OmniTrack-Humanoid/OmniTrack) · [YouTube](https://www.youtube.com/watch?v=5u93K6YZV3g)

We propose **OmniTrack**, a two-stage humanoid motion tracking framework that first generates physically feasible references in simulation and then learns a general policy to track them, improving accuracy and generalization to unseen motions.

<details markdown="1">
<summary>BibTeX</summary>

```bibtex
@article{li2026omnitrack,
  title   = {OmniTrack: General motion tracking via physics-consistent reference},
  author  = {Li, Yuhan and Zhi, Peiyuan and Wang, Yunshen and Liu, Tengyu and Yan, Sixu and Liu, Wenyu and Wang, Xinggang and Jia, Baoxiong and Huang, Siyuan},
  journal = {arXiv preprint arXiv:2602.23832},
  year    = {2026}
}
```
</details>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">ICLR 2026</div>
      <img src="images/papers/ReCogDrive/framework.png" alt="ReCogDrive framework overview" width="100%">
    </div>
  </div>
  <div class="paper-box-text" markdown="1">

## [ReCogDrive: A Reinforced Cognitive Framework for End-to-End Autonomous Driving](https://xiaomi-research.github.io/recogdrive/)

[Yongkang Li](https://owl-10.github.io/yongkangli/), [Kaixin Xiong](https://scholar.google.com/citations?user=Kh01ChoAAAAJ&hl=en&oi=ao), Xiangyu Guo, Fang Li, **Sixu Yan**, [Gangwei Xu](https://gangweix.github.io/), [Lijun Zhou](https://scholar.google.com/citations?hl=en&user=RYIXvAoAAAAJ), [Long Chen](https://long.ooo/), [Haiyang Sun](https://scholar.google.com/citations?hl=en&user=SYbFNsIAAAAJ), [Bing Wang](https://scholar.google.com/citations?user=uwTzb6IAAAAJ&hl=en&oi=sra), Kun Ma, [Guang Chen](https://scholar.google.com/citations?user=yO82m38AAAAJ&hl=en), [Hangjun Ye](https://scholar.google.com/citations?user=68tXhe8AAAAJ), [Wenyu Liu](https://eic.hust.edu.cn/professor/liuwenyu/), [Xinggang Wang](https://xwcv.github.io/)

[Paper](https://proceedings.iclr.cc/paper_files/paper/2026/file/ff7bf6014f7826da531aa50f4538ee19-Paper-Conference.pdf) · [arXiv](https://arxiv.org/abs/2506.08052) · [Project](https://xiaomi-research.github.io/recogdrive/) · [Code](https://github.com/xiaomi-research/recogdrive) · [Models](https://huggingface.co/collections/owl10/recogdrive-68bafa143de172bab8de5752) · [Dataset](https://huggingface.co/datasets/owl10/ReCogDrive_Pretraining)

We propose **ReCogDrive**, a reinforced cognitive framework that combines vision-language driving understanding with a diffusion planner and reinforcement learning to generate safer, more stable trajectories for end-to-end autonomous driving.

<details markdown="1">
<summary>BibTeX</summary>

```bibtex
{% raw %}
@inproceedings{li2026recogdrive,
  title     = {{ReCogDrive}: A Reinforced Cognitive Framework for End-to-End Autonomous Driving},
  author    = {Li, Yongkang and Xiong, Kaixin and Guo, Xiangyu and Li, Fang and Yan, Sixu and Xu, Gangwei and Zhou, Lijun and Chen, Long and Sun, Haiyang and Wang, Bing and Ma, Kun and Chen, Guang and Ye, Hangjun and Liu, Wenyu and Wang, Xinggang},
  booktitle = {International Conference on Learning Representations},
  volume    = {2026},
  pages     = {157518--157556},
  year      = {2026}
}
{% endraw %}
```
</details>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">IEEE RA-L 2025</div>
      <img src="images/papers/M3Bench/teaser.jpg" alt="M3Bench teaser" width="100%">
    </div>
  </div>
  <div class="paper-box-text" markdown="1">

## [M<sup>3</sup>Bench: Benchmarking Whole-body Motion Generation for Mobile Manipulation in 3D Scenes](https://zeyuzhang.com/papers/m3bench/)

[Zeyu Zhang](https://zeyuzhang.com/)<sup>\*</sup>, **Sixu Yan<sup>\*</sup>**, [Muzhi Han](https://scholar.google.com/citations?user=jqbHlSsAAAAJ&hl=en), Zaijin Wang, [Xinggang Wang](https://xwcv.github.io/), [Song-Chun Zhu](https://zhusongchun.net/), [Hangxin Liu](https://liuhx111.github.io/)

***\* denotes equal contribution***

[Paper](https://arxiv.org/pdf/2410.06678) · [arXiv](https://arxiv.org/abs/2410.06678) · [Project](https://zeyuzhang.com/papers/m3bench/) · [YouTube](https://youtu.be/TwJQnRm663M?si=dXVRyi1eJv57DaEaz) · [Bilibili](https://www.bilibili.com/video/BV1jd73zxEYo/)

We propose **M<sup>3</sup>Bench**, a large-scale benchmark and data generation toolkit for evaluating whole-body motion generation in mobile manipulation. It includes over 30,000 pick-and-place tasks across 119 realistic 3D scenes, with expert trajectories generated by a VKC planner.

<details markdown="1">
<summary>BibTeX</summary>

```bibtex
@article{zhang2025m3bench,
  title     = {M${}^{3}$Bench: Benchmarking Whole-Body Motion Generation for Mobile Manipulation in 3D Scenes},
  author    = {Zhang, Zeyu and Yan, Sixu and Han, Muzhi and Wang, Zaijin and Wang, Xinggang and Zhu, Song-Chun and Liu, Hangxin},
  journal   = {IEEE Robotics and Automation Letters},
  year      = {2025},
  volume    = {10},
  number    = {7},
  pages     = {7286--7293},
  publisher = {IEEE}
}
```
</details>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">IEEE T-PAMI 2025</div>
      <img src="images/papers/M2Diffuser/overview.png" alt="M2Diffuser overview" width="100%">
    </div>
  </div>
  <div class="paper-box-text" markdown="1">

## [M<sup>2</sup>Diffuser: Diffusion-based Trajectory Optimization for Mobile Manipulation in 3D Scenes](https://m2diffuser.github.io/)

**Sixu Yan**, [Zeyu Zhang](https://zeyuzhang.com/), [Muzhi Han](https://scholar.google.com/citations?user=jqbHlSsAAAAJ&hl=en), Zaijin Wang, [Qi Xie](https://github.com/sudoku77/), Zhitian Li, Zhehan Li, [Hangxin Liu](https://liuhx111.github.io/), [Xinggang Wang](https://xwcv.github.io/), [Song-Chun Zhu](https://zhusongchun.net/)

[Paper](https://m2diffuser.github.io/assets/paper/M2Diffuser.pdf) · [arXiv](https://arxiv.org/pdf/2410.11402) · [Project](https://m2diffuser.github.io/) · [Code](https://github.com/m2diffuser/M2Diffuser) · [YouTube](https://youtu.be/T7kpDifRtfk?si=-R5agRpDM4uJKtuz) · [Bilibili](https://www.bilibili.com/video/BV14yMAzbE9v/)

We propose **M<sup>2</sup>Diffuser** (Mobile Manipulation Diffuser), a conditional diffusion-based neural motion planner capable of generating full-body coordinated trajectories that satisfy both physical and task constraints.

<details markdown="1">
<summary>BibTeX</summary>

```bibtex
@article{yan2025m2diffuser,
  title     = {M2Diffuser: Diffusion-based Trajectory Optimization for Mobile Manipulation in 3D Scenes},
  author    = {Yan, Sixu and Zhang, Zeyu and Han, Muzhi and Wang, Zaijin and Xie, Qi and Li, Zhitian and Li, Zhehan and Liu, Hangxin and Wang, Xinggang and Zhu, Song-Chun},
  journal   = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
  year      = {2025},
  publisher = {IEEE}
}
```
</details>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">CVPR 2025 Highlight</div>
      <img src="images/papers/DiffusionDrive/truncated_diffusion_policy.png" alt="DiffusionDrive method overview" width="100%">
    </div>
  </div>
  <div class="paper-box-text" markdown="1">

## [DiffusionDrive: Truncated Diffusion Model for End-to-End Autonomous Driving](https://github.com/hustvl/DiffusionDrive/)

[Bencheng Liao](https://github.com/LegendBC), [Shaoyu Chen](https://scholar.google.com/citations?user=PIeNN2gAAAAJ&hl=en&oi=sra), Haoran Yin, [Bo Jiang](https://thebojiang.github.io/), [Cheng Wang](https://scholar.google.com/citations?user=PdJIyPIAAAAJ&hl=zh-CN), **Sixu Yan**, Xinbang Zhang, Xiangyu Li, Ying Zhang, [Qian Zhang](https://scholar.google.com/citations?user=pCY-bikAAAAJ&hl=zh-CN), [Xinggang Wang](https://xwcv.github.io/)

[Paper](https://arxiv.org/pdf/2411.15139) · [arXiv](https://arxiv.org/abs/2411.15139) · [Project](https://github.com/hustvl/DiffusionDrive) · [Code](https://github.com/hustvl/DiffusionDrive) · [Hugging Face](https://huggingface.co/hustvl/DiffusionDrive)

We propose **DiffusionDrive**, a truncated diffusion-based planner for real-time end-to-end autonomous driving. By injecting multi-mode anchors and reducing denoising to two steps, it achieves fast inference while maintaining high-quality trajectory prediction.

<details markdown="1">
<summary>BibTeX</summary>

```bibtex
@inproceedings{liao2025diffusiondrive,
  author    = {Liao, Bencheng and Chen, Shaoyu and Yin, Haoran and Jiang, Bo and Wang, Cheng and Yan, Sixu and Zhang, Xinbang and Li, Xiangyu and Zhang, Ying and Zhang, Qian and Wang, Xinggang},
  title     = {DiffusionDrive: Truncated Diffusion Model for End-to-End Autonomous Driving},
  booktitle = {Proceedings of the Computer Vision and Pattern Recognition Conference (CVPR)},
  year      = {2025},
  pages     = {12037--12047}
}
```
</details>

  </div>
</div>

<span class="anchor" id="education"></span>

# 🎓 Education

- **Huazhong University of Science and Technology (HUST)**, 2024.09–Present  
  Ph.D. Student, [HUST Vision Lab (HUSTVL)](https://github.com/hustvl/)  
  Research advisor: Prof. [Xinggang Wang](https://xwcv.github.io/)

- **Shanghai Jiao Tong University (SJTU)**, 2021.09–2024.06  
  M.S. Student, [Robot Control and Machine Vision Lab (RCMVL)](http://www.rcmvl.com/)  
  Research advisor: Prof. [Zhenhua Xiong](https://me.sjtu.edu.cn/teacher_directory1/xiongzhenhua.html/); academic advisor: Prof. [Han Ding](https://me.sjtu.edu.cn/zmxy/57361.html/)

- **Ocean University of China (OUC)**, 2017.09–2021.06  
  Undergraduate Student, GPA rank **1/62** during the application season  
  Research advisor: Prof. Xiaojie Tian

<span class="anchor" id="internships"></span>

# 💼 Internships

- **Beijing Institute for General Artificial Intelligence (BIGAI)**, 2023.07–2024.08  
  Research Intern, Robotics Lab  
  Research advisors: Dr. [Hangxin Liu](https://liuhx111.github.io/) and Dr. [Zeyu Zhang](https://zeyuzhang.com/); academic advisor: Prof. [Song-Chun Zhu](https://zhusongchun.net/)

<span class="anchor" id="service"></span>

# 🤝 Academic Service

- Reviewer, IEEE Transactions on Automation Science and Engineering (**T-ASE 2026**)
- Reviewer, European Conference on Computer Vision (**ECCV 2026**)
- Reviewer, IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR 2026**)
- Reviewer, Conference on Neural Information Processing Systems (**NeurIPS 2025**)
- Reviewer, IEEE Robotics and Automation Letters (**RA-L 2024**)
- Reviewer, IEEE International Conference on Robotics and Automation (**ICRA 2024**)

<span class="anchor" id="honors"></span>

# 🏆 Selected Awards & Honors

- **2026** — Grand Prize, 14th Hubei Challenge Cup College Student Entrepreneurship Plan Competition, Huazhong University of Science and Technology
- **2025** — Best Poster Award, 4th Workshop on Mobile Manipulation and Embodied Intelligence (MOMA.v4), IROS 2025
- **2025** — Champion, Solo Dance, 2025 World Humanoid Robot Games
- **2025** — Best Paper Award (First Prize), 1st International Conference on General Artificial Intelligence
- **2025** — National Scholarship for Ph.D. Students, Huazhong University of Science and Technology
- **2025** — Outstanding Graduate Student, Huazhong University of Science and Technology
- **2023** — First-class Comprehensive Academic Scholarship, Shanghai Jiao Tong University
- **2022** — First-class Comprehensive Academic Scholarship, Shanghai Jiao Tong University
- **2021** — National Scholarship for Undergraduates, Ocean University of China
- **2021** — First-class Scholarship for Academic Excellence, Ocean University of China
- **2021** — Outstanding Individual of the 10th Role Model Program, College of Engineering, OUC
- **2021** — Outstanding Bachelor's Thesis Award, Ocean University of China
- **2019** — First-class Scholarship for Academic Excellence, Ocean University of China
- **2019** — Scholarship for Social Practice, Ocean University of China
- **2019** — First Prize, 13th National College Student Energy Saving and Emission Reduction Competition
- **2019** — Honorable Mention (Second Prize), Mathematical Contest in Modeling (MCM)
- **2019** — Second Prize, 10th National Undergraduate Mathematics Competition
- **2019** — First Prize, 9th Shandong Undergraduate Mathematics Competition
- **2019** — First Prize, 2nd Shandong Undergraduate Physics Competition
- **2018** — First-class Scholarship for Academic Excellence, Ocean University of China
- **2018** — Scholarship for Technological Innovation, Ocean University of China

---

This website is based on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template.
