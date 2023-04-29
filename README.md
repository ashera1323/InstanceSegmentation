# InstanceSegmentation
# ObjectDetection

This is computer vision project aimed to train models Yolo8 and Detectron2 to detect Fir-tree and Yandex rovers on pictures.
In the proccess, after processing all steps and evaluation: Detectron2 model achived more accurate results.

Models used: Yolov8 and Detectron2.

More about models itself you can read on: https://roboflow.com/model/yolov8 and https://roboflow.com/model/detectron2.

Dataset: consists of 100 pictures: Fir-trees and Yandex rovers. Picture size: 6000 x 4000. Resolution: 72 x 72

Dataset itself: https://app.roboflow.com/innopolis-university-ixqwo/treeroverinstancesegmentation/1

#### Step 1: Dataset Collection.
Dataset was colected manually: 100 photos of fir-tree and yandex rovers was taken.
#### Step 2: Segmentation labels on object using roboflow <img width="1438" alt="Снимок экрана 2023-04-29 в 19 55 32" src="https://user-images.githubusercontent.com/80173158/235314463-5d0b8dde-af3c-42af-a54f-e0709d3532f3.png">

#### Step 3: After data preperation, we push our dataset to detectron2 model: fit and train it.<img width="512" alt="Снимок экрана 2023-04-29 в 19 57 05" src="https://user-images.githubusercontent.com/80173158/235314523-358bd5fc-4522-480f-810f-56c5960fd4e4.png">

link to colab: https://colab.research.google.com/drive/1AOMx4YdLHg5S_XWWW_eV4O2fNObh5nYA?usp=sharing

### Step 4: Train Yolov8 in the same manner.

link to colab: https://colab.research.google.com/drive/1eK3H5wxiKhJWRzAiHYU9FcM_v_eK52_1?usp=sharing

### Step 5: Evaluation. 
Yolov8: <img width="1292" alt="Снимок экрана 2023-04-29 в 19 59 17" src="https://user-images.githubusercontent.com/80173158/235314623-5913a521-609c-4f52-ac74-34865fded078.png">

detectron2:
<img width="1165" alt="Снимок экрана 2023-04-29 в 20 00 28" src="https://user-images.githubusercontent.com/80173158/235314667-3e5eedf7-eca0-49c4-a7ac-9fe6d73c0b34.png">
