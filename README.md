# ⭐ Star Astrometr

**Star Astrometr** is an open-source Python 3 application that processes `.fits` files and generates astrometric visualizations. The program supports three types of plots: **scatter plot**, **histogram**, and **heatmap**, all based on detected star coordinates using WCS (World Coordinate System).

---

## 📸 What It Does

- Loads `.fits` images from a folder
- Randomly samples star-like pixel coordinates
- Transforms pixel positions to WCS (RA/DEC)
- Generates:
  - 🌌 **Scatter Plot** of star positions
  - 📊 **Histogram** of RA and DEC distributions
  - 🌡️ **Heatmap** of raw FITS image intensity

---

## 📦 Installation

### ⚙️ Requirements

- Python 3.8+
- pip

### 🖥️ Windows / 🐧 Linux / 🍎 macOS

```bash
# Clone the repository
git clone https://github.com/AKANINE621/Star-Astromet.git
cd star-astrometr

# (Optional) Create and activate a virtual environment
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
