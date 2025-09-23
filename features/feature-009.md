# Feature 009: Heart Rate Monitoring

## 🧑‍💻 Category:
- Patient-Centered

## 📝 Description:
Continuously or periodically tracks the patient’s heart rate (beats per minute - BPM) using:

- Wearable devices (Apple Watch, Fitbit, Garmin — see feature-073, 074)
- Manual entry (for users without devices)
- Camera-based pulse detection (future CV feature — research mode)

## 📊 Visualization & Alerts:
- Real-time BPM display
- Resting HR vs Active HR tracking
- Zones:
  - Green: Normal (60–100 BPM)
  - Yellow: Elevated (100–120 BPM) or Low (50–59 BPM)
  - Red: Critical (>120 BPM at rest or <50 BPM with symptoms)

- AI Alert: “Your resting heart rate has increased by 15% this week — possible stress or illness.”

## 🔄 Dependencies:
- User profile (feature-001)
- Health metrics database
- Device integrations (features 073, 074)
- Notification system
- SOS emergency trigger (feature-027 — if extreme + symptoms)

## 📱 UX Note:
- Live graph with zoom (last hour / day / week)
- “Add Note”: “Was anxious during this reading.”
- Weekly HR variability report (indicator of stress/recovery)
