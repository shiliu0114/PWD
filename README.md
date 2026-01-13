# PWD: Prior-Guided and Wavelet-Enhanced Diffusion Model for Fast Limited-Angle Imaging on Dental CT
[![arXiv](https://img.shields.io/badge/arXiv-2507.05317-b31b1b.svg)](https://arxiv.org/abs/2507.05317)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
This repository contains the official implementation of the paper **"PWD: Prior-Guided and Wavelet-Enhanced Diffusion Model for Fast Limited-Angle imaging on Dental CT"**.
## Abstract
Generative diffusion models have received increasing attention in medical imaging, particularly in limited-angle computed tomography (LACT). Standard diffusion models achieve high-quality image reconstruction，but require a large number of sampling steps during inference, resulting in substantial computational overhead.Although skip-sampling strategies have been proposed to improve efficiency, they often lead to loss of fine structuraldetails. To address this issue, we propose a prior information embedding and wavelet feature fusion fast sampling diffusion model for LACT reconstruction. The PWD enables efficient sampling while preserving reconstruction fidelity in LACT, and effectively mitigates the degradation
typically introduced by skip-sampling. Specifically, during the training phase, PWD maps the distribution of LACT images to that of fully sampled target images, enabling the model to learn structural correspondences between them.During inference, the LACT image serves as an explicit prior to guide the sampling trajectory, allowing for high quality reconstruction with significantly fewer steps. In addition, PWD performs multi-scale feature fusion in the wavelet domain, effectively enhancing the reconstruction of fine details by leveraging both low-frequency and high frequency information. Quantitative and qualitative evaluations on clinical dental arch CBCT and periapical datasets demonstrate that PWD outperforms existing methods under the same sampling condition. Using only 50 sampling steps, PWD achieves at least 1.7 dB improvement in PSNR and 10% gain in SSIM.








## Citation
```bibtex
@article{liu2025pwd,
  title={PWD: Prior-Guided and Wavelet-Enhanced Diffusion Model for Fast Limited-Angle imaging on Dental CT},
  author={Liu, Yi and Wen, Yiyang and Zhou, Zekun and Ma, Junqi and Wang, Linghang and Yao, Yucheng and Shi, Liu and Liu, Qiegen},
  journal={arXiv preprint arXiv:2507.05317},
  year={2025}
}
