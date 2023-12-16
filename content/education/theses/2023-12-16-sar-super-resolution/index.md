---
title: Investigation of super-resolution methods for high-resolution SAR imagery
date: 2023-11-06
show_date: false
show_related: true
profile: false
tags: ['sar','super-resolution']
---

The widespread availability of Satellite data from the Sentinel missions has significantly propelled research in the convergence  of Earth Observation and Machine Learning, leading to groundbreaking advancements in crucial applications like rapid flood mapping [1], burnt scar mapping [2], and land cover classification [3]. Many applications, however, would benefit from a finer spatial resolution than the one offered by the Sentinel missions. In this thesis, the student will engage with state-of-the-art super-resolution methods [4,5,6], attempting to enhance SAR data from the Sentinel-1 mission (~10m per pixel), providing meaningful high resolution SAR images (~1m per pixel). As a first step the student will create a dataset, aligning high-resolution SAR from commercial products[7] with freely available low-resolution Sentinel-1 data. The resulting super-resolution method will be meticulously evaluated both in terms of its ability to address unseen downstream tasks as well as the soundness of the resulting high-resolution SAR image.

Supervisor: Nikolaos Ioannis Bountos

contact: bountos@noa.gr , ipapoutsis@noa.gr

[1] Bountos, Nikolaos Ioannis, et al. "Kuro Siwo: 12.1 billion $ m^ 2$ under the water. A global multi-temporal satellite dataset for rapid flood mapping." arXiv preprint arXiv:2311.12056 (2023).

[2] Sdraka, Maria, et al. "FLOGA: A machine learning ready dataset, a benchmark and a novel deep learning model for burnt area mapping with Sentinel-2." arXiv preprint arXiv:2311.03339 (2023).

[3] Papoutsis, Ioannis, et al. "Benchmarking and scaling of deep learning models for land cover image classification." ISPRS Journal of Photogrammetry and Remote Sensing 195 (2023): 250-268.

[4] Zamfir, Eduard, Marcos V. Conde, and Radu Timofte. "Towards real-time 4k image super-resolution." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023.

[5] Gao, Sicheng, et al. "Implicit diffusion models for continuous super-resolution." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023.

[6] Park, JoonKyu, Sanghyun Son, and Kyoung Mu Lee. "Content-aware local gan for photo-realistic super-resolution." Proceedings of the IEEE/CVF International Conference on Computer Vision. 2023.

[7] https://registry.opendata.aws/umbra-open-data/