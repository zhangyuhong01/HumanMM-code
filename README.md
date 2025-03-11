# [CVPR 2025] HumanMM: Global Human Motion Recovery from Multi-shot Videos

[Yuhong Zhang](https://scholar.google.com/citations?user=oV7sxpYAAAAJ&hl=zh-CN)💡, [Guanlin Wu](https://guanlinwu123.github.io)💡, [Ling-Hao Chen](https://lhchen.top/), [Zhuokai Zhao](https://zhuokai-zhao.com/), [Jing Lin](https://jinglin7.github.io/), Xiaoke Jiang, Jiamin Wu, Zhuoheng Li, [Hao Frank Yang](https://www.haofrankyang.net), [Haoqian Wang](https://www.sigs.tsinghua.edu.cn/whq_en/main.htm)🌟, [Lei Zhang](https://www.leizhang.org/)🌟

💡Equal Contribution, 🌟Corresponding Author  


📄 **[arXiv Paper](https://arxiv.org/abs/2503.07597)**, 📂 **[Dataset](https://huggingface.co/datasets/YuhongZhang/ms-Motion)**, 💻 **[Code Repository](https://github.com/zhangyuhong01/HumanMM-code)**, 🌍 **[Project Page](https://zhangyuhong01.github.io/HumanMM/)**


## 🚀 Demo

We present the first method capable of recovering **globally consistent human motion** from multi-shot videos while maintaining **cross-view motion coherence** across sequential video clips shot by varying camera viewpoints. 
![image](https://github.com/user-attachments/assets/9feec867-40a9-4082-b059-5299658283d6)

👉 [Watch the Demo](https://www.youtube.com/watch?v=gG6QVITc82U)


## 📝 Abstract

We present a novel framework designed to reconstruct **long-sequence 3D human motion** in **world coordinates** from **in-the-wild videos with multiple shot transitions**. These long-sequence in-the-wild motions are highly valuable for **motion generation and understanding**, but are challenging to recover due to **abrupt shot transitions, partial occlusions, and dynamic backgrounds**.

Existing methods primarily focus on **single-shot videos** or **camera-space multi-shot alignment**, which fail to ensure global motion continuity. In this work, we integrate **enhanced camera pose estimation** with **Human Motion Recovery (HMR)** by incorporating a **shot transition detector** and a **robust alignment module** for accurate **pose and orientation continuity across shots**.

We also introduce a **custom motion integrator** to mitigate **foot sliding** and maintain **temporal consistency**. Evaluations on our created **multi-shot dataset** demonstrate the **robustness** of our approach in reconstructing realistic human motion in world coordinates.


## 🙏 Acknowledgements

This work was partially funded by the Shenzhen Science and Technology Project under Grant KJZD20240903103210014. 
We sincerely thank Ms. Yaxin Chen from IDEA Research for contributing the expressive dance motion used in our demo presentation.


## 📖 Citation

If you find our work useful, please consider citing:

```bibtex
@misc{zhang2025humanmmglobalhumanmotion,
      title={HumanMM: Global Human Motion Recovery from Multi-shot Videos},
      author={Yuhong Zhang and Guanlin Wu and Ling-Hao Chen and Zhuokai Zhao and Jing Lin and Xiaoke Jiang and Jiamin Wu and Zhuoheng Li and Hao Frank Yang and Haoqian Wang and Lei Zhang},
      year={2025},
      eprint={2503.07597},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2503.07597},
}
```

