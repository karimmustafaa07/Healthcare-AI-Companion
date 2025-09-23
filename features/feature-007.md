# Feature 007: Appointment Reminder System

## 🧑‍💻 Category:
- Patient-Centered

## 📝 Description:
Automatically reminds patients of upcoming medical appointments (doctor visits, lab tests, scans, etc.).

Features:
- Add appointment: date, time, doctor, location, purpose
- Sync with hospital/clinic calendars (see feature-077)
- Recurring appointments (e.g., “Every 3 months for checkup”)

## 🔔 Reminder Schedule:
- 1 week before → gentle notification
- 1 day before → push + SMS
- 1 hour before → push + optional voice call (see feature-111)
- If missed → “Did you miss your appointment? Reschedule now.”

## 🔄 Dependencies:
- User profile (feature-001)
- Hospital integration API (feature-077)
- Notification system
- Voice assistant (future feature-111)
- Calendar sync (Google Calendar, Apple Calendar — optional)

## 📱 UX Note:
- “Upcoming Appointments” widget on home dashboard
- One-tap reschedule or cancel (if clinic allows)
- AI Suggestion: “Dr. Smith usually runs 15 min late — arrive at 3:15 PM instead of 3:00 PM.”
