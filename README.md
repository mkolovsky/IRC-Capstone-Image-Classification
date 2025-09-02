# 🌲 IRC Trail Use Detection Model  

This repository contains the **final trained YOLOv5 model (`best.pt`)** from the Loyola Marymount University MSBA Capstone Project, in partnership with the **Irvine Ranch Conservancy (IRC)**.  

The model detects and classifies trail camera images into four categories:  
- 🚶 Pedestrian  
- 🚴 Cyclist  
- 🐎 Equestrian  
- 🚙 Vehicle  

---

## 📂 Repository Contents  
- `best.pt` → Final YOLOv5 trained model weights.  
- `IRC Label Studio + YOLOv5 Model Guide.pdf` → Step-by-step instructions for labeling, exporting, and preparing data, then using the model in **AddaxAI**.  

---

## ⚙️ How to Use  

### 1. Upload the Model to AddaxAI  
1. Log in to [AddaxAI](https://addax.ai).  
2. Navigate to the **Model Upload** section.  
3. Select and upload the `best.pt` file from this repository.  
4. Once uploaded, AddaxAI will handle inference, generating detections and dashboards.  

### 2. Label Studio Workflow (Optional — if training new models)  
If you need to re-train or expand the dataset, follow the included PDF guide:  
- Set up **Label Studio** for image annotation.  
- Export labels in YOLO format.  
- Train YOLOv5 in Google Colab using the steps provided.  
- Upload the newly generated `best.pt` into AddaxAI.  

---

## 📊 Model Performance (Final Evaluation)  
- **mAP50:** 96.4%  
- **Precision:** 90.1%  
- **Recall:** 94.5%  
- **F1-Score:** 92.1%  

---

Advisors: LMU Faculty  

---

⚡ **Note:** For most users, the only required step is to **upload `best.pt` into AddaxAI**. The Label Studio guide is included for those who wish to replicate or extend the training process.
