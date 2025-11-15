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

##       AI IMAGE UPSCALER — USER GUIDE 

- This application uses advanced AI (Real-ESRGAN) to upscale
photos in high quality. No installation required.

- ZIP Password: 1234

### 📦 CONTENTS (INSIDE THE ZIP)

```bash
Upscaler/
│   Upscaler.exe        → The program
│   README.txt          → Instructions
│
├── models/             → AI model files (.pth)
└── _internal/          → Required dependencies (DO NOT DELETE)
```


### HOW TO USE (NORMAL USERS)


### 1️⃣ Extract the ZIP properly**

Right-click the ZIP → “Extract All…”

- ✔ Enter password: **1234**
- ✔ You MUST extract the whole folder.
- ✔ Do NOT run Upscaler.exe directly inside the ZIP!


### 2️⃣ Open the program

Inside the extracted folder:

    Upscaler.exe

Double-click to open.


### 3️⃣ Choose your input & output folders

- Input folder = The folder where your images are located  
- Output folder = Where upscaled images will be saved  

Supported file types:
    PNG, JPG, JPEG, BMP


### 4️⃣ Choose Upscale Factor

Options:
    2×     → Best quality / recommended  
    4×     → Very large images (slower)


### 5️⃣ Choose GPU or CPU

✔ If your PC has an NVIDIA GPU:
      Keep “Use GPU” checked (much faster)

✔ If not:
      Uncheck it → Runs on CPU


### 6️⃣ Start Upscaling

Press:

    Start Upscaling

The program will show:
    - Progress bar  
    - “image 3 / 20” counter  
    - Status messages  


### 7️⃣ Where are my upscaled images saved?

Inside your chosen Output Folder:

    upscaled_Filename.png



## **IMPORTANT NOTES** 

**⚠ DO NOT DELETE:**

    _internal/ folder  
    models/ folder  

The program will NOT run without them.

**⚠ You must always run:**

    Upscaler.exe
    (not any file inside _internal)



## SYSTEM REQUIREMENTS

- ✔ Windows 10 / 11 (64-bit)
- ✔ 4GB RAM minimum (8GB recommended)
- ✔ GPU acceleration requires:
      - NVIDIA GPU
      - CUDA-compatible driver






## 📦 Installation (For Developers)

### 1️⃣ Clone the repository
```bash
git clone https://github.com/DS-All/AI-Image-Upscaler.git
cd Upscaler
```

### 2️⃣ Create a virtual environment
```bash
python -m venv venv
```

### 3️⃣ Activate it

Windows:
```bash
venv\Scripts\activate
```
macOS/Linux:
```bash
source venv/bin/activate
```

### 4️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
### 5️⃣ Place model files

Download RealESRGAN models and place them into:
```bash
Upscaler/models/
```

## TROUBLESHOOTING

### 💥 Program does not open  
→ Make sure you extracted the ZIP first  
→ Do not run directly from inside the ZIP  
→ Ensure _internal folder is next to Upscaler.exe  

### 💥 GPU option not working  
→ Your PC may not have an NVIDIA GPU  
→ Install latest NVIDIA drivers  

### 💥 “Model file not found”  
→ Ensure *.pth files exist inside the models/ folder

### VERSION HISTORY

v1.0 — Initial release
   - 2×/3×/4× Real-ESRGAN upscaling
   - GPU/CPU toggle
   - Batch folder support
   - Progress bar and counter

THANK YOU FOR USING
AI IMAGE UPSCALER ❤️

