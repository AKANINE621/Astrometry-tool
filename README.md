# ⭐ Star Astrometr

**Star Astrometr** is an open-source Python 3 tool for performing basic astrometric analysis from `.fits` (Flexible Image Transport System) images. It automatically detects stars and generates three types of visualizations: heatmap, histogram, and scatter plot.

## 📌 Overview

Star Astrometr is designed for amateur and professional astronomers who want to extract positional and brightness data from astronomical images. It helps users analyze star distributions and intensity patterns efficiently using Python-based plotting.

---

## ✨ Features

- ✅ Input: `.fits` image files
- ✅ Output: three types of plots
  - 🌡️ **Heatmap** — star density visualization
  - 📊 **Histogram** — pixel brightness distribution
  - 🌌 **Scatter Plot** — star positions in 2D space
- ✅ Cross-platform: Works on Windows, Linux, and macOS
- ✅ Lightweight and easy to use
- ✅ Open source (MIT License)

---

## 🧰 Installation

### 📦 Requirements

- Python **3.8 or newer**
- pip package manager

### 🔧 Install on Windows / macOS / Linux

```bash
# Clone the repository
git clone https://github.com/AKANINE621/Star-Astromet.git
cd star-astrometr

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
