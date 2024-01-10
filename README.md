# BuildingFunctionMapping
Buildings, as fundamental man-made structures in urban environments, serve as crucial indicators for understanding various city function zones. In this study, we proposed a semi-supervised framework to identify every building's function in large-scale urban areas with multi-modality remote-sensing data. In detail, optical images, building height LiDAR, and nighttime-light data are collected to describe the morphological attributes of buildings. Then, the area of interest (AOI) and building masks from the volunteered geographic information (VGI) data are collected to form sparsely labeled samples.

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
 ![image](https://github.com/LiZhuoHong/BuildingMap/blob/main/Visual_result_v4.png)

Data download
-------
* [The **HR optical images** (1 m/pixel)](https://drive.google.com/file/d/1JyL2DEpXwP8mZzaC4q21p4gxkO8Gc_TQ/view?usp=sharing)
* [The **building height LiDAR** (10 m/pixel)](https://drive.google.com/file/d/1FV6bDpsDrjr98XmJN4d55vTmq9DvQrb4/view?usp=sharing)
* [**nighttime-light data** (10 m/pixel)](https://drive.google.com/file/d/1YyuxeMweYXY0uI1e4gx-DFlvIOiuCl1J/view?usp=sharing)

