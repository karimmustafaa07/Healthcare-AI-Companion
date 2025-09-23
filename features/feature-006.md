# Feature 006: Medication Reminder System

## 🧑‍💻 Category:
- Patient-Centered

## 📝 Description:
Sends intelligent, customizable reminders to patients to take their medications on time.

Features:
- Add medication name, dosage, frequency (e.g., “2x daily”, “every 8h”)
- Set specific times or flexible windows (“morning”, “after lunch”)
- Snooze option (10 min / 30 min)
- Mark as “Taken” / “Skipped” / “Taken Late”

## 🔔 Notification Channels:
- Push notification (mobile app)
- SMS fallback (if app not opened)
- Email summary (daily/weekly)
- Voice assistant alert (see feature-111)

## 🔄 Dependencies:
- User profile (feature-001)
- Medication history database (feature-018)
- Notification system
- Voice assistant module (future feature-111)
- Drug interaction checker (feature-040)

## 📱 UX Note:
- “Medication Calendar” view
- Color-coded: Green = taken, Red = missed, Gray = upcoming
- AI Tip: “You often miss your evening dose — try setting alarm after dinner.”
