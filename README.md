# Awesome_dualpixel_camera
List of awesome papers on dualpixel camera system, including lenses, dualpixel sensors, and post-processing

<!--A curated list of resources for Image and Video Deblurring-->
<!-- PROJECT LOGO -->
<p align="center">
  <h3 align="center">Dual Pixel Camera</h3>
</p>

## Attention
Cloned from [Dual Pixel](https://github.com/tkuri/Awesome-DualPixel/blob/main/README.md), update in future.

## Table of contents
- [Lens](#lens)
- [DualPixel](#dualpixel)
- [Dateset](#dataset)

## Lens
|Year|Pub|Paper|App|Repo|
|:---:|:---:|:---:|:---:|:---:|
|2019|OE|[Extrapolating from lens design databases using deep learning](https://pubmed.ncbi.nlm.nih.gov/31684583/)|Lens||
|2021|OE|[Deep learning-enabled framework for automatic lens design starting point generation](https://www.semanticscholar.org/paper/Deep-learning-enabled-framework-for-automatic-lens-C%C3%B4t%C3%A9-Lalonde/528e38584706d41bfcd8962fa0bf9eb2f37cf545)|Lens||
|2022|OE|[Inferring the solution space of microscope objective lenses using deep learning](https://opg.optica.org/viewmedia.cfm?uri=oe-30-5-6531&seq=0)|Lens||
|2022|NC|[Curriculum Learning for ab initio Deep Learned Refractive Optics (DeepLens)](https://www.nature.com/articles/s41467-024-50835-7)|Lens|[Code](https://github.com/singer-yang/AutoLens)|
|2023|CVPR|[The differentiable lens: Compound lens search over glass surfaces and materials for object detection](https://arxiv.org/pdf/2212.04441v2)|Lens||
|2023|ICCP & TPAMI|[Aberration-Aware Depth-from-Focus](https://singer-yang.github.io/papers/AberAwareDfF.pdf)|Lens|[Code](https://github.com/singer-yang/Aberration-Aware-Depth-from-Focus)|
|2024|Arxiv|[Image Quality Is Not All You Want: Task-Driven Lens Design for Image Classification](https://singer-yang.github.io/papers/TaskLens.pdf)|Lens||
|2024|Arxiv|[End-to-End Hybrid Refractive-Diffractive Lens Design with Differentiable Ray-Wave Model](https://arxiv.org/abs/2406.00834)|Diffractive Lens||

## Dual Pixel
|Year|Pub|Paper|App|Repo|
|:---:|:---:|:---:|:---:|:---:|
|2016|ITE Transactions on Media Technology and Applications|[A Low Noise and High Sensitivity Image Sensor with Imaging and Phase-Difference Detection AF in All Pixels](https://www.jstage.jst.go.jp/article/mta/4/2/4_123/_article)|Sensor||
|2018|SIGGRAPH|[Synthetic Depth-of-Field with a Single-Camera Mobile Phone](https://arxiv.org/abs/1806.04171)|Depth / Segmenation / Synthetic DoF||
|2019|CVPR|[Reflection Removal Using a Dual-Pixel Sensor](https://abhijithpunnappurath.github.io/dprr.html)|Reflection Removal|[Code](https://github.com/abhijithpunnappurath/dprr)|
|2019|ICCV|[Learning Single Camera Depth Estimation using Dual-Pixels](https://arxiv.org/abs/1904.05822)|Depth|[Code & Dataset](https://github.com/google-research/google-research/tree/master/dual_pixels)|
|2020|ICCP|[Modeling Defocus-Disparity in Dual-Pixel Sensors](https://abhijithpunnappurath.github.io/ICCP2020.pdf)|Depth|[Code & Dataset](https://github.com/abhijithpunnappurath/dual-pixel-defocus-disparity)|
|2020|CVPR|[Learning to Autofocus](https://learntoautofocus-google.github.io/)|Autofocus|[Dataset](https://learntoautofocus-google.github.io/)|
|2020|ECCV|[Du2Net: Learning Depth Estimation from Dual-Cameras and Dual-Pixels](https://augmentedperception.github.io/du2net/)|Disparity (w/Stereo)||
|2020|ECCV|[Defocus Deblurring Using Dual-Pixel Data](https://www.eecs.yorku.ca/~abuolaim/eccv_2020_dp_defocus_deblurring/)|Deblur|[Code & Dataset](https://github.com/Abdullah-Abuolaim/defocus-deblurring-dual-pixel)|
|2021|CVPR|[Dual Pixel Exploration: Simultaneous Depth Estimation and Image Restoration](https://openaccess.thecvf.com/content/CVPR2021/html/Pan_Dual_Pixel_Exploration_Simultaneous_Depth_Estimation_and_Image_Restoration_CVPR_2021_paper.html)|Depth / Deblur|[Code & Dataset](https://github.com/panpanfei/Dual-Pixel-Exploration-Simultaneous-Depth-Estimation-and-Image-Restoration)|
|2021|CVPRW|[NTIRE 2021 Challenge for Defocus Deblurring Using Dual-pixel Images: Methods and Results](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/html/Abuolaim_NTIRE_2021_Challenge_for_Defocus_Deblurring_Using_Dual-Pixel_Images_Methods_CVPRW_2021_paper.html)|Deblur||
|2021|CVPRW|[ATTSF Attention! Stay Focus!](https://arxiv.org/abs/2104.07925)|Deblur|[Code](https://github.com/tuvovan/ATTSF)|
|2021|ICCV|[Defocus Map Estimation and Deblurring From a Single Dual-Pixel Image](https://openaccess.thecvf.com/content/ICCV2021/html/Xin_Defocus_Map_Estimation_and_Deblurring_From_a_Single_Dual-Pixel_Image_ICCV_2021_paper.html)|Deblur /  Defocus Map|[Code & Dataset](https://github.com/cmu-ci-lab/dual_pixel_defocus_estimation_deblurring)|
|2021|ICCV|[Learning to Reduce Defocus Blur by Realistically Modeling Dual-Pixel Data](https://openaccess.thecvf.com/content/ICCV2021/html/Abuolaim_Learning_To_Reduce_Defocus_Blur_by_Realistically_Modeling_Dual-Pixel_Data_ICCV_2021_paper.html)|Deblur|[Code & Dataset](https://github.com/Abdullah-Abuolaim/recurrent-defocus-deblurring-synth-dual-pixel)|
|2021|IEEE|[World Largest Mobile Image Sensor with All Directional Phase Detection Auto Focus Function](https://ieeexplore.ieee.org/document/9567122)|Depth||
|2021|ICTC|[Disparity probability volume guided defocus deblurring using dual pixel data](https://ieeexplore.ieee.org/document/9621024)|Deblur||
|2021|Journal of Electronic Imaging|[Defocus deblurring: a designed deep model based on CNN](https://www.spiedigitallibrary.org/journals/journal-of-electronic-imaging/volume-30/issue-6/063013/Defocus-deblurring-a-designed-deep-model-based-on-CNN/10.1117/1.JEI.30.6.063013.short?SSO=1)|Deblur||
|2021|IEEE|[All-Directional Dual Pixel Auto Focus Technology in CMOS Image Sensors](https://ieeexplore.ieee.org/document/9492472)|Circuits||
|2022|WACV|[Improving Single-Image Defocus Deblurring: How Dual-Pixel Images Help Through Multi-Task Learning](https://arxiv.org/abs/2108.05251)|Deblur|[Code & Dataset](https://github.com/Abdullah-Abuolaim/multi-task-defocus-deblurring-dual-pixel-nimat)|
|2022|ISSCC|[A 1/1.57-inch 50Mpixel CMOS Image Sensor With 1.0μm All-Directional Dual Pixel by 0.5μm-Pitch Full-Depth Deep-Trench Isolation Technology](https://ieeexplore.ieee.org/document/9731567)|Circuits||
|2022|ECCV|[Facial Depth and Normal Estimation using Single Dual-Pixel Camera](https://arxiv.org/abs/2111.12928)|Depth / Surface Normal / Anti-spoofing / Relighting|[Code & Dataset](https://github.com/MinJunKang/DualPixelFace)|
|2022|ARXIV|[Learning Dual-Pixel Alignment for Defocus Deblurring](https://arxiv.org/abs/2204.12105v1)|Deblur||
|2022|Journal of Image and Graphing|[全像素双核成像技术及应用研究综述](http://www.cjig.cn/jig/ch/reader/view_abstract.aspx?file_no=20221201)|Summarize||
|2022|ARXIV|[Dual-Pixel Raindrop Removal](https://arxiv.org/pdf/2210.13321)|Raindrop|[code](http://www.ok.sc.e.titech.ac.jp/res/SIR/)|
|2023|ICCV|[Exploring Positional Characteristics of Dual-Pixel Data for Camera Autofocus](https://ieeexplore.ieee.org/document/10376947)|Autofocus||
|2023|CVPR|[K3DN: Disparity-Aware Kernel Estimation for Dual-Pixel Defocus Deblurring](https://openaccess.thecvf.com/content/CVPR2023/html/Yang_K3DN_Disparity-Aware_Kernel_Estimation_for_Dual-Pixel_Defocus_Deblurring_CVPR_2023_paper.html)|Deblur||
|2023|CVPR|[Spatio-Focal Bidirectional Disparity Estimation From a Dual-Pixel Image](https://openaccess.thecvf.com/content/CVPR2023/html/Kim_Spatio-Focal_Bidirectional_Disparity_Estimation_From_a_Dual-Pixel_Image_CVPR_2023_paper.html)|Depth / Disparity|[Code](https://github.com/KAIST-VCLAB/dual-pixel-disparity)|
|2023|ICCP|[Learning to Synthesize Photorealistic Dual-pixel Images from RGBD frames](https://ai.sony/publications/Learning-to-Synthesize-Photorealistic-Dual-pixel-Images-from-RGBD-frames/)|Simulator|[Code & Dataset](https://github.com/feiran-l/Neural-Dual-Pixel-Simulator)|
|2023|ICCV|[Exploring Positional Characteristics of Dual-Pixel Data for Camera Autofocus](https://openaccess.thecvf.com/content/ICCV2023/html/Choi_Exploring_Positional_Characteristics_of_Dual-Pixel_Data_for_Camera_Autofocus_ICCV_2023_paper.html)|Autofocus||
|2024|ACM Trans. Graph.|[Split-Aperture 2-in-1 Computational Cameras](https://dl.acm.org/doi/10.1145/3658225)|Depth /  HDR|[Code](https://github.com/princeton-computational-imaging/2in1_camera)|


## Dataset
|Year|Pub|Paper|Detail|
|:---:|:---:|:---:|:---:|
|2019|ICCV|[Learning Single Camera Depth Estimation using Dual-Pixels](https://github.com/google-research/google-research/tree/master/dual_pixels)|Train:2506, Test:684, Res:1512x2016(DP), 16bit png, DP Raw / Depth|
|2020|ICCP|[Modeling Defocus-Disparity in Dual-Pixel Sensors](https://github.com/abhijithpunnappurath/dual-pixel-defocus-disparity)|Num:100, Res:5180x2940, RGB 8bit jpg / 16bit tif Depth, DP LR / Depth|
|2020|ECCV|[Defocus Deblurring Using Dual-Pixel Data](https://github.com/Abdullah-Abuolaim/defocus-deblurring-dual-pixel)|Num:500, Res:1680x1120, 16bit, Used for NTIRE 2021 Challenge (CVPRW)|
|2021|CVPR|[Dual Pixel Exploration: Simultaneous Depth Estimation and Image Restoration](https://github.com/panpanfei/Dual-Pixel-Exploration-Simultaneous-Depth-Estimation-and-Image-Restoration)|DP Simulator from [NYUD Dataset](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html)|
|2021|ICCV|[Learning to Reduce Defocus Blur by Realistically Modeling Dual-Pixel Data](https://github.com/Abdullah-Abuolaim/recurrent-defocus-deblurring-synth-dual-pixel)|DP Simulator form [SYNTHIA-SF dataset](https://synthia-dataset.net/downloads/)|
|2023|ICCP|[Learning to Synthesize Photorealistic Dual-pixel Images from RGBD frames](https://github.com/feiran-l/Neural-Dual-Pixel-Simulator)|Num:5130, Res:1680x1120, RGB(DP LRC) 8bit png / Depth 16bit png|