# Feature 026: Vaccination Tracker

## 🧑‍💻 Category:
- Patient-Centered

## 📝 Description:
Maintains a complete, up-to-date record of all vaccines the patient has received, with smart reminders for upcoming or overdue doses.

## 💉 Tracked Vaccines Include:
- Routine (MMR, DTaP, Polio, Hepatitis B)
- Annual (Flu)
- Age-based (Shingles, Pneumococcal)
- Travel-related (Typhoid, Yellow Fever)
- Condition-specific (e.g., extra flu shots for diabetics)

## 📅 Smart Features:
- **Auto-schedule** based on CDC/WHO guidelines + patient age/health
- **Reminder**: “Flu shot due in October” or “You’re overdue for Tdap booster”
- **Travel mode**: Suggest vaccines based on destination (if enabled)
- **Pediatric tracking**: For parents managing child’s immunization

## 📥 Input Methods:
- Manual entry (date, vaccine name, lot number, clinic)
- Scan vaccination card (future CV — feature-117)
- Import from public health records or clinic EHR (feature-077)

## 🔄 Dependencies:
- Medical history (feature-017)
- Age/gender profile (feature-001)
- Travel data (optional)
- Appointment system (feature-007)
- Routine screening reminders (feature-021)

## 📱 UX Note:
- Color-coded status: ✅ Complete | ⏳ Due Soon | ❌ Overdue
- “Vaccination Certificate” export (PDF, QR code — see feature-118)
- Share with school, employer, or travel agency (with consent)
