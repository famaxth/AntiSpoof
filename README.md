# 🎙 Fake Voice Detection with LightCNN (PyTorch)

This project was developed as part of the **Summer Research Practice at HSE University**.  
It implements and trains a **LightCNN**-based model to detect **synthetic (spoofed) speech** using the **ASVSpoof 2019** dataset.  

The system is trained to distinguish between genuine and fake audio samples and achieves an **Equal Error Rate (EER)** of approximately **4%**.  

---

## 📌 Features
- **LightCNN architecture** optimized for audio-based anti-spoofing  
- Preprocessing pipeline for ASVspoof 2019 dataset  
- Training and evaluation scripts in PyTorch  
- Achieved **~4% EER** on evaluation set  
- Supports GPU acceleration

---

## 🛠 Tech Stack
- **Language:** Python  
- **Framework:** PyTorch  
- **Model:** LightCNN  
- **Dataset:** ASVspoof 2019  
- **Metric:** Equal Error Rate (EER)

---

![Accuracy Plot](assets/accuracy1.png)
![Accuracy Plot](assets/accuracy2.png)
