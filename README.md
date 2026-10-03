# 🛰️ Satellite Oil Spill AI Analytics & Surveillance Dashboard

An AI-powered Satellite SAR Image Processing and Marine Surveillance Analytics Dashboard built using Python, OpenCV, and Streamlit.

## 🌟 Key Features
- **Real-time SAR Image Processing:** Detects oil spill patches using OpenCV Adaptive Thresholding and U-Net Deep Learning Segmentation.
- **Glassmorphic Interactive UI:** Custom modern Ocean/Satellite theme with animated floating satellite orbit.
- **Precision Metrics:** Calculates Accuracy, Mean IoU (Intersection over Union), and Dice Similarity Coefficient.
- **Spatial GPS Mapping:** Pinpoint geographical location of detected spills on interactive maps.
- **Patch Inspection Table:** Detailed pixel area breakdown and bounding box coordinates for marine response teams.

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Satellite-Oil-Spill-Dashboard.git](https://github.com/YOUR_USERNAME/Satellite-Oil-Spill-Dashboard.git)
   cd Satellite-Oil-Spill-Dashboard

1. Install dependencies:
    Bash
    pip install -r requirements.txt

2. Run the Streamlit application:
    Bash
    streamlit run app.py