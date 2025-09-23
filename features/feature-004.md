# Feature 004: Blood Pressure Monitoring

## 🧑‍💻 Category:
- Patient-Centered

## 📝 Description:
Enables patients to log and monitor their blood pressure readings:
- Systolic (top number)
- Diastolic (bottom number)
- Heart rate (optional, if device provides)

Readings can be:
- Manually entered
- Automatically synced via Bluetooth BP monitors (see feature-075)

## 📊 Visualization & Alerts:
- Color-coded readings:
  - Green: Normal (<120/80)
  - Yellow: Elevated (120-139/80-89)
  - Red: Hypertension (≥140/90)
- Trend graph over days/weeks
- AI Alert: “3 consecutive high readings — consult your doctor.”

## 🔄 Dependencies:
- User profile (feature-001)
- Health metrics database
- Device integration (feature-075 — BP monitors)
- Notification system
- Emergency escalation (feature-027 — SOS)

## 📱 UX Note:
- One-tap quick log
- “Add Note” option: “Felt dizzy after reading.”
- Weekly BP report auto-generated
