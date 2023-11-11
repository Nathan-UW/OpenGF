# OpenGF: An Ultra-Large-Scale Ground Filtering Dataset Built Upon Open ALS Point Clouds Around the World

![Image](Imgs/figexample.png)

[**[Paper]**](https://openaccess.thecvf.com/content/CVPR2021W/EarthVision/html/Qin_OpenGF_An_Ultra-Large-Scale_Ground_Filtering_Dataset_Built_Upon_Open_ALS_CVPRW_2021_paper.html) [**[Download]**](#download) [**[Results]**](#results) [**[Codes]**](#code)

OpenGF is an Ultra-Large-Scale Ground Filtering dataset covering over 47 km<sup>2</sup> built upon open ALS point clouds of 4 different countries around the world. It not only includes more than half a billion finely labeled ground and non-ground points, but also contains 9 different terrain scenes. <br />

Details on the dataset can be found at [CVPRW2021](https://openaccess.thecvf.com/content/CVPR2021W/EarthVision/html/Qin_OpenGF_An_Ultra-Large-Scale_Ground_Filtering_Dataset_Built_Upon_Open_ALS_CVPRW_2021_paper.html). <br />

If you have questions, or any suggestions to help us improve the dataset, please contact [Nannan Qin](mailto:nnqin@nuist.edu.cn).

## <a name="download"></a> Download

Dataset can be downloaded at [GoogleDrive](https://drive.google.com/drive/folders/1ud3fuiaNGHBiTVmIg36mrDarz-zzCzID?usp=sharing) or [百度网盘](https://pan.baidu.com/s/1WWDfyXoZWJP32nXfWDrvWQ)(提取码：rncj). Check [Changelog](#changelog) for changes. <br />

OpenGF contains information licensed under the Open Government Licence – Ontario, the CC BY 4.0 & the CC BY-SA 4.0 Licence. Part of this work is based on [data, processing] services provided by the OpenTopography Facility with support from the National Science Foundation under NSF Award Numbers 1948997, 1948994 & 1948857.

---
## <a name="results"></a> Ground filtering results 

More results to be added

*Default: point coordinates only*

Results on Test I
| Method          | OA(%)    | RMSE(m) | IoU<sub>1</sub>(%)   | IoU<sub>2</sub>(%)    | 
|------------------|--------|--------|--------|----------|
| [PTD]       |  94.82 | 0.37 | 91.10 |  89.00    |
| [PMF](https://pdal.io)       |  90.63 |  0.51 |  85.22 |  79.62   | 
| [MCC](http://sourceforge.net/projects/mccLiDAR/develop)      | 96.29 | 0.42 | 93.63 |  91.86   | 
| [CSF](https://www.cloudcompare.org)        | 93.07 | 0.95 |  88.17 |85.64   | 
| [PointNet++](https://github.com/intel-isl/Open3D-PointNet2-Semantic3D) |  97.58 |  0.25 | 95.75 | 94.68    | 
| [DGCNN](https://github.com/AnTao97/dgcnn.pytorch) |  96.34 |  0.41 | 93.78 | 91.81    | 
| [KPConv](https://github.com/HuguesTHOMAS/KPConv) | 97.79 |  0.20 | 96.10 |  95.17 | 
| [RandLA-Net](https://github.com/QingyongHu/RandLA-Net) |  96.29 | 0.29 | 93.74  |  91.65| 
| [SCF-Net](https://github.com/leofansq/SCF-Net) |  95.75 | 0.28 |  92.90 |  90.43| 



---
## <a name="code"></a> Codes for training your own data
* [RandLA-Net](https://github.com/WeikaiTan/RandLA-Net.git)

## <a name="tip"></a> Data preparation tip
At present, the point clouds are stored in laz files to reduce the storage space as much as possible. If you are not familiar with the laz format, it is recommended to use professional tools (such as 'CloudCompare') to convert laz files to other common files (such as 'ply') before subsequent processing.


## Citation

If it is helpful for your work, please consider citing our paper:

    @inproceedings{qin2021opengf,
        title={{OpenGF}: An ultra-large-scale ground filtering dataset built upon open {ALS} point clouds around the world},
        author={Qin, Nannan and Tan, Weikai and Ma, Lingfei and Zhang, Dedong and Li, Jonathan},
        booktitle={Proc. IEEE Conf. Comput. Vis. Pattern Recog. Workshops},
        pages={1082--1091},
        year={2021}
    }

    @article{qin2023deep,
        title={Deep learning for filtering the ground from {ALS} point clouds: A dataset, evaluations and issues},
        author={Qin, Nannan and Tan, Weikai and Ma, Lingfei and Zhang, Dedong and Guan, Haiyan and Li, Jonathan},
        journal={ISPRS J. Photogramm. Remote Sens.},
        volume={202},
        pages={246--261},
        year={2023}
    }    


## <a name="changelog"></a> Changelog
* [2023-11-11] A comprehensive survey based on this work has been accepted by JAG! 
* [2023-06-25] A journal extension of this work has been published in ISPRS P&RS! 
* [2023-02-07] Added code for RandLA-Net
* [2021-10-01] The HD Figure 5 in the paper(see Fig_5.docx) has been released to facilitate the visual comparison with new research results!
* [2021-04-11] The dataset is available for download!
* [2021-04-08] The OpenGF has been accepted by CVPRW 2021!

## Related projects
1. [3D-Terrain-Recognition: Deep fusion of multi-view and multimodal representation of ALS point cloud for 3D terrain scene recognition](https://github.com/Nathan-UW/3D-Terrain-Recognition) 
2. [VPNet-CRF: Semantic Labeling of ALS Point Cloud via Learning Voxel and Pixel Representations](https://github.com/Nathan-UW/VPNet)
3. [Towards-Intelligent-GF: A Comprehensive Survey](https://github.com/Nathan-UW/Towards-Intelligent-GF)
4. [Toronto-3D: A Large-scale Mobile LiDAR Dataset for Semantic Segmentation of Urban Roadways](https://github.com/WeikaiTan/Toronto-3D) ![Github](https://img.shields.io/github/stars/WeikaiTan/Toronto-3D.svg?style=flat&label=Star)

