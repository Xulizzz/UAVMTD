# UAVMTD
UAV Maize Tassels Detection dataset
## Introduction
Maize tassel is a key phenotypic trait in varieties selection, detasseling arrangement for seed maize fields, and its associated tasseling time is also a key growth stage in maize development. In order to propose a detecton method suitable for complex scenes and estimate tasseling time of different varieties, we created this dataset
that including different maize varieties, light conditions, tasseling stages.
## Highlights
* with 100 UAV images acquired during 2019, 2020 in Hebi, Henan Province, China and 42 UAV images acquired during 2021 in Tongliao,Inner Mongolia Autonomous Region, China.
* images were acquired using DJI ZENMUSE X4s and DJI ZENMUSE X5s cameras mounted on the DJI Inspire 2 drone at a flight altitude of 20m.
* There are 28182 manually labeled maize tassels with the corresponding bounding boxes, including 17254, 6514, 4414 samples in 2019,2020 and 2021 respectively.
* The dataset varied from planting management modes, varieties, planting density, and light conditions.  
![image](https://github.com/Xulizzz/UAVMTD/blob/main/samples%20under%20different%20conditions.png)
## Download
* [Download from Google drive]
* [Download from Baidu yun](https://pan.baidu.com/s/1MK6REJNplECYwaXwfKDC4g)(MTD1)
## Details of our Dataset
* The name of jpg and txt was composed of "field location", "flight altitude", "acquisition time" and "picture number".
* every jpg has a corresponding txt, which records location of bounding boxes with five columns. 
* The first column is the name of the object.
* The remaining four columns are the location information of bounding boxes with the format [x_min, y_min, x_max, y_max]. 
## Citation
If you use the dataset for your research, please do not forget to quote:
## Permission
This dataset is only for academic purposes. Contact XUli Zan (zanxuli@cau.edu.cn) or Zhe Liu (liuz@cau.edu.cn) for the commerial use.
