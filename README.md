# Awesome-Image-Forensics
A curated list of image forensics works (including image manipulation dataset, image manipulation detection, image manipulation localization, etc.) and related resources. This is inspired by [Awesome-FAS](https://github.com/RizhaoCai/Awesome-FAS), [Awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [Awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [Awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), [Awesome-NAS](https://github.com/D-X-Y/Awesome-AutoDL) and [Awesome-Pruing](https://github.com/he-y/Awesome-Pruning).

Please feel free to pull requests or open an issue to add papers.

# Contents
- [Databases](#databases)
- [Manipulation-Detection-And-Localization-Methods](#Manipulation-Detection-And-Localization-Methods)

# Databases
|  Name   | Release year | Venue | Download | #Pristine | #Manipulated | #Copy-move | #Splicing | #Inpainting  | 
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Columbia](https://ieeexplore.ieee.org/abstract/document/4036658)|2006|ICME|[link](https://www.ee.columbia.edu/ln/dvmm/downloads/authsplcuncmp/)|183|180|0|180|0|
|[CASIAv1](https://ieeexplore.ieee.org/document/6625374)|2013|ChinaSIP|[github](https://github.com/namtpham/casia1groundtruth)|800|920|459|461|0|
|[CASIAv2](https://ieeexplore.ieee.org/abstract/document/6625374)|2013|ChinaSIP|[github](https://github.com/namtpham/casia2groundtruth)|7491|5123|3295|1828|0|
|[COVER](https://ieeexplore.ieee.org/abstract/document/7532339)|2016|ICIP|[github](https://github.com/wenbihan/coverage)|100|100|100|0|0|
|[NIST2016](https://www.nist.gov/system/files/documents/2017/09/07/nc2017evaluationplan_20170804.pdf)|2016|OpenMFC|[link](https://www.nist.gov/itl/iad/mig/nimble-challenge-2017-evaluation)|0|564|68|288|208|
|[DEFACTO](https://ieeexplore.ieee.org/abstract/document/8903181)|2019|EUSIPCO|[github](https://defactodataset.github.io/)|0|149k|19k|105k|25k|
|[IMD2020](https://openaccess.thecvf.com/content_WACVW_2020/html/w4/Novozamsky_IMD2020_A_Large-Scale_Annotated_Dataset_Tailored_for_Detecting_Manipulated_Images_WACVW_2020_paper.html)|2020|WACVW|[link](http://staff.utia.cas.cz/novozada/db/)|404|2010|-|-|-|

# Manipulation-Detection-And-Localization-Methods
## Year 2022
| Title | Release year | Venue | Modality | Pixel-level | Image-level | Code | 
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Image manipulation detection by multiple tampering traces and edge artifact enhancemen](https://www.sciencedirect.com/science/article/pii/S0031320322005064)|2023|Pattern Recognition|RGB&Noise|Y|N|-|
|[A Principled Design of Image Representation: Towards Forensic Tasks](https://ieeexplore.ieee.org/document/9881995)|2022|T-PAMI|RGB&DIR|Y|N|[github](https://github.com/ShurenQi/DIR)|
|[Towards JPEG-resistant Image Forgery Detection and Localization via Self-supervised Domain Adaptation](https://ieeexplore.ieee.org/abstract/document/9904872)|2022|T-PAMI|RGB&Noise|Y|Y|-|
|[MVSS-Net: Multi-View Multi-Scale Supervised Networks for Image Manipulation Detection](https://ieeexplore.ieee.org/abstract/document/9789576)|2022|T-PAMI|RGB&Noise|Y|Y|[github](https://github.com/dong03/MVSS-Net/tree/359ac66528d1231e542ac5b562303019e4d51832)|
|[ET: Edge-Enhanced Transformer for Image Splicing Detection](https://ieeexplore.ieee.org/abstract/document/9769936)|2022|SPL|RGB&Boundary|Y|N|-|
|[Learning JPEG Compression Artifacts for Image Manipulation Detection and Localization](https://link.springer.com/article/10.1007/s11263-022-01617-5)|2022|IJCV|RGB&Noise|Y|N|[github](https://github.com/mjkwon2021/CAT-Net)|
|[Robust Image Forgery Detection Against Transmission Over Online Social Networks](https://ieeexplore.ieee.org/abstract/document/9686650)|2022|T-IFS|RGB|Y|N|[github](https://github.com/HighwayWu/ImageForensicsOSN)|
|[PSCC-Net: Progressive Spatio-Channel Correlation Network for Image Manipulation Detection and Localization](https://ieeexplore.ieee.org/abstract/document/9819903)|2022|T-CSVT|RGB|Y|Y|[github](https://github.com/proteus1991/PSCC-Net)|
|[Objectformer for image manipulation detection and localization](https://openaccess.thecvf.com/content/CVPR2022/html/Wang_ObjectFormer_for_Image_Manipulation_Detection_and_Localization_CVPR_2022_paper.html)|2022|CVPR|RGB&Frequency|Y|Y|-|
|[Robust Image Forgery Detection Over Online Social Network Shared Images](https://openaccess.thecvf.com/content/CVPR2022/html/Wu_Robust_Image_Forgery_Detection_Over_Online_Social_Network_Shared_Images_CVPR_2022_paper.html)|2022|CVPR|RGB|Y|N|[github](https://github.com/HighwayWu/ImageForensicsOSN)|
|[JPEG Compression-aware Image Forgery Localization](https://dl.acm.org/doi/abs/10.1145/3503161.3547749)|2022|MM|RGB|Y|N|-|
|[Generic Image Manipulation Localization through the Lens of Multi-scale Spatial Inconsistence](https://dl.acm.org/doi/abs/10.1145/3503161.3548100)|2022|MM|RGB&Boundary|Y|N|-|
|[ESRNet: Efficient Search and Recognition Network for Image Manipulation Detection](https://dl.acm.org/doi/full/10.1145/3506853)|2022|TOMM|RGB|Y|N|[github](https://github.com/tampered816/tool)|
|[Learning to localize image forgery using end-to-end attention network](https://www.sciencedirect.com/science/article/pii/S0925231222011274)|2022|Neurocomputing|RGB&Frequency|Y|N|[github](https://github.com/sadaf-ali/-Learning-to-Localize-Image-Forgery-Using-End-to-End-Attention-Network)|

## Year 2021
| Title | Release year | Venue | Modality | Pixel-level | Image-level | Code | 
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Image Splicing Detection, Localization and Attribution via JPEG Primary Quantization Matrix Estimation and Clustering](https://ieeexplore.ieee.org/abstract/document/9622213)|2021|T-IFS|RGB|Y|Y|-|
|[Image Tampering Localization Using a Dense Fully Convolutional Network](https://ieeexplore.ieee.org/abstract/document/9393396)|2021|T-IFS|RGB|Y|N|[github](https://github.com/ZhuangPeiyu/Dense-FCN-for-tampering-localization/tree/4940eb341832940834ecde76a1c7482a786932fe)|
|[Multi-Task SE-Network for Image Splicing Localization](https://ieeexplore.ieee.org/abstract/document/9591639)|2021|T-CSVT|RGB|Y|N|[github](https://github.com/YulansZhang/Multi-task-SE-Network-for-Image-Splicing-Localization)|
|[Self-supervised Domain Adaptation for Forgery Localization of JPEG Compressed Images](https://openaccess.thecvf.com/content/ICCV2021/html/Rao_Self-Supervised_Domain_Adaptation_for_Forgery_Localization_of_JPEG_Compressed_Images_ICCV_2021_paper.html)|2021|ICCV|RGB|Y|Y|-|
|[Image Manipulation Detection by Multi-View Multi-Scale Supervision](https://openaccess.thecvf.com/content/ICCV2021/html/Chen_Image_Manipulation_Detection_by_Multi-View_Multi-Scale_Supervision_ICCV_2021_paper.html)|2021|ICCV|RGB&Noise|Y|Y|[github](https://github.com/dong03/MVSS-Net/tree/359ac66528d1231e542ac5b562303019e4d51832)|
|[TransForensics: Image Forgery Localization with Dense Self-Attention](https://openaccess.thecvf.com/content/ICCV2021/html/Hao_TransForensics_Image_Forgery_Localization_With_Dense_Self-Attention_ICCV_2021_paper.html)|2021|ICCV|RGB|Y|N|-|
|[CAT-Net: Compression artifact tracing network for detection and localization of image splicing](https://openaccess.thecvf.com/content/WACV2021/html/Kwon_CAT-Net_Compression_Artifact_Tracing_Network_for_Detection_and_Localization_of_WACV_2021_paper.html)|2021|WACV|RGB&Noise|Y|N|[github](https://github.com/mjkwon2021/CAT-Net)|
|[SPAN: Spatial pyramid attention network for image manipulation localization](https://link.springer.com/chapter/10.1007/978-3-030-58589-1_19#main-content)|2020|ECCV|RGB&Noise|Y|N|[github](https://github.com/ZhiHanZ/IRIS0-SPAN/tree/d8e4241f151ef2f40eacbb970fe5e3f531c6a4b4)|

## Year 2017-2020
| Title | Release year | Venue | Modality | Pixel-level | Image-level | Code | 
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Generate, Segment, and Refine: Towards Generic Manipulation Segmentation](https://ojs.aaai.org/index.php/AAAI/article/view/7007)|2020|AAAI|RGB|Y|N|[github](https://github.com/pengzhou1108/GSRNet)|
|[Constrained R-CNN: A general image manipulation detection model](https://ieeexplore.ieee.org/abstract/document/9102825)|2020|ICME|Noise|Y|N|[github](https://github.com/HuizhouLi/Constrained-R-CNN)|
|[Hybrid lstm and encoder???decoder architecture for detection of image forgeries](https://ieeexplore.ieee.org/abstract/document/8626149)|2019|T-IP|RGB|Y|N|[github](https://github.com/jawadbappy/forgery_localization_HLED)|
|[Adversarial Learning for Constrained Image Splicing Detection and Localization Based on Atrous Convolution](https://ieeexplore.ieee.org/abstract/document/8658131)|2019|T-IFS|RGB|Y|N|[github](https://github.com/yaqiliu-cs/CISDL-DMAC)|
|[Forensic Similarity for Digital Images](https://ieeexplore.ieee.org/abstract/document/8744262)|2019|T-IFS|RGB|Y|N|[github](https://github.com/nilsonsales/forensic-similarity-for-digital-images)|
|[Noiseprint: A CNN-Based Camera Model Fingerprint](https://ieeexplore.ieee.org/abstract/document/8713484)|2019|T-IFS|RGB&Noise|Y|N|[github](https://grip-unina.github.io/noiseprint/)|
|[Mantra-net: Manipulation tracing network for detection and localization of image forgeries with anomalous features](https://openaccess.thecvf.com/content_CVPR_2019/html/Wu_ManTra-Net_Manipulation_Tracing_Network_for_Detection_and_Localization_of_Image_CVPR_2019_paper.html)|2019|CVPR|RGB&Frequency|Y|N|[github](https://github.com/ISICV/ManTraNet)|
|[Localization of Deep Inpainting Using High-Pass Fully Convolutional Network](https://openaccess.thecvf.com/content_ICCV_2019/html/Li_Localization_of_Deep_Inpainting_Using_High-Pass_Fully_Convolutional_Network_ICCV_2019_paper.html)|2019|ICCV|High Frequency|Y|N|[github](https://github.com/lihaod/Deep_inpainting_localization)|
|[Learning rich features for image manipulation detection](https://openaccess.thecvf.com/content_cvpr_2018/html/Zhou_Learning_Rich_Features_CVPR_2018_paper.html)|2018|CVPR|RGB&Noise|Y|N|[github](https://github.com/minyoungg/selfconsistency)|
|[Fighting Fake News: Image Splice Detection via Learned Self-Consistency](https://openaccess.thecvf.com/content_ECCV_2018/html/Jacob_Huh_Fighting_Fake_News_ECCV_2018_paper.html)|2018|ECCV|RGB|Y|N|[github](https://github.com/LarryJiang134/Image_manipulation_detection)|
|[Image splicing localization using a multi-task fully convolutional network (MFCN)](https://www.sciencedirect.com/science/article/pii/S1047320318300178)|2017|VCIR|RGB|Y|N|-|
