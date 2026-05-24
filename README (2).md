# 🫁 PneumoScan AI — Chest X-Ray Pneumonia Detection

Hospital-Grade AI Dashboard built with EfficientNetB0 & MobileNetV2.

## 🚀 Live Demo
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://pneumoscan.streamlit.app)

## 📁 Required Model Files
Upload these files to the repo using Git LFS:
| File | Description |
|------|-------------|
| `eff_best_finetuned.h5` | EfficientNetB0 End-to-End |
| `mob_best_finetuned.h5` | MobileNetV2 End-to-End |
| `EfficientNetB0_plus_SVM.pkl` | EfficientNetB0 + SVM |
| `EfficientNetB0_plus_LR.pkl` | EfficientNetB0 + LR |
| `MobileNetV2_plus_SVM.pkl` | MobileNetV2 + SVM |
| `MobileNetV2_plus_LR.pkl` | MobileNetV2 + LR |

## ⚙️ Run Locally
```bash
pip install -r requirements.txt
streamlit run pneumonia_dashboard.py
```
