---
pageClass: home-page
# some data for the components

name: Yibo Liu
profile: /profile/profile2025.jpeg
bio: CS PhD Candidate @ UVic
email: liuyibo (at) uvic (dot) ca

socials:
  - title: google-scholar
    icon: "/icons/icons8-google-scholar-48.svg"
    link: https://scholar.google.com/citations?user=FQExy98AAAAJ&hl=en&oi=ao

  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/yib0liu

  - title: linkedin
    icon: "/icons/linkedin.svg"
    link: https://www.linkedin.com/in/yibo-liu-5a60a21b5/
    
  - title: twitter
    icon: "/icons/twitter.svg"
    link: https://twitter.com/_liuyibo

  - title: CV
    icon: "/icons/cv.svg"
    link: /files/Yibo_Liu_CV.pdf

actions:  # buggy? not working?
  - text: Projects
    link: /projects/
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About

Currently, I am a Ph.D. student in Computer Science at University of Victoria ([UVIC](https://www.uvic.ca/)), working with [Dr. Teseo Schneider](http://web.uvic.ca/~teseo/) . Prior to this, I obtained my M.S. in Computer Science from New York University ([NYU](https://www.nyu.edu/)) and B.Eng. in Electronic Engineering from Beijing University of Posts and Telecommunications ([BUPT](https://www.bupt.edu.cn/)). Previously, I have interned at Microsoft Research Asia ([MSRA](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/)). 

My current research focuses on computer graphics, physics-based simulation, geometry processing, particularly on learning-based paradigms to enhance simulations.

## Experience
**Univerisity of Victoria** | Sept 2023 - Present  <br/>
PhD student in Computer Science \
Supervisor: [Dr. Teseo Schneider](http://web.uvic.ca/~teseo/) \
Physics-informed neural framework for fluids simulation; Crowds animation and motion synthesis; Geometry processing.

**Geometric Computing Lab, New York University** | 2022 - 2023 <br/>
Research Assistant \
Supervisors: [Dr. Teseo Schneider](http://web.uvic.ca/~teseo/) and [Dr. Daniele Panozzo](https://cims.nyu.edu/gcl/daniele.html) \
GPU acceleration for contact simulations in [PolyFEM](http://github.com/polyfem/polyfem).

**Microsoft Research Asia** | Aug 2020 - Feb 2021  <br/>
Research Intern at *Data, Knowledge and Intelligence* group, full-time, onsite \
  Tabular data intelligence with reinforcement learning.

**CILVR Lab, New York University** | Mar 2020 - May 2021 <br/> 
Research Assistant \
Supervisors: [Dr. Iacer Calixto](http://iacercalixto.github.io) and [Dr. Clara Vania](http://claravania.github.io)\
Learning robust mulilingual multimodal knowledge graph representations.

<!-- - **Center for Speech and Language Technologies, Tsinghua University** | 2018 - 2019<br/>
Research intern, supervised by [Prof. Dr. Dong Wang](http://wangd.cslt.org)  \
  Conducting research on poetry generation with rythm (YunLv) as soft constraint. -->

## Publication

<ProjectCard image="/projects/fluidrep.png">

  **Neural Kinematic Bases for Fluids**
  
  **Yibo Liu**, Zhixin Fang, Sune Darkner, Noam Aigerman, Kenny Erleben, Paul Kry, Teseo Schneider
  
  **[SIGGRAPH Asia 2025]** *In ACM SIGGRAPH Asia Conference Proceedings* Sept. 2025.

  [[Paper](https://arxiv.org/abs/2504.15657)]

</ProjectCard>

<ProjectCard image="/projects/crowds.png">

  **Emergent Crowds Dynamics from Language-Driven Multi-Agent Interactions**

  *Under Review*
  
  [[Paper](https://arxiv.org/abs/2508.15047)]

</ProjectCard>

<ProjectCard image="/projects/01.png" >
<!-- <ProjectCard image="/projects/01.png" hideBorder=true> -->

  **MMMU: A Massive Multi-discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI**
  
  Xiang Yue, Yuansheng Ni, Kai Zhang, Tianyu Zheng, Ruoqi Liu, Ge Zhang, Samuel Stevens, Dongfu Jiang, Weiming Ren, Yuxuan Sun, Cong Wei, Botao Yu, Ruibin Yuan, Renliang Sun, Ming Yin, Boyuan Zheng, Zhenzhu Yang, **Yibo Liu**, Wenhao Huang, Huan Sun, Yu Su, Wenhu Chen

**[CVPR 2024]** *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, pp. 9556-9567, Jun. 2024

  [[Paper](https://arxiv.org/abs/2311.16502)] [[Website](https://mmmu-benchmark.github.io)]

</ProjectCard>

<ProjectCard image="/projects/02.png" >

  **Endowing Language Models with Multimodal Knowledge Graph Representations**

  Ningyuan Huang, Yash R. Deshpande, **Yibo Liu**, Houda Alberts, Kyunghyun Cho, Clara Vania, Iacer Calixto

  **[preprint]** *arXiv* 2206.13163, Jun. 2022

  [[Paper](https://arxiv.org/abs/2206.13163)]

</ProjectCard>

<ProjectCard image="/projects/03.png" >

  **VisualSem: a high-quality knowledge graph for vision and language**

Houda Alberts, Ningyuan Huang, Yash Deshpande, **Yibo Liu**, Kyunghyun Cho, Clara Vania, Iacer Calixto

**[EMNLP 2021 workshop]** *Proceedings of the 1st Workshop on Multilingual Representation Learning*, pp. 138-152, Nov. 2021.

  [[Paper](https://aclanthology.org/2021.mrl-1.13.pdfs)] 

</ProjectCard>

<ProjectCard image="/projects/04.png" >

  **Table2Charts: Recommending Charts by Learning Shared Table Representations**

 Mengyu Zhou, Qingtao Li, Xinyi He, Yuejiang Li , **Yibo Liu**, Wei Ji, Shi Han, Yining Chen, Daxin Jiang, Dongmei Zhang.

**[SIGKDD 2021]** *Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining*, pp. 2389-2399, Aug. 2021

  [[Paper](https://dl.acm.org/doi/pdf/10.1145/3447548.3467279)] [[Code](https://github.com/microsoft/Table2Charts)]

</ProjectCard>

## Open-Source Contribution

[→ Full list](/opensource/)

<!-- <ProjectCard image="/projects/ntm.png" >

  **Neural Topic Model Library**
  - The first Python library containing all cutting-edge neural topic models, collaborated with [Leilan Zhang](https://scholar.google.com/citations?user=FDeI9yUAAAAJ&hl=zh-CN).
  - Refactored the codebase framework and rewrote the interfaces to provide APIs compatible with the Gensim LDA library.

  [[GitHub | 431 star :star: | 80 fork](https://github.com/zll17/Neural_Topic_Models/tree/dev_b)]

</ProjectCard> -->

<ProjectCard image="/projects/polyfem.png" >

  **PolyFEM**
- Add simulation for pyramid meshes.
- Add GPU acceleration for contact simulations ([PolySolve](https://github.com/polyfem/polysolve)).
- Add support for prism and pyramid output ([Paraviewo](https://github.com/polyfem/paraviewo)).

[[GitHub | 589 star :star: | 93 fork](https://github.com/polyfem/polyfem)]

</ProjectCard>

## Projects

[→ Full list](/projects/)

<ProjectCard image="/projects/gpu.png" >

  **Lock-free Linked List Library for GPUs**
  - This project develops a CUDA-based singly linked list library, with all operations running on GPUs to fully exploit their parallelism.
  - It introduces the **first** lock-free linked list algorithm on CUDA, adapted from prior implementations on multi-core CPUs.

  [[GitHub](https://github.com/xDarkLemon/concurrent_linked_list_cuda)] [[Report](/files/gpu_final_report.pdf)]

</ProjectCard>

## Talks

**Oct 2021** I presented our paper *["VisualSem: a high-quality knowledge graph for vision and language"](/files/MRL_slides.pdf)* at [EMNLP Workshop on Multilingual Representation Learning 2021](https://www.aclweb.org/portal/content/1st-workshop-multilingual-representation-learning-mrl-emnlp).


## Peer Review Service
International Conference on Learning Representations (ICLR) Reviewer, 2026

AAAI Conference on Artificial Intelligence (AAAI) Reviewer, 2025

International Conference on Learning Representations (ICLR) Reviewer, 2025

Transactions on Visualization and Computer Graphics (TVCG) Reviewer, 2024

## Volunteer
**Judge | NASA Space Apps Challenges 2025 Victoria** | Victoria, Canada | Oct 2025

**Student Volunteer | SIGGRAPH Asia 2024** | Tokyo, Japan | Dec 2024

## Teaching Assistantship
Give lectures, lead lab sessions, grade assignments, proctor exams for the following courses:

**Geometry Modeling** | 2026 winter

**Introduction to Computer Graphics** | 2025 summer

**Data Mining** | 2025 spring, 2024 winter, 2023 fall

**Introduction to C++** | 2024 fall

**Software Architecture** | 2024 fall

## Skills
**Research Expertise:** Physics-Based Simulation; Geometry Processing; Fluids Simulation; Crowds Animation; Character Animation; Physics-informed Neural Networks; Multimodal LLM Understanding; Knowledge Base; Graph Neural Networks;

**Graphics:** C/C++; Blender, Unity, Paraview; Parallel Computing (CUDA, MPI);

**ML/NLP:** Python; PyTorch, Tensorflow; Hugging Face Transformers, SpaCy, NLTK, Gensim;  OpenCV, PIL, Librosa; NumPy, Pandas, HDF5, SciPy, Scikit Learn;

**DevOps:** C# (Unity, .NET); Java; HTML/CSS, Django, MySQL; Bash Shell, Git, Linux;

**Hardware:** VHDL, Microcontroller programming, STM32

<!-- ## Blender Art Gallery -->


<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
