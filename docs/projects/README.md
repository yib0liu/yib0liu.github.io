<!-- ---
pageClass: projects-page
--- -->

## Projects

<ProjectCard image="/projects/gpu.png" >

  **Lock-free Linked List Library for GPUs**
  
  The **first** library supporting all singly linked list operations on GPUs with CUDA.
  
  Achieveing 141x speedup for insertions and deletions compared to sequential operations.

  [[GitHub](https://github.com/xDarkLemon/concurrent_linked_list_cuda)] [[Report](/files/gpu_final_report.pdf)]

</ProjectCard>

<ProjectCard image="/projects/deform.png" >

  **A Python Implementation for *Harmonic Coordinates for Character Articulation***

  Implemented a Python-based framework for harmonic coordinates to enable smooth and natural deformation in character articulation. 
  
  The system allows intuitive control of complex mesh movements while preserving geometric consistency.
  
  [[GitHub](https://github.com/xDarkLemon/Harmonic-Coordinates-for-Character-Articulation)]

</ProjectCard>

<ProjectCard image="/projects/09.png">

  **Expressive Power, Generalization, and Optimization of Graph Neural Networks: A Survey**

Summarized the theoretic frameworks of GNN’s expressive power; summarized the generalization bounds, the generalization ability of different GNNs, and the methods to improve generalization ability; stated the explanation of over-fitting problem and summarized the optimization methods.

[[Paper](/files/GNN_Survey.pdf)]

</ProjectCard>

<ProjectCard image="/projects/08.png">

  **2021 iFlytek Bird Song Recognition Competition**

  The Bird Song Recognition Challenge aims to advance automated bird song recognition technology by predicting the bird species present in each test audio clip. 
  
  We explored various feature extraction methods and data augmentation techniques, applying image classification algorithms to audio spectrograms. Multiple models were evaluated, including CNN, CNN feature extraction combined with sequence models (LSTM/Transformer), and Vision Transformer. Ultimately, model ensembles were employed to enhance performance.

<!-- 鸟类鸣叫声识别挑战赛旨在增强自动鸟类鸣叫声识别技术，预测出每个测试音频中出现的鸟类物种。比赛中，探索了多种特征提取方法、数据增强方法，对音频频谱图使用图像分类算法进行分类，探索了多种模型，包括CNN，CNN特征提取+序列模型（LSTM/Transformer），以及Vision Transformer。最终使用模型集成提升效果。 -->

  [[Blog(CN)](/article/bird_song.html)] [[Code](https://github.com/xDarkLemon/BirdRec)]

</ProjectCard>

<!-- <ProjectCard image="/projects/10.png" >

  **COIG-PC: Chinese Open Instruction Generalist Prompt Collection**
  - Collected prompts to facilitate the fine-tuning and optimization of Chinese language models.
  
  [[Huggingface Dataset](https://huggingface.co/datasets/BAAI/COIG-PC)]

</ProjectCard> -->


<style lang="stylus">

.projects-page
  background-color #fafbfc

</style>