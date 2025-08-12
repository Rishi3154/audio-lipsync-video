Audio Lip-Synced Video Generation (IEEE Published)

> **Deep learning pipeline to synchronize lip movements in video with any input speech audio.**  
> Implemented using **Wav2Lip** architecture for realistic, frame-accurate lip movement generation.  
> 📄 *Published in IEEE Xplore — [Read Paper](https://ieeexplore.ieee.org/document/10866375)  

---


## 📸 Screenshots

![Demo Screenshot 1](screenshots/demo 1.png)  
*Figure 1: Generated lip-synced frame showing Mona Lisa with realistic mouth movements.*

![Demo Screenshot 2](screenshots/demo 2.png)  
*Figure 2: Another frame demonstrating smooth lip transitions in sync with speech.*


---


## 📌 Abstract
This project focuses on generating **lip-synced videos** by aligning facial movements with arbitrary speech audio using state-of-the-art deep learning models.  
The implementation is based on the **Wav2Lip** architecture, which ensures precise temporal alignment between audio and video frames without requiring manual annotations.  

The system can be used in:
- Film dubbing automation
- Accessibility tools for the hearing impaired
- Real-time virtual avatars

---

## Tech Stack
- **Language:** Python 3.8+
- **Frameworks & Libraries:** PyTorch, NumPy, OpenCV, librosa, ffmpeg
- **Model:** Wav2Lip (GAN-based architecture)
- **Tools:** Jupyter Notebook, Google Colab, CUDA-enabled GPU

---

## Features
- Synchronizes lip movements in video with arbitrary speech audio
- Works with any clear frontal-face video
- High visual realism using GAN-based architecture
- Frame-accurate temporal alignment


