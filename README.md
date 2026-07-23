# ✦ Lumina — Next-Gen AI Photo Studio & RAW Processor

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.0_Pro-blueviolet?style=for-the-badge&logo=appveyor" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Dependencies-Zero_Pure_JS-orange?style=for-the-badge" alt="Zero Dependencies">
  <img src="https://img.shields.io/badge/Performance-60_FPS_Canvas-brightgreen?style=for-the-badge" alt="Performance">
</p>

<p align="center">
  <b>A lightweight, ultra-fast, web-native digital darkroom & AI-enhanced photo editor built from scratch.</b>
  <br>
  <i>Pro-grade color science, non-destructive editing pipeline, real-time pixel math, and multi-model AI vision features — zero node_modules required.</i>
</p>

---

## 🔥 Why Lumina?

Lumina bridges the gap between heavyweight desktop editors (Lightroom / Capture One) and modern cloud AI capabilities. Running entirely in the browser using raw canvas manipulation, high-speed 3D LUT mathematical models, and client-side web workers, Lumina offers **zero-latency real-time editing** without heavy installations or subscription fees.

---

## ⚡ Key Highlights & Features

### 🎛️ Pro-Grade Tone & Light Engine
- **Full Exposure Range:** Precision control over EV stops, brightness, micro-contrast, highlights, and deep shadows.
- **Dynamic White/Black Point Clipping:** Preserve highlight detail and lift dark regions without crushing pixels.
- **Custom S-Curves:** Hardware-accelerated contrast mapping built directly over canvas pixel arrays.

### 📈 Master Tone Curves
- **Spline-Based Curve Editor:** Cubic Hermite spline interpolation for continuous, natural tonal control.
- **Multi-Channel Precision:** Independent channel tuning across **RGB**, **Red**, **Green**, and **Blue** channels.
- **Double-Click Reset & Real-Time Nodes:** Interactive draggable curve handles with live rendering feedback.

### 🎨 HSL & Multi-Zone Color Grading
- **8-Channel Color Mixer:** Dedicated Hue, Saturation, and Luminance adjustment for Red, Orange, Yellow, Green, Aqua, Blue, Purple, and Magenta.
- **Hollywood Split-Toning:** Independent Hue/Sat/Luminance color wheel mapping for **Shadows**, **Midtones**, and **Highlights**.
- **Teal & Orange Cinematic Engine:** Instant cinematic color transformations engineered specifically for visual narrative depth.

### 🧠 Multi-Provider AI Vision Engine
- **Supported AI Providers:** Integrated API bindings for **Anthropic (Claude 3.5)**, **OpenAI (GPT-4o)**, **Google Gemini 1.5 Pro**, and **DeepSeek**.
- **Auto-Tone ML:** Local pixel luminosity histogram analysis combined with LLM inference to automatically determine optimal exposure parameters.
- **Smart Scene Enhance:** Content-aware enhancement algorithms tuned for Landscapes, Portraits, Night/Low-Light, and Sky Optimization.
- **Magic Retouching & Restoration:** One-click Magic Unblur, AI Denoising, and Face-Aware Portrait smoothing.

### 🔬 Real-Time Scopes & Canvas Tools
- **Live Tri-Color Histogram:** RGB and Luminance overlap visualization updating at 60 FPS.
- **A/B Split-Screen Compare:** Live draggable before/after curtain slider.
- **Interactive Spot Healing & Eyedropper:** In-canvas pixel color sampling and dynamic surround-averaging spot removal.
- **Non-Destructive Transform Stack:** Arbitrary horizontal/vertical flipping, degree-precise rotation, zoom, and panning.

---

## 🛠️ Built With

| Tech | Role |
| :--- | :--- |
| **HTML5 Canvas 2D API** | Pixel manipulation, custom unsharp masking, and radial vignette math. |
| **Vanilla ES6+ JavaScript** | Zero frameworks, zero bundlers. Pure high-performance code execution. |
| **CSS3 Custom Variables & Glassmorphism** | Modern, dark-room visual interface inspired by DaVinci Resolve. |
| **RESTful LLM API Connectors** | Direct client-side streaming & JSON inference calls to top AI engines. |

