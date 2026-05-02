<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=220&section=header&text=Kallol%20Chakraborty&fontSize=52&fontColor=00d9ff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20Medical%20Imaging%20%7C%20Deep%20Learning%20for%20Human%20Health&descAlignY=60&descSize=17&descColor=ffffff" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2500&pause=800&color=00D9FF&center=true&vCenter=true&multiline=false&width=650&lines=Building+AI+that+detects+brain+tumors+%F0%9F%A7%A0;Diagnosing+chest+diseases+from+X-Rays+%F0%9F%AB%81;Detecting+bone+fractures+in+real-time+%F0%9F%A6%B4;Making+healthcare+smarter+with+deep+learning+%E2%9D%A4%EF%B8%8F)](https://git.io/typing-svg)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=kolloln&color=00d9ff&style=for-the-badge&label=PROFILE+VIEWS)
![GitHub Followers](https://img.shields.io/github/followers/kolloln?style=for-the-badge&color=00d9ff&labelColor=0d1117)

</div>

---

## 👨‍💻 Who Am I

```yaml
name         : Kallol Chakraborty
role         : AI Engineer — Medical Imaging & Deep Learning
company      : Medical AI Research
location     : Bangladesh 🇧🇩
experience   : Computer Vision · PyTorch · Medical Image Analysis
passion      : "Using AI to detect diseases earlier, faster, and more accurately"
available    : Open to collaborations & research projects ✅
```

---

## 🔥 Currently Working On

| Project | Description | Status |
|---------|-------------|--------|
| 🧠 **Brain Tumor Analysis** | Multi-class MRI classification + U-Net segmentation | `✅ Complete` |
| 🫁 **Chest X-Ray Diagnosis** | Pneumonia · COVID-19 · TB detection | `🔄 In Progress` |
| 🦴 **Bone Fracture Detector** | YOLOv8 real-time fracture localization | `🔄 In Progress` |
| 👁️ **Retinal Disease Grading** | Diabetic retinopathy 5-class grading | `📋 Planned` |
| 🔬 **Skin Lesion Classification** | Melanoma detection · ISIC dataset | `📋 Planned` |

---

## 🏥 Portfolio — Medical AI Projects

<details>
<summary><b>🧠 Brain Tumor Classification & Segmentation</b> — Click to expand</summary>
<br/>

**Goal:** Automatically classify and segment brain tumors from MRI scans

**What it does:**
- Classifies 4 tumor types: Glioma · Meningioma · Pituitary · No Tumor
- U-Net pixel-level segmentation of tumor boundaries
- Grad-CAM explainability heatmaps for clinical trust

**Models used:** EfficientNet-B4 · ResNet50 · VGG16 · U-Net

**Results:**
| Model | Accuracy | AUC-ROC |
|-------|----------|---------|
| EfficientNet-B4 | **97.8%** | **0.995** |
| ResNet50 | 95.2% | 0.987 |
| U-Net Dice | **0.887** | — |

**Tech:** `PyTorch` `timm` `Albumentations` `MLflow` `ONNX`

[![View Repository](https://img.shields.io/badge/📁_View_Repository-181717?style=for-the-badge&logo=github)](https://github.com/kolloln/brain-tumor-analysis)

</details>

<details>
<summary><b>🫁 Chest X-Ray Disease Detection</b> — Click to expand</summary>
<br/>

**Goal:** Multi-label disease detection from chest radiographs

**Detects:** Pneumonia · COVID-19 · Tuberculosis · Pleural Effusion · Cardiomegaly

**Approach:**
- DenseNet121 backbone (pretrained CheXNet weights)
- Multi-label binary cross-entropy loss
- Class activation maps for lesion localization

**Dataset:** NIH ChestX-ray14 (112,000+ images)

**Tech:** `PyTorch` `DenseNet` `OpenCV` `FastAPI` `Docker`

</details>

<details>
<summary><b>🦴 Bone Fracture Detection</b> — Click to expand</summary>
<br/>

**Goal:** Real-time fracture detection and localization from X-rays

**Supports:** Hip · Wrist · Spine · Rib · Tibia fractures

**Approach:**
- YOLOv8 for bounding box detection
- Custom fracture classification head
- DICOM file support for clinical workflow

**Tech:** `YOLOv8` `OpenCV` `DICOM` `TensorRT`

</details>

<details>
<summary><b>👁️ Diabetic Retinopathy Grading</b> — Click to expand</summary>
<br/>

**Goal:** Grade retinopathy severity (0=No DR → 4=Proliferative)

**Approach:**
- EfficientNet-B5 with mixup augmentation
- Ordinal regression loss for grade ordering
- Deployed as REST API

**Dataset:** Kaggle DR Detection (88,702 fundus images)

**Tech:** `PyTorch` `FastAPI` `ONNX` `Docker`

</details>

---

## 📁 Repositories

<div align="center">

[![brain-tumor-analysis](https://github-readme-stats.vercel.app/api/pin/?username=kolloln&repo=brain-tumor-analysis&theme=tokyonight&hide_border=true&title_color=00d9ff&icon_color=00d9ff)](https://github.com/kolloln/brain-tumor-analysis)

</div>

---

## 🛠️ Tech Stack

<div align="center">

**Deep Learning Frameworks**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![MONAI](https://img.shields.io/badge/MONAI-0072C6?style=for-the-badge)

**Computer Vision**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Albumentations](https://img.shields.io/badge/Albumentations-FF4081?style=for-the-badge)
![timm](https://img.shields.io/badge/timm-Models-orange?style=for-the-badge)
![YOLO](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logoColor=black)

**MLOps & Deployment**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)

**Languages & Tools**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 📊 GitHub Stats

<div align="center">
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=kolloln&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&title_color=00d9ff&icon_color=00d9ff"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kolloln&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&title_color=00d9ff"/>
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=kolloln&theme=tokyonight&hide_border=true&ring=00d9ff&fire=ff6b6b&currStreakLabel=00d9ff" width="60%"/>
</div>

---

## 🎯 Domain Expertise

```
🧠  Neuroimaging          Brain MRI  →  Tumor Detection & Segmentation
🫁  Thoracic Imaging      Chest X-Ray  →  Pneumonia, COVID-19, TB
🦴  Musculoskeletal       X-Ray  →  Fracture Detection & Localization
👁️  Ophthalmology         Fundus  →  Diabetic Retinopathy Grading
🔬  Dermatology           Dermoscopy  →  Melanoma Classification
🫀  Cardiology            Cardiac MRI  →  Heart Segmentation
```

---

## 📫 Get In Touch

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-kolloln-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kolloln)
[![Email](https://img.shields.io/badge/Email-kallolchakraborty2019%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kallolchakraborty2019@gmail.com)

<br/>

💬 Open to: **Research Collaborations · Freelance Medical AI Projects · Open Source Contributions**

</div>

---

<div align="center">

> *"The goal of AI in medicine is not to replace the doctor — it's to give every patient access to the world's best diagnosis."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=120&section=footer" width="100%"/>

</div>
