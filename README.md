<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:0a3d62,70:1a5276,100:00d9ff&height=230&section=header&text=Kallol%20Chakraborty&fontSize=55&fontColor=ffffff&fontAlignY=40&animation=fadeIn&desc=AI%20Engineer%20%7C%20Medical%20Imaging%20%7C%20Deep%20Learning%20for%20Human%20Health&descAlignY=62&descSize=18&descColor=a0d8ef" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2000&pause=600&color=00D9FF&center=true&vCenter=true&width=820&lines=🧠+Brain+Tumor+Classification+%26+Segmentation;🫁+Chest+X-Ray+Multi-Disease+Diagnosis;🦴+Real-Time+Bone+Fracture+Detection;👁️+Diabetic+Retinopathy+Grading;🔬+Skin+Lesion+%26+Melanoma+Detection;🫀+Cardiac+Structure+Segmentation;🫧+COVID-19+%26+Lung+Disease+from+CT;🧬+Alzheimer%E2%80%99s+Disease+Classification;🔴+Blood+Cell+Detection+%26+Analysis;🔵+Kidney+Stone+%26+Liver+Tumor+Detection;❤️+Building+AI+That+Saves+Lives)](https://git.io/typing-svg)

<br/>

[![GitHub followers](https://img.shields.io/github/followers/kolloln?style=for-the-badge&color=00d9ff&labelColor=0d1117&logo=github)](https://github.com/kolloln)
![Profile Views](https://komarev.com/ghpvc/?username=kolloln&color=00d9ff&style=for-the-badge&label=PROFILE+VIEWS)
[![Medical AI](https://img.shields.io/badge/🏥_Medical_AI_Engineer-0d1117?style=for-the-badge&labelColor=00d9ff&color=0d1117)]()
[![Open To Work](https://img.shields.io/badge/💼_Open_To_Collaborate-brightgreen?style=for-the-badge)]()

</div>

---

## 👨‍💻 About Me

<img align="right" width="340" src="https://raw.githubusercontent.com/Potential17/Potential17/master/user%20(2).gif"/>

I am an **AI Engineer** specializing in **Medical Imaging and Deep Learning**, dedicated to building intelligent systems that detect, classify, and segment human diseases from medical images.

My work spans across **10+ medical AI projects** covering neuroimaging, radiology, ophthalmology, dermatology, cardiology, and more — translating cutting-edge deep learning research into clinically useful tools.

**Mission:** *Make accurate disease diagnosis accessible to everyone through AI.*

```yaml
name       : Kallol Chakraborty
role       : AI Engineer — Medical Imaging & Deep Learning  
location   : Bangladesh 🇧🇩
company    : Medical AI Research
focus      : Disease Detection · Segmentation · Classification
frameworks : PyTorch · TensorFlow · MONAI · YOLOv8
status     : Open to Research Collaborations & Projects ✅
email      : kallolchakraborty2019@gmail.com
```

<br clear="right"/>

---

## 🔥 Project Overview

<div align="center">

| # | Project | Domain | Model | Dataset | Status |
|---|---------|--------|-------|---------|--------|
| 01 | 🧠 Brain Tumor Classification & Segmentation | Neuroimaging | EfficientNet-B4 + U-Net | Kaggle BraTS | ✅ Complete |
| 02 | 🫁 Chest X-Ray Disease Detection | Thoracic | DenseNet121 | NIH ChestX-ray14 | 🔄 Active |
| 03 | 🦴 Bone Fracture Detection | Musculoskeletal | YOLOv8 | MURA + Custom | 🔄 Active |
| 04 | 👁️ Diabetic Retinopathy Grading | Ophthalmology | EfficientNet-B5 | Kaggle DR | 🔄 Active |
| 05 | 🔬 Skin Lesion Classification | Dermatology | EfficientNet-B4 | HAM10000 | 📋 Planned |
| 06 | 🫀 Cardiac Segmentation (3D MRI) | Cardiology | 3D U-Net / MONAI | ACDC | 📋 Planned |
| 07 | 🫧 COVID-19 Detection from CT | Pulmonology | ResNet50 | SARS-CoV-2 CT | 📋 Planned |
| 08 | 🧬 Alzheimer's Disease Classification | Neurology | ViT + CNN | ADNI / OASIS | 📋 Planned |
| 09 | 🔴 Blood Cell Detection & Analysis | Hematology | YOLOv8 + CNN | BCCD Dataset | 📋 Planned |
| 10 | 🔵 Kidney Stone Detection | Urology | ResNet + Attention | CT Kidney Dataset | 📋 Planned |
| 11 | 🟠 Liver Tumor Segmentation | Gastroenterology | nnU-Net | LiTS Challenge | 📋 Planned |
| 12 | 🟢 Malaria Cell Detection | Infectious Disease | MobileNetV3 | NIH Malaria | 📋 Planned |

</div>

---

## 🏥 Portfolio — Medical AI Projects

---

### 🧠 01 — Brain Tumor Classification & Segmentation
<div>
<img src="https://img.shields.io/badge/Status-✅_Complete-brightgreen?style=flat-square"/>
<img src="https://img.shields.io/badge/Accuracy-97.8%25-00d9ff?style=flat-square"/>
<img src="https://img.shields.io/badge/Dice_Score-0.887-orange?style=flat-square"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/Dataset-Kaggle_BraTS-20BEFF?style=flat-square"/>
</div>

> Automated multi-class brain tumor detection and pixel-level segmentation from MRI scans.

**Tumor Classes:** Glioma · Meningioma · Pituitary Tumor · No Tumor

**Architecture:**
- **Classification:** EfficientNet-B4 (transfer learning) → Global Avg Pool → FC head → 4-class Softmax
- **Segmentation:** U-Net with skip connections → Dice+BCE loss → Binary tumor mask
- **Explainability:** Grad-CAM heatmaps for clinical trust

**Results:**
| Model | Accuracy | F1 | AUC-ROC |
|-------|----------|----|---------|
| ⚡ EfficientNet-B4 | **97.8%** | **0.977** | **0.995** |
| ResNet50 | 95.2% | 0.951 | 0.987 |
| VGG16 | 93.6% | 0.934 | 0.981 |
| U-Net Segmentation | Dice **0.887** | IoU **0.798** | — |

**Stack:** `PyTorch` `timm` `EfficientNet-B4` `U-Net` `Albumentations` `MLflow` `Grad-CAM` `ONNX`

[![View Repository](https://img.shields.io/badge/📂_View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kolloln/brain-tumor-analysis)

---

### 🫁 02 — Chest X-Ray Multi-Disease Diagnosis
<div>
<img src="https://img.shields.io/badge/Status-🔄_Active-yellow?style=flat-square"/>
<img src="https://img.shields.io/badge/Pathologies-14_Classes-purple?style=flat-square"/>
<img src="https://img.shields.io/badge/Dataset-NIH_ChestX--ray14-blue?style=flat-square"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
</div>

> Multi-label detection of 14 thoracic pathologies from chest radiographs.

**Detects:** Pneumonia · COVID-19 · Tuberculosis · Pleural Effusion · Cardiomegaly · Atelectasis · Consolidation · Edema · Emphysema · Fibrosis · Hernia · Infiltration · Mass · Nodule

**Architecture:** DenseNet121 (CheXNet pretrained) → Multi-label BCE → Class Activation Maps for lesion localization

**Stack:** `TensorFlow` `DenseNet121` `CheXNet` `OpenCV` `FastAPI` `Docker` `DICOM`

---

### 🦴 03 — Bone Fracture Real-Time Detection
<div>
<img src="https://img.shields.io/badge/Status-🔄_Active-yellow?style=flat-square"/>
<img src="https://img.shields.io/badge/Model-YOLOv8-00FFFF?style=flat-square"/>
<img src="https://img.shields.io/badge/Task-Object_Detection-red?style=flat-square"/>
<img src="https://img.shields.io/badge/Dataset-MURA-orange?style=flat-square"/>
</div>

> Real-time fracture detection and localization from X-ray images with bounding box output.

**Fracture Types:** Hip · Wrist · Radius · Spine · Rib · Tibia · Fibula

**Architecture:** YOLOv8 backbone → Custom fracture classification head → TensorRT deployment → DICOM file support

**Stack:** `YOLOv8` `OpenCV` `TensorRT` `DICOM` `FastAPI` `Docker`

---

### 👁️ 04 — Diabetic Retinopathy Grading
<div>
<img src="https://img.shields.io/badge/Status-🔄_Active-yellow?style=flat-square"/>
<img src="https://img.shields.io/badge/Grades-0_to_4-orange?style=flat-square"/>
<img src="https://img.shields.io/badge/Dataset-Kaggle_88K_Images-20BEFF?style=flat-square"/>
</div>

> 5-class severity grading of diabetic retinopathy from fundus photography.

**Grades:** No DR → Mild → Moderate → Severe → Proliferative DR

**Architecture:** EfficientNet-B5 + Mixup augmentation → Ordinal regression loss → REST API deployment

**Stack:** `PyTorch` `EfficientNet-B5` `Albumentations` `Mixup` `ONNX` `FastAPI`

---

### 🔬 05 — Skin Lesion & Melanoma Classification
<div>
<img src="https://img.shields.io/badge/Status-📋_Planned-lightgrey?style=flat-square"/>
<img src="https://img.shields.io/badge/Classes-7_Types-purple?style=flat-square"/>
<img src="https://img.shields.io/badge/Dataset-HAM10000-red?style=flat-square"/>
<img src="https://img.shields.io/badge/Target_AUC-0.94+-brightgreen?style=flat-square"/>
</div>

> 7-class skin lesion classification with melanoma detection on dermoscopy images.

**Classes:** Melanoma · Nevus · Basal Cell Carcinoma · Actinic Keratosis · Benign Keratosis · Dermatofibroma · Vascular Lesion

**Architecture:** EfficientNet-B4 → Focal Loss (class imbalance) → SHAP + Grad-CAM explainability

**Stack:** `PyTorch` `EfficientNet` `Focal Loss` `SHAP` `Grad-CAM` `Albumentations`

---

### 🫀 06 — Cardiac Structure Segmentation (3D MRI)
<div>
<img src="https://img.shields.io/badge/Status-📋_Planned-lightgrey?style=flat-square"/>
<img src="https://img.shields.io/badge/Model-3D_U--Net_MONAI-0072C6?style=flat-square"/>
<img src="https://img.shields.io/badge/Dataset-ACDC_Challenge-blue?style=flat-square"/>
</div>

> 3D segmentation of cardiac structures from cine MRI for automated cardiac analysis.

**Structures:** Left Ventricle · Right Ventricle · Myocardium

**Architecture:** 3D U-Net (MONAI framework) → Sliding window inference → Dice + Hausdorff distance metrics

**Stack:** `PyTorch` `MONAI` `3D U-Net` `NIfTI` `ITK` `VTK`

---

### 🫧 07 — COVID-19 & Lung Disease Detection from CT
<div>
<img src="https://img.shields.io/badge/Status-📋_Planned-lightgrey?style=flat-square"/>
<img src="https://img.shields.io/badge/Classes-4_Types-orange?style=flat-square"/>
<img src="https://img.shields.io/badge/Dataset-SARS--CoV--2_CT-blue?style=flat-square"/>
</div>

> Multi-class lung disease classification from CT scan slices.

**Classes:** COVID-19 · Pneumonia · Lung Cancer · Normal

**Architecture:** ResNet50 + Attention gate → Grad-CAM lesion localization → Deployment API

**Stack:** `PyTorch` `ResNet50` `OpenCV` `Attention` `FastAPI`

---

### 🧬 08 — Alzheimer's Disease Classification
<div>
<img src="https://img.shields.io/badge/Status-📋_Planned-lightgrey?style=flat-square"/>
<img src="https://img.shields.io/badge/Model-ViT+CNN_Hybrid-purple?style=flat-square"/>
<img src="https://img.shields.io/badge/Dataset-ADNI_OASIS-blue?style=flat-square"/>
</div>

> 4-stage Alzheimer's severity classification from structural brain MRI.

**Stages:** Non-Demented → Very Mild → Mild → Moderate Demented

**Architecture:** Vision Transformer (ViT) + CNN hybrid → Cross-attention fusion → 4-class output

**Stack:** `PyTorch` `ViT` `timm` `MONAI` `NiBabel`

---

### 🔴 09 — Blood Cell Detection & Analysis
<div>
<img src="https://img.shields.io/badge/Status-📋_Planned-lightgrey?style=flat-square"/>
<img src="https://img.shields.io/badge/Model-YOLOv8+CNN-00FFFF?style=flat-square"/>
<img src="https://img.shields.io/badge/Dataset-BCCD-red?style=flat-square"/>
</div>

> Automated blood cell detection, counting, and classification from microscopy images.

**Cell Types:** RBC · WBC (Neutrophil, Eosinophil, Basophil, Lymphocyte, Monocyte) · Platelets

**Architecture:** YOLOv8 for detection → CNN classifier for WBC subtype → Cell count output

**Stack:** `YOLOv8` `OpenCV` `PyTorch` `Microscopy`

---

### 🔵 10 — Kidney Stone Detection from CT
<div>
<img src="https://img.shields.io/badge/Status-📋_Planned-lightgrey?style=flat-square"/>
<img src="https://img.shields.io/badge/Model-ResNet+Attention-blue?style=flat-square"/>
<img src="https://img.shields.io/badge/Dataset-CT_Kidney-orange?style=flat-square"/>
</div>

> Binary classification and localization of kidney stones from CT scan images.

**Classes:** Normal · Cyst · Stone · Tumor

**Architecture:** ResNet50 + Squeeze-Excitation attention → Grad-CAM localization → Clinical report generation

**Stack:** `PyTorch` `ResNet50` `SE-Net` `Grad-CAM`

---

### 🟠 11 — Liver Tumor Segmentation
<div>
<img src="https://img.shields.io/badge/Status-📋_Planned-lightgrey?style=flat-square"/>
<img src="https://img.shields.io/badge/Model-nnU--Net-orange?style=flat-square"/>
<img src="https://img.shields.io/badge/Dataset-LiTS_Challenge-red?style=flat-square"/>
</div>

> Automatic liver and tumor segmentation from abdominal CT scans.

**Architecture:** nnU-Net (self-configuring) → 3D patch-based training → Multi-class segmentation (background · liver · tumor)

**Stack:** `nnU-Net` `PyTorch` `MONAI` `NIfTI` `SimpleITK`

---

### 🟢 12 — Malaria Cell Detection
<div>
<img src="https://img.shields.io/badge/Status-📋_Planned-lightgrey?style=flat-square"/>
<img src="https://img.shields.io/badge/Model-MobileNetV3-green?style=flat-square"/>
<img src="https://img.shields.io/badge/Dataset-NIH_Malaria-blue?style=flat-square"/>
</div>

> Lightweight malaria parasite detection for deployment on low-resource devices.

**Classes:** Parasitized · Uninfected

**Architecture:** MobileNetV3 (optimized for edge devices) → TFLite export → Android/Raspberry Pi deployment

**Stack:** `TensorFlow` `MobileNetV3` `TFLite` `OpenCV`

---

## 🛠️ Tech Arsenal

<div align="center">

**Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![MONAI](https://img.shields.io/badge/MONAI-0072C6?style=for-the-badge)

**Computer Vision**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Albumentations](https://img.shields.io/badge/Albumentations-FF4081?style=for-the-badge)
![timm](https://img.shields.io/badge/timm-Pretrained_Models-orange?style=for-the-badge)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logoColor=black)

**Models & Architectures**

![EfficientNet](https://img.shields.io/badge/EfficientNet-B4%2FB5-00d9ff?style=for-the-badge)
![U-Net](https://img.shields.io/badge/U--Net-Segmentation-9B59B6?style=for-the-badge)
![ResNet](https://img.shields.io/badge/ResNet-50%2F101-E74C3C?style=for-the-badge)
![ViT](https://img.shields.io/badge/Vision_Transformer-ViT-2ECC71?style=for-the-badge)

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

## 🎯 Research Focus

```
🧠  Neuroimaging           Brain MRI → Tumor Classification & Segmentation    ████████████  100%
🫁  Thoracic Radiology     Chest X-Ray → 14-Class Disease Detection           ████████████   85%
🦴  Musculoskeletal        X-Ray → Real-Time Fracture Localization             ██████████░░   80%
👁️  Ophthalmology          Fundus → Retinopathy Grading                       ████████░░░░   65%
🔬  Dermatology            Dermoscopy → Melanoma & Lesion Classification       ███████░░░░░   55%
🫀  Cardiology             Cardiac MRI → 3D Structure Segmentation             ██████░░░░░░   50%
🫧  Pulmonology            CT Scan → COVID-19 & Lung Disease                  ██████░░░░░░   50%
🧬  Neurology              MRI → Alzheimer's Stage Classification              █████░░░░░░░   40%
```

---

## 📊 GitHub Stats

<div align="center">
<img height="175em" src="https://github-readme-stats.vercel.app/api?username=kolloln&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&title_color=00d9ff&icon_color=00d9ff&text_color=ffffff&bg_color=0d1117"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kolloln&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&title_color=00d9ff&text_color=ffffff&bg_color=0d1117"/>
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=kolloln&theme=tokyonight&hide_border=true&ring=00d9ff&fire=ff6b6b&currStreakLabel=00d9ff&background=0d1117" width="55%"/>
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=kolloln&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=00d9ff&line=00d9ff&point=ff6b6b&area=true" width="95%"/>
</div>

---

## 🐍 Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kolloln/kolloln/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kolloln/kolloln/output/github-contribution-grid-snake.svg"/>
    <img alt="Snake animation" src="https://raw.githubusercontent.com/kolloln/kolloln/output/github-contribution-grid-snake-dark.svg"/>
  </picture>
</div>

---

## 📫 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-kolloln-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kolloln)
[![Email](https://img.shields.io/badge/Gmail-kallolchakraborty2019%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kallolchakraborty2019@gmail.com)

<br/>

**Open to:** `Medical AI Research` · `Freelance Projects` · `Open Source` · `Collaborations` · `Internships`

<br/>

> *"The goal of AI in medicine is not to replace doctors — it is to ensure no patient ever faces a critical diagnosis without the best intelligence available."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d9ff,50:1a5276,100:0d1117&height=130&section=footer&text=Building+AI+that+saves+lives+%F0%9F%8F%A5&fontSize=18&fontColor=ffffff&animation=twinkling" width="100%"/>

</div>

