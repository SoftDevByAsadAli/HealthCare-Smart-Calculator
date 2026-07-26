<div align="center">

# 🩺 Healthcare Smart Calculator (GUI)

### A Stylish Desktop Health Utility App — Python + Tkinter

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-0f766e?style=for-the-badge)
![Offline](https://img.shields.io/badge/Core%20App-100%25%20Offline-15803d?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-b45309?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.0.0-0369a1?style=for-the-badge)

**A single-file Tkinter desktop app for quick patient health calculations — BMI, age & patient category, temperature conversion, medicine dosage, and a full itemized medicine billing system with a built-in 40+ medicine price reference and one-click live price lookup.**

</div>

---

## ✨ Features

| 🎯 Feature | 📋 Description |
|---|---|
| 👤 **Patient Profile** | Add & view patient details (name, age, gender, weight, height, blood group) in one place |
| ⚖️ **BMI Calculator** | Calculates BMI with color-coded category (Underweight / Normal / Overweight / Obese) |
| 🎂 **Age Checker** | Classifies patient as Child / Teenager / Adult / Senior Citizen |
| 🏥 **Patient Category** | Classifies as Pediatric / General Patient / Geriatric |
| 🌡️ **Temperature Converter** | Quick Celsius → Fahrenheit conversion |
| 💊 **Medicine Dose Calculator** | Estimates recommended dose based on patient weight |
| 🧾 **Medicine Bill (Itemized)** | Add multiple medicines with quantity, auto-filled reference price, and running total |
| 📋 **40+ Medicine Price List** | Built-in local reference database across Pain, Antibiotics, Antacids, Allergy, Vitamins, Diabetes/BP & First Aid |
| 🌐 **Check Live Price** | One click opens your browser to see the real, current market price online |
| 🗑️ **Remove / Clear Bill Items** | Fix mistakes without starting over |
| 💾 **Export Receipt (.txt)** | Save a clean, professional bill file with patient info, itemized list, and grand total |
| 🖥️ **100% Offline Core** | No internet needed for any calculation — only the optional live price check opens a browser |

---

## 🎯 Concepts Covered (Week 1 — Python Basics)

| Concept | Where it's used |
|---|---|
| Variables & Data Types | Patient profile fields, bill entries |
| Operators | BMI formula, dosage calculation, bill totals |
| Control Flow (if/elif) | BMI category, age group, patient category logic |
| Functions | Every feature is a separate, reusable method |
| Error Handling (try/except) | All numeric inputs validated with friendly error messages |
| File Handling | Exporting the medicine bill as a `.txt` receipt |

---

## 🖼️ Preview

> Add your own screenshots here after running the app locally:
> `images/patient_tab.png`, `images/bmi_tab.png`, `images/bill_tab.png`

```
images/
├── patient_tab.png
├── bmi_tab.png
└── bill_tab.png
```

---

## 🛠️ Tech Stack

- **Language:** Python 3.10+
- **GUI Framework:** Tkinter (Python standard library — no extra install needed)
- **Storage:** None required (in-memory session; bill exports to `.txt` on demand)

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/<your-username>/healthcare-smart-calculator.git
cd healthcare-smart-calculator

# Run the app (no dependencies to install!)
python healthcare_smart_calculator_gui.py
```

> On Linux, if Tkinter isn't available by default:
> `sudo apt install python3-tk`

---

## 📖 How to Use

1. Go to **Patient Profile** tab → fill in details → click **Save Patient**
2. Use **BMI Calculator**, **Age Checker**, **Patient Category**, or **Medicine Dose** tabs — each pulls data from the saved patient automatically
3. Use **Temp Converter** anytime, independently
4. In **Medicine Bill**:
   - Pick a medicine from the dropdown (price auto-fills) or type a custom name
   - Adjust quantity with the spinbox
   - Click **Check Live Price** to verify the real current price in your browser
   - Click **Add to Bill**, repeat for more items
   - **Export Receipt** to save a `.txt` copy

---

## ⚠️ Disclaimer

This is an educational project. BMI, dosage, and medicine price data are for
learning purposes only and should **not** replace professional medical or
pharmacy advice. The built-in price list is a local reference (approximate,
editable) — always confirm current prices via the "Check Live Price" button
or your local pharmacy before billing.

---

## 📂 Project Structure

```
healthcare-smart-calculator/
├── healthcare_smart_calculator_gui.py   # Complete single-file application
├── images/                              # Screenshots (optional, for this README)
└── README.md
```

---

## 👤 Author

**Asad Ali**
BSIT Graduate | Aspiring Healthcare AI Informatics Specialist

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and share.

---

<div align="center">

### ⭐ If you find this project useful, consider giving it a star!

Made with ❤️ using Python & Tkinter

</div>
