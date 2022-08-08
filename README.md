<p align="center"> <img src="https://img.shields.io/badge/I%20Support-%20%F0%9F%87%B5%F0%9F%87%B8%20Palestine-007A3D" alt="m0xyasser" /> </p>

<p align="center"> <img src="https://img.shields.io/badge/YOLO-v7-red" alt="m0xyasser" /> </p>


# what's new in Yolov7 ?

- [YOLOv7 Paper](https://arxiv.org/pdf/2207.02696.pdf)
- [YOLOv7 Breakdown](https://blog.roboflow.com/yolov7-breakdown/)

# Training a Custom YOLOv7 Model (Google Colab)

1. Preparing a Dataset to train [Roboflow](https://docs.roboflow.com/quick-start)

    1. [Quick Start](https://www.youtube.com/watch?v=O-ZPxTpb2Yg) **(Video)**
    1. [Adding Data](https://docs.roboflow.com/adding-data) **(Doc)**
    1. [Annotate](https://www.youtube.com/watch?v=pJaM06FG-wQ) **(Video)**
    1. [Dataset Health Check](https://www.youtube.com/watch?v=wuEilfYbHDQ) **(Video)**
    
1. Open [YOLOv7 Colab notebook](https://colab.research.google.com/drive/1X9A8odmK4k6l26NDviiT6dd6TgR-piOa) OR [YOLOv7 Colab notebook](https://colab.research.google.com/drive/1X9A8odmK4k6l26NDviiT6dd6TgR-piOa)
    - After you finish making and annotating the dataset, export the data in (YOLO v7 PyTorch) format and then Paste the snippet into a notebook in section `Download Correctly Formatted Custom Data`
    
1. Then follow the instructions of the **YOLOv7 Colab notebook**

# Training a Custom YOLOv7 Model (On Device)

## **1. Installing Yolov7 :**

Open Terminal then Write :
```shell
git clone "https://github.com/M0xYasser/Train-By-YOLOv7x.git"

```
OR :

Click Here To [Download](https://github.com/M0xYasser/Train-By-YOLOv7x/archive/refs/heads/main.zip)

## **2. Installing our dependencies :**

```shell
cd yolov7
pip3 install -r requirements.txt
```

## **3. Getting our pretrained model :**

```shell
wget https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7x.pt
```

## **4. Detect Images :**

```shell
python3 detect.py --weights /runs/train/exp2/weights/best.pt --conf 0.65 --source /content/gdrive/MyDrive/yolov7/smartCart-2/test/videos/20220808_120214.mp4```

# Resources

1. [Training YOLOv7 in Google Colab Course](https://store.augmentedstartups.com/605618c8-d8c8-4a25-be71-852308115520)
2. [Products DataSet V2](https://app.roboflow.com/project-uc8wq/smartcart-lxoxy/2) by [@M0xYasser](https://github.com/M0xYasser)
3. [YOLOv5 training with custom data](https://www.youtube.com/watch?v=GRtgLlwxpc4) **(MakeSence)**
4. [How to Train YOLO v5 on a Custom Dataset](https://www.youtube.com/watch?v=MdF6x6ZmLAY&t=524s) **(RoboFlow)**

# Models Trainned (YOLOv7x)

<details>
<summary> Model 1️⃣  </summary>
    
- **Model 1️⃣ >>** [URL](https://drive.google.com/drive/folders/1usN_U6H86pDW9ckbOsxY7Hmywnji7FCx?usp=sharing)
    
- **P_curve**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183253669-26939809-2cc1-4e5a-a9a9-c56049e6a280.png" alt="P_curve" /> </p>

- **R_curve**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183253667-420ed06f-7496-4ccf-b3ae-287fef9c44ac.png" alt="R_curve" /> </p>

- **PR_curve**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183253671-43f96edc-8cfa-450a-98bf-ecda0cb4e844.png" alt="PR_curve" /> </p>
    
- **Confusion_matrix**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183253665-71a16ac5-fb6f-4b7f-82fb-ace28a4b02a5.png" alt="confusion_matrix" /> </p>

- **Detection detected**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183254311-57cd01e5-c07d-4722-a977-ef6ae7434a11.jpg" /> </p>
    
- **Detection not detected**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183254309-66e3827f-8035-4b7d-8c8c-7a02ccb13850.jpg" /> </p>
</details>

<details>
<summary> Model 2️⃣  </summary>
    
- **Model 2️⃣ >>** [URL](https://drive.google.com/drive/folders/1iYqNkSk1soBe-5X_c3UzOkK45t0ysi2e?usp=sharing)
    
- **P_curve**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183254857-4b0c0ea0-7847-4060-926e-87379088e000.png" alt="P_curve" /> </p>

- **R_curve**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183254860-db43c8dc-048e-4131-9951-8009ee76bf6c.png" alt="R_curve" /> </p>

- **PR_curve**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183254861-205e1201-9f70-4ad8-844b-f02e552eb774.png" alt="PR_curve" /> </p>
    
- **Confusion_matrix**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183254864-b893aa61-b24a-45b7-ac2a-c2a2ba1a4ffa.png" alt="confusion_matrix" /> </p>

- **Detection detected**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183254855-da95e61c-cf4a-45b3-ad98-f74ee03ce914.jpg" /> </p>
    
- **Detection not detected**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183254853-bc90d6b4-67a8-4647-9afb-9b402e27b161.jpg" /> </p>
</details>

<details>
<summary> Model 3️⃣  </summary>
    
- **Model 3️⃣ >>** [URL](https://drive.google.com/drive/folders/1ukIbNcojwGMqp9pKiS3zFUOSw4YVj0rL?usp=sharing)
    
- **P_curve**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183255104-6abdf78e-a989-4058-bf51-e0df26454e2d.png" alt="P_curve" /> </p>

- **R_curve**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183255100-6d841613-b5c7-4b04-82f3-0a7522d92b5d.png" alt="R_curve" /> </p>

- **PR_curve**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183255102-56265ed7-4d6d-4d18-b9dc-0b6821af08ed.png" alt="PR_curve" /> </p>
    
- **Confusion_matrix**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183255107-12046546-96f7-4589-8e53-492fb6332bcc.png" alt="confusion_matrix" /> </p>

- **Detection detected**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183255099-7132df1a-3344-4534-81e4-fab8207a7a00.jpg" /> </p>
    
- **Detection not detected**
<p align="center"> <img src="https://user-images.githubusercontent.com/47388207/183255095-10d79bdf-2316-44be-91f5-ea411d2dde4f.jpg" /> </p>
</details>
