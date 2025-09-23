# Feature 018: Complete Medication History Log

## 🧑‍💻 Category:
- Patient-Centered

## 📝 Description:
A detailed, chronological record of all medications the patient has taken, including:

- Current prescriptions
- Past medications (with start/end dates)
- Over-the-counter drugs (e.g., ibuprofen, antihistamines)
- Supplements (linked to feature-016)
- Dosage, frequency, and route (oral, injection, etc.)
- Prescribing doctor & pharmacy
- Reason for use (e.g., “Amoxicillin — for sinus infection, Jan 2024”)

## 📥 Input Methods:
- Manual entry
- Scan prescription labels (see feature-117)
- Import from pharmacy systems (feature-078)
- Voice input: “I took Metformin 500mg twice daily from 2020 to 2023”

## 🔍 Features:
- Timeline view of medication use
- Search by drug name, condition, or date
- “Medication Summary” PDF for doctor visits
- Highlight gaps or overlaps in treatment

## 🔄 Dependencies:
- Pharmacy integration (feature-078)
- Drug database (feature-047)
- Medical history (feature-017)
- AI for parsing scanned prescriptions (future CV/NLP)
- Drug interaction checker (feature-040)

## ⚠️ Safety Note:
- Flags discontinued meds that may still be in system
- Reminds: “You stopped this 6 months ago — don’t restart without consulting doctor”
