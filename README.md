# Awesome-Image-Forensics

# Contents
- [Databases](#databases)
- [Manipulation-Detection-And-Localization-Methods](#Manipulation-Detection-And-Localization-Methods)

# Databases
|  Name   | Release year | Venue | Download | #Pristine | #Manipulated | #Copy-move | #Splicing | #Inpainting  | 
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|[CASIAv2](https://ieeexplore.ieee.org/abstract/document/6625374)|2013|ChinaSIP|[github](https://github.com/namtpham/casia2groundtruth)|7491|5123|3295|1828|0|
|[COVER](https://ieeexplore.ieee.org/abstract/document/7532339)|2016|ICIP|[github](https://github.com/wenbihan/coverage)|100|100|100|0|0|
|[Columbia](https://ieeexplore.ieee.org/abstract/document/4036658)|2006|ICME|[link](https://www.ee.columbia.edu/ln/dvmm/downloads/authsplcuncmp/)|183|180|0|180|0|
|[NIST2016](https://www.nist.gov/system/files/documents/2017/09/07/nc2017evaluationplan_20170804.pdf)|2016|OpenMFC|[link](https://www.nist.gov/itl/iad/mig/nimble-challenge-2017-evaluation)|0|564|68|288|208|
|[CASIAv1](https://ieeexplore.ieee.org/document/6625374)|2013|ChinaSIP|[github](https://github.com/namtpham/casia1groundtruth)|800|920|459|461|0|
|[IMD2020](https://openaccess.thecvf.com/content_WACVW_2020/html/w4/Novozamsky_IMD2020_A_Large-Scale_Annotated_Dataset_Tailored_for_Detecting_Manipulated_Images_WACVW_2020_paper.html)|2020|WACVW|[link](http://staff.utia.cas.cz/novozada/db/)|404|2010|-|-|-|
|[DEFACTO](https://ieeexplore.ieee.org/abstract/document/8903181)|2019|EUSIPCO|[github](https://defactodataset.github.io/)|0|149k|19k|105k|25k|

# Manipulation-Detection-And-Localization-Methods
| Title | Release year | Venue | Modality | Pixel-level | Image-level | Code | 
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|[MVSS-Net: Multi-View Multi-Scale Supervised Networks for Image Manipulation Detection](https://ieeexplore.ieee.org/abstract/document/9789576)|2022|T-PAMI|RGB&Boundary&Noise|Y|Y|[github](https://github.com/dong03/MVSS-Net/tree/359ac66528d1231e542ac5b562303019e4d51832)|
|[Robust Image Forgery Detection Against Transmission Over Online Social Networks](https://ieeexplore.ieee.org/abstract/document/9686650)|2022|T-IFS|-|-|-|[github](https://github.com/HighwayWu/ImageForensicsOSN)|
|[PSCC-Net: Progressive Spatio-Channel Correlation Network for Image Manipulation Detection and Localization](https://ieeexplore.ieee.org/abstract/document/9819903)|2022|T-CSVT|RGB|Y|Y|[github](https://github.com/proteus1991/PSCC-Net)|
|[Objectformer for image manipulation detection and localization](https://openaccess.thecvf.com/content/CVPR2022/html/Wang_ObjectFormer_for_Image_Manipulation_Detection_and_Localization_CVPR_2022_paper.html)|2022|CVPR|RGB&Frequency|Y|Y|-|
|[Robust Image Forgery Detection Over Online Social Network Shared Images](https://openaccess.thecvf.com/content/CVPR2022/html/Wu_Robust_Image_Forgery_Detection_Over_Online_Social_Network_Shared_Images_CVPR_2022_paper.html)|2022|CVPR|-|-|-|[github](https://github.com/HighwayWu/ImageForensicsOSN)|
|[Image Manipulation Detection by Multi-View Multi-Scale Supervision](https://openaccess.thecvf.com/content/ICCV2021/html/Chen_Image_Manipulation_Detection_by_Multi-View_Multi-Scale_Supervision_ICCV_2021_paper.html)|2021|ICCV|Boundary&Noise|Y|Y|[github](https://github.com/dong03/MVSS-Net/tree/359ac66528d1231e542ac5b562303019e4d51832)|
|[SPAN: Spatial pyramid attention network for image manipulation localization](https://link.springer.com/chapter/10.1007/978-3-030-58589-1_19#main-content)|2020|ECCV|RGB&Noise|Y|-|[github](https://github.com/ZhiHanZ/IRIS0-SPAN/tree/d8e4241f151ef2f40eacbb970fe5e3f531c6a4b4)|
|[Generate, Segment, and Refine: Towards Generic Manipulation Segmentation](https://ojs.aaai.org/index.php/AAAI/article/view/7007)|2020|AAAI|RGB|Y|-|[github](https://github.com/pengzhou1108/GSRNet)|
|[Constrained R-CNN: A general image manipulation detection model](https://ieeexplore.ieee.org/abstract/document/9102825)|2020|ICME|-|-|-|-|
|[CAT-Net: Compression artifact tracing network for detection and localization of image splicing](https://openaccess.thecvf.com/content/WACV2021/html/Kwon_CAT-Net_Compression_Artifact_Tracing_Network_for_Detection_and_Localization_of_WACV_2021_paper.html)|2020|WACV|-|-|-|-|
|[Hybrid lstm and encoder–decoder architecture for detection of image forgeries](https://ieeexplore.ieee.org/abstract/document/8626149)|2019|T-IP|-|-|-|-|
|[Mantra-net: Manipulation tracing network for detection and localization of image forgeries with anomalous features](https://openaccess.thecvf.com/content_CVPR_2019/html/Wu_ManTra-Net_Manipulation_Tracing_Network_for_Detection_and_Localization_of_Image_CVPR_2019_paper.html)|2019|CVPR|-|-|-|-|
|[Localization of Deep Inpainting Using High-Pass Fully Convolutional Network](https://openaccess.thecvf.com/content_ICCV_2019/html/Li_Localization_of_Deep_Inpainting_Using_High-Pass_Fully_Convolutional_Network_ICCV_2019_paper.html)|2019|ICCV|-|-|-|-|
|[Learning rich features for image manipulation detection](https://openaccess.thecvf.com/content_cvpr_2018/html/Zhou_Learning_Rich_Features_CVPR_2018_paper.html)|2018|CVPR|-|-|-|-|
|[Image splicing localization using a multi-task fully convolutional network (MFCN)](https://www.sciencedirect.com/science/article/pii/S1047320318300178)|2017|VCIR|RGB|Y|-|-|
