<div align="center">
  <h1><p>GenVidBench: A Challenging Benchmark for Detecting<br>AI-Generated Video [AAAI2026]</p></h1>
  <p>Zhen-Liang Ni*, Qiangyu Yan*, Mouxiao Huang, Tianning Yuan, Yehui Tang</p>
  <p>Hailin Hu✉️, Xinghao Chen✉️, Yunhe Wang✉️</p>
  <p>
  ▶ Huawei Noah's Ark Lab
  </p>
</div>


<p align="center">
  <a href="https://github.com/genvidbench/GenVidBench" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Repository-blue?logo=github" alt="GitHub">
  </a>
  <a href="https://arxiv.org/abs/2501.11340" target="_blank">
    <img src="https://img.shields.io/badge/Paper-arXiv-red?logo=arxiv" alt="Paper">
  </a>
  <a href="https://huggingface.co/datasets/jian-0/GenVidBench/tree/main" target="_blank">
    <img src="https://img.shields.io/badge/Download-Dataset-green?logo=download" alt="Download">
  </a>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/8e34a3fe-5dfa-4424-8657-7290d5a0248a" alt="微信截图_20240908221413">
</div>

Instruction
---
<div style="text-align: justify;">
  <p>
    The rapid advancement of video generation models has made it increasingly challenging to distinguish AI-generated videos from real ones. This issue underscores the urgent need for effective AI-generated video detectors to prevent the dissemination of false information through such videos. However, the development of high-performance generative video detectors is currently impeded by the lack of large-scale, high-quality datasets specifically designed for generative video detection. To this end, we introduce GenVidBench, a challenging AI-generated video detection dataset with several key advantages:
  </p>
  <ul>
    <li><strong>Cross Source and Cross Generator:</strong> Mitigates the interference of video content on the detection. The cross-generator ensures diversity in video attributes between the training and test sets.</li>
    <li><strong>State-of-the-Art Video Generators:</strong> Includes videos from 8 state-of-the-art AI video generators.</li>
    <li><strong>Rich Semantics:</strong> Videos are analyzed from multiple dimensions and categorized by content.</li>
  </ul>
  <p>
    We conduct a comprehensive evaluation of different advanced video generators and present a challenging setting.
  </p>
</div>
<div align="center">
  <img width="1704" height="400" alt="data_sum" src="https://github.com/user-attachments/assets/54058a77-77bc-42a6-9a31-aef60ee7c4cc" />
</div>

Results
---
<div align="center">
  <img width="1200" height="400" alt="result_6m" src="https://github.com/user-attachments/assets/00419f03-7068-4e02-9226-e15c58e116e4" />

  <img width="550" height="400" alt="f1" src="https://github.com/user-attachments/assets/4de33683-160e-4966-8a95-6fca39cfc869" />

  <img width="550" height="400" alt="results_143k" src="https://github.com/user-attachments/assets/787c131c-78b2-4e09-b4eb-0b3c6755e19a" />
</div>

News
---
<div style="text-align: justify;">
  <p>
  2025/11/09: Good news! Our paper has been accepted by AAAI 2026. And in the near future we'll release the latest paper and a 6.7M dataset, which will be the largest dataset in the field.
  </p>
  <p>
  2025/02/11: Update the download link and fixed the bug. Note that we uploaded the ID of Pair1 in the original dataset to the file path 'data/sampled_dataset_uuid.zip'. Due to copyright restrictions, We can't provide these videos directly. You can select the corresponding video from these three data sets Vript/HD-VG-130M/VidProM based on these IDs. 
  </p>
  <p>
  2025/01/25: The training code is released.
  </p>
  <p>
  2025/01/20: The paper is published at Arxiv.
  </p>
</div>




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
