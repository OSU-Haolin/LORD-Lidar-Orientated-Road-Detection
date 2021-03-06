# Road Detection and Vehicle Control
#### Haolin ZHANG, Xiao LIU, Ruoyang FU, Simeng HUANG, Hongwei JIANG
#### Department of Electrical and Computer Engineering, The Ohio State University
##### Latest version:08/11/2020

#### 1. Environment and Dataset Setup

Please setup dataset according to the following folder structure:
```
RD
 |---- ptsemseg
 |---- outputs
 |---- configs
 |---- dataset
 |    |---- training
 |    |    |---- image_2
 |    |    |---- gt_image_2
 |    |    |---- velodyne
 |    |    |---- calib
 |    |    |---- image_2_proj
 |    |    |---- image_2_sn
 |    |    |---- image_2_ADT
 |    |---- testing
 |    |    |---- image_2
 |    |    |---- velodyne
 |    |    |---- calib
 |    |    |---- image_2_proj
 |    |    |---- image_2_sn
 |    |    |---- image_2_ADT
```
#### 2. Instruction
##### Evaluation
Open the `simpleExample_evalTrainResults.py`<br>
Revise the `line 29-30` to your own data path<br>
e.g <br>
    `datasetDir = '/home/RD/'`<br>
    `outputDir = '/home/RD/result'`<br>
According to the above example paths, your data should be put in following paths:<br>
Your ground truth images should be in `'/home/RD/training/gt_imge_2'`
Your ouput results should be in `'/home/RD/result/baseline_perspective_train'`<br>
Then run the `simpleExample_evalTrainResults.py` (in python 2.7) and the evaluation scores will be printed<br>


#### 3. Demo
Waiting for update...

#### 4. Update Log

##### 06/06/2020
* Revised evaluation tools (in `devkit_road` (from http://www.cvlibs.net/datasets/kitti/eval_road.php))

##### 06/10/2020
* Upload segmentation models (in `RD`)

##### 06/12/2020
* Upload Lidar2image tools (in `LIDAR`)

##### 08/11/2020
* Finish Lidar2image tools (in `LIDAR`)

