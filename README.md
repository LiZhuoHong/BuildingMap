# BuildingFunctionMapping
Buildings, as fundamental man-made structures in urban environments, serve as crucial indicators for understanding various city function zones. In this study, we proposed a semi-supervised framework to identify every building's function in large-scale urban areas with multi-modality remote-sensing data. In detail, optical images, building height LiDAR, and nighttime-light data are collected to describe the morphological attributes of buildings. Then, the area of interest (AOI) and building masks from the volunteered geographic information (VGI) data are collected to form sparsely labeled samples.

Data description
-------

###Multi-modality remote-sensing data:
* The HR optical images (1 m/pixel) are collected from the Google Earth imagery. The images contained three bands of red, green, and blue \cite{li2023sinolc}.

* The building height LiDAR (10 m/pixel) is from the Chinese building height estimate dataset (CNBH-10 m) \cite{wu2023first}.

* The nighttime-light data (10 m/pixel) are from the SDGSAT-1, the world’s first scientific satellite for sustainable development goals. \cite{guo2023sdgsat}.

###Weakly labels:

* The AOI data (vector) are collected from the OSM data. The AOI data contains more than 100 building function types (e.g., cinema, hospital, department, and market). \cite{li2023sinolc}.

* The building mask (vector) are from the building rooftop dataset containing 90 Chinese cities' building masks
