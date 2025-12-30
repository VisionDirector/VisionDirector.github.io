# VisionDirector

This is the repository that contains source code for the [VisionDirector project website](https://your-org.github.io/VisionDirector/).

**VisionDirector: Vision-Language Guided Closed-Loop Refinement for Generative Image Synthesis**

[Meng Chu](https://github.com/your-org)<sup>1</sup>, Senqiao Yang<sup>2</sup>, Haoxuan Che<sup>3*†</sup>, Suiyun Zhang<sup>3</sup>, Xichen Zhang<sup>1</sup>, Shaozuo Yu<sup>2</sup>, Haokun Gui<sup>1</sup>, Zhefan Rao<sup>1</sup>, Dandan Tu<sup>3</sup>, Rui Liu<sup>3*</sup>, Jiaya Jia<sup>1</sup>

<sup>1</sup>HKUST, <sup>2</sup>CUHK, <sup>3</sup>Huawei Research

<sup>*</sup>Corresponding authors

## Abstract

Professional image creation often relies on long, multi-goal instructions specifying global composition, local object placement, typography, and stylistic constraints. While modern diffusion models achieve strong visual fidelity, they frequently fail to satisfy such tightly coupled objectives.

To systematically expose this gap, we introduce **LongGoalBench (LGBench)**, a dual-modality benchmark comprising 2,000 text-to-image and image-to-image tasks with over 29,000 annotated goals and automated goal-level verification.

We further propose **VisionDirector**, a vision-language guided closed-loop framework that decomposes long instructions into structured goals, dynamically plans generation or editing actions, and verifies goal satisfaction after each step without retraining diffusion backbones.

## Links

- 📄 [Paper (arXiv)](https://arxiv.org/abs/2512.19243)
- 🌐 [Project Page](https://your-org.github.io/VisionDirector/)
- 💻 [Code](https://github.com/your-org/VisionDirector)
- 📊 [LGBench Dataset](https://github.com/your-org/LGBench)

## Citation

If you find VisionDirector useful for your work, please cite:

```bibtex
@article{chu2026visiondirector,
  title   = {VisionDirector: Vision-Language Guided Closed-Loop Refinement for Generative Image Synthesis},
  author  = {Chu, Meng and Yang, Senqiao and Che, Haoxuan and Zhang, Suiyun and Zhang, Xichen and Yu, Shaozuo and Gui, Haokun and Rao, Zhefan and Tu, Dandan and Liu, Rui and Jia, Jiaya},
  journal = {CVPR},
  year    = {2026}
}
```

## Website License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

Website template adapted from [Nerfies](https://github.com/nerfies/nerfies.github.io).
