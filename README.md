# BuildingFunctionMapping
Buildings, as fundamental man-made structures in urban environments, serve as crucial indicators for understanding various city function zones. In this study, we proposed a semi-supervised framework to identify every building's function in large-scale urban areas with multi-modality remote-sensing data. In detail, optical images, building height LiDAR, and nighttime-light data are collected to describe the morphological attributes of buildings. Then, the area of interest (AOI) and building masks from the volunteered geographic information (VGI) data are collected to form sparsely labeled samples.

This work is accepted by IGARSS 2024 (oral). See you in Athens!

Contact me at ashelee@whu.edu.cn
* [**Paper**](https://arxiv.org/abs/2405.05133](https://ieeexplore.ieee.org/document/10641437 )
* [**My homepage**](https://lizhuohong.github.io/lzh/)
  
Our previous works:

* [**Paraformer (L2HNet V2)**](https://arxiv.org/abs/2403.02746): accepted by **:rocket: CVPR 2024 (Highlight)**, the hybrid CNN-ViT framework for HR land-cover mapping using LR labels.[**Code**](https://github.com/LiZhuoHong/Paraformer/)
* [**SegLand**](https://arxiv.org/abs/2404.12721): accepted by **:rocket: CVPRW 2024 (Oral)** and won 1st place in OpenEarthMap Challenge, discovering novel classes in land-cover mapping.[**Code**](https://github.com/LiZhuoHong/SegLand)
* [**L2HNet V1**](https://www.sciencedirect.com/science/article/abs/pii/S0924271622002180): accepted by ISPRS P&RS in 2022, The low-to-high network for HR land-cover mapping using LR labels.
* [**SinoLC-1**](https://essd.copernicus.org/articles/15/4749/2023/): accepted by ESSD in 2023, the first 1-m resolution national-scale land-cover map of China.[**Data**](https://zenodo.org/record/7821068)

Data description
-------

### Multi-modality remote-sensing data:
* The **HR optical images** (1 m/pixel) are collected from the Google Earth imagery. The images contained three bands of red, green, and blue.

* The **building height LiDAR** (10 m/pixel) is from the Chinese building height estimate dataset (CNBH-10 m).

* The **nighttime-light data** (10 m/pixel) are from the SDGSAT-1, the world’s first scientific satellite for sustainable development goals. 

### Weak labels:

* **The AOI data** (vector) are collected from the OSM data. The AOI data contains over 100 building function types (e.g., cinema, hospital, department, and market).

* **The building masks** (vector) are from the building rooftop dataset containing 90 Chinese cities' building masks.

![image](https://github.com/LiZhuoHong/BuildingFunctionMapping/blob/main/Visual_result_v4.png)

Function type description
-------
The classification system includes seven typical building function types:
* Residential (labeled value: 1)
* Commercial (labeled value: 2)
* Public service (labeled value: 3)
* Public health (labeled value: 4)
* Sport and art (labeled value: 6)
* Industrial (labeled value: 7)
* Unlabled buildings (labeled value: 20)
 ![image](https://github.com/LiZhuoHong/BuildingMap/blob/main/Streetview_v4.png)

Data download
-------
* [The **HR optical images** (1 m/pixel)](https://drive.google.com/file/d/1JyL2DEpXwP8mZzaC4q21p4gxkO8Gc_TQ/view?usp=sharing)
* [The **building height LiDAR** (10 m/pixel)](https://drive.google.com/file/d/1FV6bDpsDrjr98XmJN4d55vTmq9DvQrb4/view?usp=sharing)
* [**nighttime-light data** (10 m/pixel)](https://drive.google.com/file/d/1YyuxeMweYXY0uI1e4gx-DFlvIOiuCl1J/view?usp=sharing)
* [**Weak label**](https://drive.google.com/file/d/1JFFOsvRyjeAvKbfbfFhR9UdBr-sExLPU/view?usp=sharing)

Citation
-------
   ```bash
@article{li2022breaking,
  title={Breaking the resolution barrier: A low-to-high network for large-scale high-resolution land-cover mapping using low-resolution labels},
  author={Li, Zhuohong and Zhang, Hongyan and Lu, Fangxiao and Xue, Ruoyao and Yang, Guangyi and Zhang, Liangpei},
  journal={ISPRS Journal of Photogrammetry and Remote Sensing},
  volume={192},
  pages={244--267},
  year={2022},
  publisher={Elsevier}
}
@article{li2024identifying,
  title={Identifying every building's function in large-scale urban areas with multi-modality remote-sensing data},
  author={Li, Zhuohong and He, Wei and Li, Jiepan and Zhang, Hongyan},
  journal={arXiv preprint arXiv:2405.05133},
  year={2024}
}
