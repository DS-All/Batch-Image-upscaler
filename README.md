# 🔼 AI Image Upscaler (RealESRGAN GUI)

A simple, fast, and user-friendly desktop application for upscaling **real human photos** using **Real-ESRGAN**.  
Designed and packaged with **PyInstaller**, the app works fully offline and supports both **CPU** and **GPU** modes.

---

## 🚀 Features

### ✅ Super-Resolution Upscaling
- Supports **2×** and **4×** upscaling.
- Automatically converts images to RGB for consistent results.
- Works with: `.png`, `.jpg`, `.jpeg`, `.bmp`.

### ✅ GPU Acceleration (Optional)
- Detects GPU automatically.
- Checkbox to enable/disable GPU.
- Uses FP16 mode on CUDA for faster inference.

### ✅ Batch Processing
- Select input folder → processes all images inside.
- Saves results into the chosen output folder.
- Real-time progress bar with image counter (e.g., `12 / 87`).

### ✅ Local Model Support
- Reads `.pth` model files from the project `/models/` directory.
- Currently supports:
  - **RealESRGAN_x2plus.pth**
  - **RealESRGAN_x4plus.pth**

### ✅ User-Friendly GUI
- Built with **Tkinter**.
- No command line required.
- Clean, simple layout.

---

## 📦 Installation (For Developers)

### 1️⃣ Clone the repository
```bash
git clone https://github.com/DS-All/AI-Image-Upscaler.git
cd Upscaler
