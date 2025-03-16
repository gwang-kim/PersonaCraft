## PersonaCraft: Personalized and Controllable Full-Body Multi-Human Scene Generation Using Occlusion-Aware 3D-Conditioned Diffusion</sub>

[![arXiv](https://img.shields.io/badge/arXiv-2411.18068-red)](https://arxiv.org/abs/2411.18068) [![project_page](https://img.shields.io/badge/-project%20page-green)](https://gwang-kim.github.io/persona_craft/)


<p align="center">
  <img src="assets/0_teaser.jpg" />
</p> 



> **PersonaCraft: Personalized and Controllable Full-Body Multi-Human Scene Generation Using Occlusion-Aware 3D-Conditioned Diffusion**<br>
> [Gwanghyun Kim](https://gwang-kim.github.io/)\*, [Suh Yoon Jeon](https://www.linkedin.com/in/suhyoonjeon/)*, [Seunggyu Lee](https://www.linkedin.com/in/seunggyu-lee-18163b263/), [Se Young Chun](https://icl.snu.ac.kr/pi) <br>
> Seoul National University <br>
> 
>**Abstract**: <br>
We present **PersonaCraft**, a framework for controllable and occlusion-robust full-body personalized image synthesis of multiple individuals in complex scenes. Current methods struggle with occlusion-heavy scenarios and complete body personalization, as 2D pose conditioning lacks 3D geometry, often leading to ambiguous occlusions and anatomical distortions, and many approaches focus solely on facial identity. In contrast, our PersonaCraft integrates diffusion models with 3D human modeling, employing SMPLx-ControlNet, to utilize 3D geometry like depth and normal maps for robust 3D-aware pose conditioning and enhanced anatomical coherence. To handle fine-grained occlusions, we propose Occlusion Boundary Enhancer Network that exploits depth edge signals with occlusion-focused training, and Occlusion-Aware Classifier-Free Guidance strategy that selectively reinforces conditioning in occluded regions without affecting unoccluded areas. PersonaCraft can seamlessly be combined with Face Identity ControlNet, achieving full-body multi-human personalization and thus marking a significant advancement beyond prior approaches that concentrate only on facial identity. Our dual-pathway body shape representation with SMPLx-based shape parameters and textual refinement, enables precise full-body personalization and flexible user-defined body shape adjustments. Extensive quantitative experiments and user studies demonstrate that PersonaCraft significantly outperforms existing methods in generating high-quality, multi-person images with accurate personalization and robust occlusion handling.

## Notice 

- The code is comming soon!



## User-Defined Body Shape Control

<p align="center">
  <img src="assets/0_udbc.jpg" />
</p> 



## PersonaCraft with Style LoRAs 

<p align="center">
  <img src="assets/0_style_lora.jpg" />
</p> 

