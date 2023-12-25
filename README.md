# DL-based-spectral-super-resolution

# Single Spectral Image Super-Resolution Datasets

| Dataset | Description | Download Link |
|------------|------------|----------|
| CAVE   | Collected using VariSpec Liquid Crystal Tunable Filter and CCD camera (Apogee Alta U260). Comprises 32 spectral images of everyday objects (e.g., statues, food) captured at 10nm wavelength intervals in the range of 400-700nm, with a resolution of 512×512×31. | [Link](http://www.cs.columbia.edu/CAVE/databases/multispectral) |
| Harvard    | Captured using the Nuance FX spectral camera with tunable filters, containing 50 real-world indoor and outdoor images with 31 channels spaced 10nm apart in the range of 420-720nm. Spatial resolution is 1392×1040. | [Link](http://vision.seas.harvard.edu/hyperspec/explore.html) |
| ICVL    | Captured using the Specim PS Kappa DX4 spectral camera, including scenes from 203 urban (residential/commercial), suburban, rural, indoor, and plant environments. Original images have 519 channels in the range of 400-1000nm and spatial resolution of 1392×1300. Commonly used data consists of 31 channels spaced approximately 10nm apart from 400-700nm. | [Link](https://icvl.cs.bgu.ac.il/hyperspectral/) |
| NUS    | Captured using the Specim PFD-CL-65-V10E spectral camera, comprising 64 scenes. Original images cover the range of 400-1000nm, while commonly used data includes 31 channels in the range of 400-700nm. | [Link](http://www.comp.nus.edu.sg/~whitebal/spectral_reconstruction/index.html) |
| Botswana    | Captured by the Hyperion sensor on the Earth Observing-1 (EO-1) satellite, with 242 spectral channels covering the range of 400-2500nm at a spectral resolution of 10nm. Spatial dimensions are 1496×256. | [Link](https://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes) |
| Chikusei    | Captured by the Headwall Hyperspec-VNIR-C imaging sensor in agricultural and urban areas in Chikusei, Japan. Comprises 128 spectral bands in the range of 363-1018nm. Spatial dimensions are 2517×2335 pixels, with a geometric resolution of 2.5×2.5m2 per pixel. | [Link](http://naotoyokoya.com/Download.html) |
| Pavia University    | Captured above the University of Pavia, Italy, with the ROSIS airborne sensor in 2003, including 610×340 pixels and 115 spectral channels. | [Link](https://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes) |
| Pavia Center    | Description | [Link](https://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes) |
| Urban    | Description | [Link](https://rslab.ut.ac.ir/data) |
| Washington DC    | Description | [Link](https://engineering.purdue.edu/~biehl/MultiSpec/hyperspectral.html) |
| Indians Pines    | Description | [Link](https://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes) |
| Foster    | Description | [Link](https://personalpages.manchester.ac.uk/staff/d.h.foster/Local/_Illumination/_HSIs/Local/_Illumination/_HSIs/_2015.html) |
| Hoston    | Description | [Link](http://dase.grss-ieee.org/) |
| UCMERCED    | Description | [Link](http://vision.ucmerced.edu/datasets) |

# Fusion-based Spectral Image Super-Resolution Datasets

| Dataset | Description | Download Link |
|------------|------------|----------|
| QuickBird    | Captured by the QuickBird satellite, includes low-resolution multispectral images and panchromatic images. Spatial resolutions for low-resolution multispectral and panchromatic images are 2.44m and 0.61m, respectively. The multispectral image has four channels: R, G, B, NIR. | [Link](https://www.satimagingcorp.com/satellite-sensors/quickbird/) |
| HypSen   | Comprises 30m resolution hyperspectral images captured by the Hyperion sensor on the Earth Observing-1 satellite and 10m resolution multispectral images captured by the Sentinel-2A satellite. After noise and water absorption band removal, the low-resolution hyperspectral image has 84 spectral channels, while the high-resolution multispectral image contains 13 spectral channels. | [Link](https://example.com/dataset2) |
| AVIRIS Cuprite    | Collected by NASA's Airborne Visible/Infrared Imaging Spectrometer (AVIRIS) over the Cuprite mining district in Nevada, includes four images with dimensions 512×512×224 and a spectral range from 370nm to 2500nm. | [Link](https://example.com/dataset3) |



# Method list and code link

| Method                   | Scene | Base Framework | Supervision Paradigm | Publication Venue | Code Link |
|--------------------------|-------|-----------------|-----------------------|----------------------|-----------------------|
| 3D-FCNN (Mei et al., 2017) | SpaSR | CNN | Supervised | RS |  |
| SDCNN (Li et al., 2017) | SpaSR | CNN | Supervised | NC |  |
| 1D2DCNN (Li et al., 2019) | SpaSR | CNN | Supervised | RS |  |
| IDN (Hu et al., 2019) | SpaSR | CNN | Supervised | RS |  |
| MW-3D-CNN (Yang et al., 2019) | SpaSR | CNN | Supervised | RS |  |
| DFMF (Xie et al., 2019) | SpaSR | CNN | Supervised | TGRS |  |
| RIFN (Hu et al., 2020) | SpaSR | CNN | Supervised | TGRS |  |
| 3DASRGAN (Dou et al., 2020) | SpaSR | GAN | Supervised | RS |  |
| MCNet (Li et al., 2020c) | SpaSR | CNN | Supervised | RS | [Link](https://github.com/qianngli/MCNet) |
| SSPSR (Jiang et al., 2020) | SpaSR | CNN | Supervised | TGRS | [Link](https://github.com/junjun-jiang/SSPSR) |
| SFCSR (Wang et al., 2020a) | SpaSR | CNN | Supervised | TIE | [Link](https://github.com/qianngli/SFCSR) |
| UCNN (Lu et al., 2021) | SpaSR | CNN | Supervised | RS |  |
| MMCA (Magid et al., 2021) | SpaSR | CNN | Supervised | ICCV |  |
| SGARDN (Liu et al., 2021) | SpaSR | CNN | Supervised | TGRS |  |
| Bi3DQRNN (Fu et al., 2021) | SpaSR | CNN | Supervised | JSTARS | [Link](https://github.com/zhiyuan0112/Bi-3DQRNN) |
| INR (Zhang et al., 2022a) | SpaSR | CNN | Supervised | TGRS |  |
| RFSR (Wang et al., 2022) | SpaSR | CNN | Supervised | TGRS |  |
| DualSR (Li et al., 2022c) | SpaSR | CNN | Supervised | TIP | [Link](https://github.com/qianngli/DualSR) |
| SRAGAN (Li et al., 2021b) | SpaSR | GAN | Supervised | TGRS |  |
| LE-GAN (Shi et al., 2022) | SpaSR | CNN | Supervised | TGRS |  |
| DSSTSR (Long et al., 2023) | SpaSR | Transformer | Supervised | TGRS |  |
| HSCNN (Xiong et al., 2017) | SpeSR | CNN | Supervised | ICCVW |  |
| GANSSR (Lore et al., 2019) | SpeSR | GAN | Supervised | CVPRW |  |
| AWAN (Li et al., 2020a) | SpeSR | CNN | Supervised | CVPRW | [Link](https://github.com/Deep-imagelab/AWAN) |
| PDFN (Zhang et al., 2020a) | SpeSR | CNN | Supervised | AAAI |  |
| SSRAN (Zheng et al., 2021c) | SpeSR | CNN | Supervised | TGRS |  |
| DAGDN (Zhu et al., 2021a) | SpeSR | DUN | Supervised | TCI | [Link](https://github.com/zbzhzhy/GD-Net) |
| SEN (Zhu et al., 2021b) | SpeSR | CNN | Unsupervised | ICCV | [Link](https://github.com/zbzhzhy/Unsupervised-Spectral-Reconstruction) |
| HSACS (Li et al., 2021a) | SpeSR | CNN | Supervised | TNNLS |  |
| SSRN-IPH (Hang et al., 2021) | SpeSR | CNN | Supervised | TIP |  |
| SSN (Fu et al., 2022) | SpeSR | CNN | Supervised | TPAMI |  |
| DRCRNet (Li et al., 2022a) | SpeSR | CNN | Supervised | CVPRW | [Link](https://github.com/jojolee6513/DRCR-net) |
| PoNet (He et al., 2022) | SpeSR | DUN | Supervised | IF |  |
| MST++ (Cai et al., 2022) | SpeSR | Transformer | Supervised | CVPRW | [Link](https://github.com/caiyuanhao1998/MST-plus-plus) |
| MFormer (Li et al., 2023b) | SpeSR | Transformer | Unsupervised | TGRS |  |
| HPRN (Wu et al., 2023) | SpeSR | CNN | Supervised | TNNLS | [Link](https://github.com/deep-imagelab/hprn) |
| CTJN (Du et al., 2023) | SpeSR | CNN&Transformer | Supervised | TGRS |  |
| SSFAN (Liu et al., 2023) | SpeSR | GAN | Supervised | JSTARS |  |
| SSJSR (Mei et al., 2020) | SSSR | CNN | Supervised | TGRS |  |
| US3RN (Ma et al., 2021) | SSSR | DUN | Supervised | TIP | [Link](https://github.com/junjun-jiang/US3RN) |
| SSFIN (Ma et al., 2022) | SSSR | CNN | Supervised | TCI | [Link](https://github.com/junjun-jiang/SSFIN) |
| PNN (Masi et al., 2016) | PS | CNN | Supervised | RS |  |
| PanNet (Yang et al., 2017) | PS | CNN | Supervised | ICCV |  |
| MSDCNN (Yuan et al., 2018) | PS | CNN | Supervised | TGRS |  |
| PanGAN (Ma et al., 2020) | PS | GAN | Unsupervised | IF | [Link](https://github.com/jiayi-ma/PanGAN) |
| SSConv (Wang et al., 2021) | PS | CNN | Supervised | ACM MM | [Link](https://github.com/liangjiandeng/MUCNN) |
| GPPNN (Xu et al., 2021) | PS | DUN | Supervised | CVPR | [Link](https://github.com/xsxjtu/GPPNN) |
| HyperKite (Bandara et al., 2021) | PS | CNN | Supervised | TGRS | [Link](https://github.com/wgcban/DIP-HyperKite.git) |
| PanCSC-Net (Cao et al., 2021) | PS | DUN | Supervised | TGRS |  |
| HyperTransformer (Bandara et al., 2022) | PS | Transformer | Supervised | CVPR | [Link](https://github.com/wgcban/HyperTransformer) |
| Proximal PanNet (Cao et al., 2022) | PS | DUN | Supervised | AAAI |  |
| panformer (Zhou et al., 2022a) | PS | Transformer | Supervised | AAAI | [Link](https://github.com/manman1995/pansharpening) |
| DIIB (Gao et al., 2022) | PS | CNN | Unsupervised | CVPRW |  |
| MDCUN (Yang et al., 2022) | PS | DUN | Supervised | CVPR | [Link](https://github.com/yggame/mdcun) |
| MutInf (Zhou et al., 2022b) | PS | CNN | Supervised | CVPR | [Link](https://github.com/manman1995/pansharpening) |
| LHFnet (Zhou et al., 2022c) | PS | CNN | Supervised | ACM MM | [Link](https://github.com/manman1995/pansharpening) |
| DR-NET (Xu et al., 2022) | PS | Transformer | Supervised | TGRS |  |
| PanViT (Meng et al., 2022) | PS | Transformer | Supervised | TGRS |  |
| SFINet (Zhou et al., 2022d) | PS | CNN | Supervised | ECCV | [Link](https://github.com/manman1995/pansharpening) |
| UPanGAN (Xu et al., 2023) | PS | GAN | Unsupervised | IF |  |
| iGDANet (Qu et al., 2023) | PS | DUN | Unsupervised | TCYB |  |
| uSDN (Qu et al., 2018) | MHF | CNN | Unsupervised | CVPR | [Link](https://github.com/aicip/usdn) |
| DBIN (Wang et al., 2019) | MHF | CNN | Supervised | ICCV |  |
| HSRG (Fu et al., 2019) | MHF | CNN | Unsupervised | CVPR |  |
| CUCaNet (Yao et al., 2020) | MHF | CNN | Unsupervised | ECCV | [Link](https://github.com/danfenghong/ECCV2020_CUCaNet) |
| FusionNet (Wang et al., 2020b) | MHF | CNN | Unsupervised | TIP |  |
| UAL (Zhang et al., 2020b) | MHF | CNN | Unsupervised | CVPR | [Link](https://github.com/JiangtaoNie/UAL) |
| DBSR (Zhang et al., 2020c) | MHF | CNN | Unsupervised | TNNLS |  |
| u2-MDN (Qu et al., 2021) | MHF | CNN | Unsupervised | TGRS | [Link](https://github.com/aicip/u2MDN) |
| PZRes-Net (Zhu et al., 2020) | MHF | CNN | Supervised | TIP | [Link](https://github.com/ZHU-Zhiyu/PZRes-Net) |
| MHF-Net (Xie et al., 2020) | MHF | DUN | Supervised | TPAMI | [Link](https://github.com/XieQi2015/MHF-net/tree/master) |
| HyCoNet (Zheng et al., 20201b) | MHF | CNN | Unsupervised | TGRS | [Link](https://github.com/saber-zero/hyperfusion) |
| NonRegSRNet (Zheng et al., 2021c) | MHF | CNN | Unsupervised | TGRS | [Link](https://github.com/saber-zero/NonRegSRNet) |
| MoG-DCN (Dong et al., 2021) | MHF | DUN | Supervised | TIP | [Link](https://see.xidian.edu.cn/faculty/wsdong/Projects/MoG-DCN.htm) |
| DEIL (Fu et al., 2022b) | MHF | CNN | Unsupervised | TPAMI |  |
| S2DMDN (Dong et al., 2022a) | MHF | DUN | Supervised | TGRS |  |
| UDALN (Li et al., 2022b) | MHF | CNN | Unsupervised | GRSL | [Link](https://github.com/JiaxinLiCAS/UDALN_GRS) |
| Fusformer (Hu et al., 2022a) | MHF | Transformer | Supervised | TGRS | [Link](https://github.com/J-FHu/Fusformer) |
| GuidedNet (Ran et al., 2023) | MHF | CNN | Supervised | TCYB | [Link](https://github.com/Evangelion09/GuidedNet) |
| PSRT (Deng et al., 2023) | MHF | Transformer | Supervised | TGRS | [Link](https://github.com/Deng-shangqi/PSRT) |
| DPLN (Zhang et al., 2023) | MHF | CNN | Unsupervised | CAAI TRIT |   |
| BUSIFusion (Dong et al., 2023) | MHF | DUN  | Unsupervised | TCI |  |

## How to Use

Provide additional information and instructions on how to download and use the dataset here.
