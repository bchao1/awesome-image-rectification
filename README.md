# Awesome Image Rectification 
A curated list of image rectification (distortion correction) and camera calibration papers.

## Table of Contents
- Deep Learning Based Methods
- Graphics Based Methods
- Datasets
- Related Papers

## Deep Learning Based
|Paper|Supervised|Link|Conference|Notes|
|---|---|---|---|---|
|Blind Geometric Distortion Correction on Images Through Deep Learning|Yes|[Link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Blind_Geometric_Distortion_Correction_on_Images_Through_Deep_Learning_CVPR_2019_paper.pdf)|CVPR '19|Parameterized distortions (barrel, pincushion, and etc)|
|ESIR: End-to-end Scene Text Recognition via Iterative Image Rectification||[Link](https://arxiv.org/pdf/1812.05824.pdf)|CVPR '19|Scene text distortion|
|Learning to Calibrate Straight Lines for Fisheye Image Rectification||[Link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Xue_Learning_to_Calibrate_Straight_Lines_for_Fisheye_Image_Rectification_CVPR_2019_paper.pdf)|CVPR '19|Fish eye distortion, straight line calibration|
|Symmetry-constrained Rectification Network for Scene Text Recognition||[Link](https://arxiv.org/pdf/1908.01957.pdf)|ICCV '19|Scene text distortion|
|DR-GAN: Automatic Radial Distortion Rectification Using Conditional GAN in Real-Time|Yes|[Link](https://ieeexplore.ieee.org/document/8636975)|IEEE Transactions on Circuits and Systems for Video Technology'19|Conditional GAN . Learn the mapping between distorted and clean images.No hand-crafted technique.|
|FishEyeRecNet: A Multi-Context Collaborative Deep Network for Fisheye Image Rectification|Yes|[Link](https://arxiv.org/pdf/1804.04784.pdf)|ECCV '18|Fish eye distortion, predicts camera model parameters|
|MORAN: A Multi-Object Rectified Attention Network for Scene Text Recognition||[Link](https://arxiv.org/pdf/1901.03003.pdf)||Scene text distortion|
|GridFace: Face Rectification via Learning Local Homography Transformations||[Link](https://arxiv.org/pdf/1808.06210.pdf)|ECCV '18|Face rectification|
|Fingerprint Distortion Rectification using Deep Convolutional Neural Networks||[Link](https://arxiv.org/pdf/1801.01198.pdf)|ICB '18|Fingerprint distortion|
|Deep View Morphing||[Link](https://arxiv.org/pdf/1703.02168.pdf)|CVPR '17|3D view morphing|
|Robust Scene Text Recognition with Automatic Rectification||[Link](https://arxiv.org/pdf/1603.03915.pdf)|CVPR '16|Scene text distortion|
|Radial Lens Distortion Correction Using Convolutional Neural Networks Trained with Synthesized Images|||ACCV '16|Radial lens distortion|

## Computer Graphics Based
|Paper|Link|Conference|Notes|
|---|---|---|---|
|Distortion-Free Wide-Angle Portraits on Camera Phones|[Link](http://people.csail.mit.edu/yichangshih/wide_angle_portrait/shih_sig19.pdf)|SIGGRAPH '19|Wide-angle camera, fish eye distortion|
|Restoration of Non-rigidly Distorted Underwater Images using a Combination of Compressive Sensing and Local Polynomial Image Representations|[Link](https://arxiv.org/pdf/1908.01940.pdf)|ICCV '19|Underwater image distortion|
|Rolling-Shutter-Aware Differential SfM and Image Rectification|[Link](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhuang_Rolling-Shutter-Aware_Differential_SfM_ICCV_2017_paper.pdf)|ICCV '17|Rolling shutter artifact correction|
|From Bows to Arrows: Rolling Shutter Rectification of Urban Scenes|[Link](http://openaccess.thecvf.com/content_cvpr_2016/papers/Rengarajan_From_Bows_to_CVPR_2016_paper.pdf)|CVPR '16|Rolling shutter artifact correction|
|Line-Based Multi-Label Energy Optimization for Fisheye Image Rectification and Calibration|[Link](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Zhang_Line-Based_Multi-Label_Energy_2015_CVPR_paper.pdf)|CVPR '15|Fish eye distortion|
|Lens Distortion Rectification using Triangulation based Interpolation|[Link](https://arxiv.org/pdf/1611.09559.pdf)|ISVC '15|Lens distortion|
|Radially-Distorted Conjugate Translations|[Link](https://arxiv.org/pdf/1711.11339.pdf)||Radial distortion|
|Pixel-variant Local Homography for Fisheye Stereo Rectification Minimizing Resampling Distortion|[Link](https://arxiv.org/pdf/1707.03775.pdf)||Radial Distortion|
|Rectification from Radially-Distorted Scales|[Link](https://arxiv.org/pdf/1807.06110.pdf)||Radial distortion|

## Datasets
|Paper|Paper Link|Dataset Link|Synthesized|Annotations|
|---|---|---|---|---|
|Parameterized Synthetic Image Data Set for Fisheye Lens|[Link](https://arxiv.org/pdf/1811.04627.pdf)|[Link]( http://www2.leuphana.de/misl/fisheye-data-set/)|Yes|
|Learning to Calibrate Straight Lines for Fisheye Image Rectification|[Link](https://arxiv.org/pdf/1904.09856.pdf)||No|Distortion parameters and distorted lines|

## Papers on Camera Calibration
|Paper|Link|Conference|
|---|---|---|
|Deep Single Image Camera Calibration with Radial Distortion|[Link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Lopez_Deep_Single_Image_Camera_Calibration_With_Radial_Distortion_CVPR_2019_paper.pdf)|CVPR '19|
|Parameter-free Lens Distortion Calibration of Central Cameras|[Link](http://openaccess.thecvf.com/content_ICCV_2017/papers/Bergamasco_Parameter-Free_Lens_Distortion_ICCV_2017_paper.pdf)|ICCV '17|
|Unsupervised Vanishing Point Detection and Camera Calibration from a Single Manhattan Image with Radial Distortion|[Link](http://openaccess.thecvf.com/content_cvpr_2017/papers/Antunes_Unsupervised_Vanishing_Point_CVPR_2017_paper.pdf)|CVPR '17|

## Contributing 
PR me related papers!