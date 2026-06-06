# 🏥 SepsisNet — ICU Early Warning Dashboard

A clinical decision support tool for early sepsis detection in ICU patients using qSOFA and SIRS scoring algorithms.

## 🔍 Features
- qSOFA score calculator (Quick Sequential Organ Failure Assessment)
- SIRS criteria checker (Systemic Inflammatory Response Syndrome)
- Real-time risk level classification (Low / Medium / High)
- Clean, minimal clinical UI
- Runs entirely in browser — no installation needed

## 🛠️ Tech Stack
| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Scoring Logic | qSOFA + SIRS algorithms |
| Deployment | Static — runs in any browser |

## 📊 Scoring Criteria
**qSOFA (≥2 = High Risk)**
- Respiratory rate ≥ 22/min
- Altered mentation (GCS < 15)
- Systolic BP ≤ 100 mmHg

**SIRS (≥2 = Positive)**
- Temperature > 38°C or < 36°C
- Heart rate > 90 bpm
- Respiratory rate > 20/min
- WBC > 12,000 or < 4,000

## 🚀 How to Use
1. Open `SepsisNet_Dashboard.html` in any browser
2. Enter patient vitals
3. Get instant sepsis risk score and recommendation

## ⚠️ Disclaimer
This tool is intended for educational purposes only and is not a substitute for clinical judgment.

## 👨‍💻 Author
Bharath — Biomedical Engineering, Excel Engineering College  
[GitHub](https://github.com/Bharathraj-rcode)
