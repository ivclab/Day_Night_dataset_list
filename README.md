# Day Night dataset list
Collecting a list of dataset which includes day and night images and segmentation or detection annotations.

### [v] 1. Mapillary Vistas Dataset (ICCV2017)
[[WebPage]](https://www.mapillary.com/dataset/vistas?pKey=rwbBtYKofke2NeLIvj8j-A&lat=20&lng=0&z=1.5) [[Paper]](https://research.mapillary.com/img/publications/ICCV17a.pdf) [[Evaluation Script]](https://github.com/mapillary/mapillary_vistas)

Street image with semantic segmentation annotation.  
Includes day and night images but does not contain corresponding labels.

### [v] 2. KAIST Multispectral Pedestrian Dataset (CVPR2015)
[[WebPage]](https://sites.google.com/site/pedestrianbenchmark/home) [[Paper]](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Hwang_Multispectral_Pedestrian_Detection_2015_CVPR_paper.pdf)

Consists of 95k color-thermal pairs (640x480, 20Hz) taken from a vehicle with bounding boxes annotation.   
Includes day and night labels.

### [v] 3. SYNTHIA (CVPR2016)
[[WebPage]](http://synthia-dataset.net/) [[Paper]](http://refbase.cvc.uab.es/files/RSM2016.pdf) 

Photo-realistic frames rendered from a virtual city and comes with precise pixel-level semantic annotations.  
Includes day and night labels.

<br>

# Reference dataset
Dataset that only has day or night images.

### 1. Cityscapes Dataset (CVPR2016)
[[WebPage]](https://www.cityscapes-dataset.com/dataset-overview/) [[Paper]](https://www.cityscapes-dataset.com/wordpress/wp-content/papercite-data/pdf/cordts2016cityscapes.pdf) [[Evaluation Scrpt]](https://github.com/mcordts/cityscapesScripts)

Street image with semantic segmentation annotation.  
Daytime images only. Often compare with SYNTHIA dataset.

### 2. Alderley Day/Night Dataset (ICRA2012)
[[WebPage]](https://wiki.qut.edu.au/pages/viewpage.action?pageId=181178395) [[Paper]](https://ieeexplore.ieee.org/abstract/document/6224623/)

 A vehicle dataset for vision-based place recognition with manually ground truthed frame correspondences.  
 No segmentation/detection label.
