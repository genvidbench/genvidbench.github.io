<div align="center">
  <h2>GenVidBench: A Challenging Benchmark for Detecting AI-Generated Video</h2>

  <p>Zhen-Liang Ni*, Qiangyu Yan*, Tianning Yuan, Mouxiao Huang, Yehui Tang</p>
  <p>Hailin Hu✉️, Xinghao Chen✉️, Yunhe Wang✉️</p>
</div>


<p align="center">
  <a href="https://github.com/genvidbench/GenVidBench" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Repository-blue?logo=github" alt="GitHub">
  </a>
  <a href="https://arxiv.org/abs/2407.12345" target="_blank">
    <img src="https://img.shields.io/badge/Paper-arXiv-red?logo=arxiv" alt="Paper">
  </a>
  <a href="https://github.com/genvidbench/GenVidBench" target="_blank">
    <img src="https://img.shields.io/badge/Download-Dataset-green?logo=download" alt="Download">
  </a>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/8e34a3fe-5dfa-4424-8657-7290d5a0248a" alt="微信截图_20240908221413">
</div>

Instruction
---
The rapid advancement of video generation models has made it increasingly challenging to distinguish AI-generated videos from real ones. This issue underscores the urgent need for effective AI-generated video detectors to prevent the dissemination of false information through such videos. However, the development of high-performance generative video detectors is currently impeded by the lack of large-scale, high-quality datasets specifically designed for generative video detection. To this end, we introduce GenVidBench, a challenging AI-generated video detection dataset with several key advantages: 1) Cross Source and Cross Generator: The cross-generation source mitigates the interference of video content on the detection. The cross-generator ensures diversity in video attributes between the training and test sets, preventing them from being overly similar. 2) State-of-the-Art Video Generators: The dataset includes videos from 8 state-of-the-art AI video generators, ensuring that it covers the latest advancements in the field of video generation. 3) Rich Semantics: The videos in GenVidBench are analyzed from multiple dimensions and classified into various semantic categories based on their content. This classification ensures that the dataset is not only large but also diverse, aiding in the development of more generalized and effective detection models. We conduct a comprehensive evaluation of different advanced video generators and present a challenging settings.

News
---
2025/02/11: Update the download link and fixed the bug. Note that we uploaded the ID of Pair1 in the original dataset to path 'data/sampled_dataset_uuid.zip'. Due to copyright restrictions, We can't provide these videos directly. You can select the corresponding video from these three data sets Vript/HD-VG-130M/VidProM based on these IDs. 

2025/01/25: The training code is released.

2025/01/20: The paper is published at https://arxiv.org/abs/2501.11340.

Reference
---
✨ If you find our data helpful, please cite our paper or point a star. Thank you very much!
```
@misc{ni2025genvidbenchchallengingbenchmarkdetecting,
      title={GenVidBench: A Challenging Benchmark for Detecting AI-Generated Video}, 
      author={Zhenliang Ni and Qiangyu Yan and Mouxiao Huang and Tianning Yuan and Yehui Tang and Hailin Hu and Xinghao Chen and Yunhe Wang},
      year={2025},
      eprint={2501.11340},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2501.11340}, 
}
```

License
---
CC BY-NC 4.0
