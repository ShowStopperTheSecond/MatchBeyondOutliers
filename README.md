

# Beyond Outlier Removal: Integrated Ensemble Matching for Accurate Image Keypoint Correspondence

This repository hosts the code and resources related to our paper. Stay tuned for updates!

Abstract
Our work introduces a novel approach to enhance image keypoint correspondence by integrating ensemble matching techniques, moving beyond traditional outlier removal strategies. This method aims to improve accuracy and robustness in applications such as computer vision and feature matching.


### Enhanced ALIKED
https://github.com/ShowStopperTheSecond/EnhancedALIKED


### Training Enhanced ALIKED on Kaggle
https://www.kaggle.com/code/javidtheimmortal/training-enhanced-aliked

```
@article{norouzi2025,
title = {Beyond outlier removal: Integrated ensemble matching for accurate image keypoint correspondence},
journal = {Knowledge-Based Systems},
volume = {316},
pages = {113343},
year = {2025},
issn = {0950-7051},
doi = {https://doi.org/10.1016/j.knosys.2025.113343},
url = {https://www.sciencedirect.com/science/article/pii/S0950705125003909},
author = {Javid Norouzi and Mohammad Sadegh Helfroush and Alireza Liaghat and Habibollah Danyali},
keywords = {Feature matching, Feature description, Computer vision},
abstract = {This paper presents a novel two-tier matching approach for robust feature correspondence and geometric transformation estimation in computer vision tasks. Our method combines sub-descriptor matching and multi-descriptor ensembling to significantly improve the accuracy and reliability of keypoint correspondences across images. Our approach is evaluated on both classic hand-crafted algorithms and deep learning-based methods using the HPatches, IMC2022, and YFCC100M datasets. We use a pretrained network and enhance it to incorporate additional descriptor heads optimized for our matching strategy. The two-tier matching strategy enables direct geometric transformation estimation without separate outlier removal in many cases, potentially streamlining computer vision pipelines. Results demonstrate that our approach substantially outperforms traditional single-descriptor methods, achieving over 95% correct matches for classic algorithm combinations and up to 96% for our enhanced learning-based approaches. Our approach can establish reliable correspondences without making any assumption about the mathematical relation between the matches. Additionally, we explore applications of our method in scene matching.}
}

```
