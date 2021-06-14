# OpenGF: An Ultra-Large-Scale Ground Filtering Dataset Built Upon Open ALS Point Clouds Around the World

![Image](Imgs/figexample.png)

[**[Paper]**](https://arxiv.org/abs/2101.09641) [**[Project page]**](https://uwaterloo.ca/mobile-sensing/) [**[Download]**](#download) <br />

OpenGF is an Ultra-Large-Scale Ground Filtering dataset covering over 47 km<sup>2</sup> built upon open ALS point clouds of 4 different countries around the world. It not only includes more than half a billion finely labeled ground and non-ground points, but also contains 9 different terrain scenes. <br />

Details on the dataset can be found at [CVPRW2021](https://arxiv.org/abs/2101.09641). <br />

If you have questions, or any suggestions to help us improve the dataset, please contact [Nannan Qin](mailto:n7qin@uwaterloo.ca).

## <a name="download"></a> Download

Dataset can be downloaded at [GoogleDrive](https://drive.google.com/file/d/1AFPTzUMyNSTMg_NHF5ilJuG6zLT_UA9T/view?usp=sharing) or [百度网盘](https://pan.baidu.com/s/140_-W3pe1IuToVfCN3qndQ)(提取码：ybw4). Check [Changelog](#changelog) for changes. <br />

OpenGF contains information licensed under the Open Government Licence – Ontario, the CC BY 4.0 & the CC BY-SA 4.0 Licence. Part of this work is based on [data, processing] services provided by the OpenTopography Facility with support from the National Science Foundation under NSF Award Numbers 1948997, 1948994 & 1948857.

## <a name="tip"></a> Data preparation tip
At present, the point clouds are stored in las files to reduce the storage space as much as possible. If you are not familiar with las format, it is recommended to use professional tools (such as 'CloudCompare') to convert Laz files to common files (such as 'ply') before subsequent processing.


## Citation

If it is helpful for your work, please consider citing our paper:

    @article{qin2021opengf,
        title = {OpenGF: An Ultra-Large-Scale Ground Filtering Dataset Built Upon Open ALS Point Clouds Around the World},
        author = {Qin, Nannan and Tan, Weikai and Ma, Lingfei and Zhang, Dedong and Li, Jonathan},
        booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops},
        year = {2021}
    }

## <a name="changelog"></a> Changelog 
* 11/04/2021: The dataset is available for download!
* 08/04/2021: The OpenGF has been accepted by CVPRW 2021!

## Related projects
1. [3D-Terrain-Recognition: Deep fusion of multi-view and multimodal representation of ALS point cloud for 3D terrain scene recognition](https://github.com/Nathan-UW/3D-Terrain-Recognition) ![GitHub stars](https://img.shields.io/github/stars/Nathan-UW/3D-Terrain-Recognition.svg?style=flat&label=Star)
2. [VPNet-CRF: Semantic Labeling of ALS Point Cloud via Learning Voxel and Pixel Representations](https://github.com/Nathan-UW/VPNet) ![GitHub stars](https://img.shields.io/github/stars/Nathan-UW/VPNet.svg?style=flat&label=Star)
4. [Toronto-3D: A Large-scale Mobile LiDAR Dataset for Semantic Segmentation of Urban Roadways](https://github.com/WeikaiTan/Toronto-3D) ![Github](https://img.shields.io/github/stars/WeikaiTan/Toronto-3D.svg?style=flat&label=Star)

