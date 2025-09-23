# Feature 025: Daily Symptom Tracking

## 🧑‍💻 Category:
- Patient-Centered

## 📝 Description:
Enables patients to log physical and systemic symptoms daily to monitor disease progression, treatment response, or new health concerns.

## 📋 Symptom Types:
- **General**: Fever, fatigue, weight loss
- **Respiratory**: Cough, shortness of breath, chest pain
- **Gastrointestinal**: Nausea, diarrhea, abdominal pain
- **Neurological**: Headache, dizziness, numbness
- **Pain**: Location, intensity (1–10), type (sharp, dull, throbbing)

## 📱 Input Methods:
- Quick-select from categorized list
- Body map: Tap area of pain/discomfort
- Voice input: “I have a headache and nausea”
- Severity slider + duration (hours/days)

## 📊 Visualization & AI:
- Symptom timeline with intensity heat map
- Correlation alerts:  
  “Headaches often follow poor sleep (see feature-003)”  
  “Nausea increases after taking Drug X (see feature-018)”
- Weekly report: “Top 3 symptoms this week: fatigue, cough, low appetite”

## 🔄 Dependencies:
- Medical history (feature-017)
- Medication log (feature-018)
- Sleep & activity data (features 003, 028)
- AI pattern detection (feature-057)
- Chest disease detection (feature-024)

## 📤 Sharing:
- Export symptom log for doctor visits
- Auto-include in telemedicine appointments (feature-080)
