# Feature 021: Reminder for Routine Health Screenings

## 🧑‍💻 Category:
- Patient-Centered

## 📝 Description:
Automatically reminds patients about evidence-based, age- and risk-appropriate health screenings, such as:

- Blood tests (cholesterol, HbA1c, liver/kidney function)
- Cancer screenings (mammogram, colonoscopy, Pap smear, PSA)
- Bone density (DEXA) for at-risk groups
- Eye & dental exams
- Vaccination boosters (flu, shingles, Tdap)

## 📅 Smart Scheduling:
- Based on:
  - Age & gender
  - Medical history (e.g., family cancer → earlier colonoscopy)
  - Chronic conditions (e.g., diabetes → annual eye exam)
  - Last screening date
- Follows guidelines (USPSTF, CDC, WHO)

## 🔔 Notification System:
- 3 months before: “Time to schedule your annual blood work”
- 1 month before: “Your doctor recommends a mammogram this year”
- After due date: “You’re overdue for a colonoscopy — book now?”

## 🔄 Dependencies:
- Medical history (feature-017)
- Vaccination tracker (feature-026)
- Appointment system (feature-007)
- Hospital/clinic integration (feature-077)
- AI health engine (feature-057)

## 📱 UX Note:
- “Screening Checklist” in dashboard
- One-tap: “Schedule with my doctor” or “Find a lab”
- Export list for annual physical visit
