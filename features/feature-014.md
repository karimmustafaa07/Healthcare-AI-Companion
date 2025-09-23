# Feature 014: Caffeine Consumption Monitoring

## 🧑‍💻 Category:
- Patient-Centered

## 📝 Description:
Tracks daily caffeine intake from common sources:
- Coffee (espresso, drip, cold brew)
- Tea (black, green, herbal)
- Energy drinks
- Soda (Coke, Pepsi, etc.)
- Chocolate & medications (e.g., Excedrin)

## ☕ User Input:
- Quick-select items with standard caffeine amounts
- Custom entry: “My latte has 150mg caffeine”
- Scan product barcode (future OCR feature)
- Voice log: “I had two cups of coffee this morning”

## 📊 Visualization & Alerts:
- Daily total vs. safe limit (e.g., 400mg for adults)
- Color indicator:
  - Green: <300mg
  - Yellow: 300–400mg
  - Red: >400mg or >200mg (if pregnant/sensitive)
- AI Warning: “High caffeine + anxiety symptoms → consider switching to decaf.”

## 🔄 Dependencies:
- User profile (feature-001)
- Mood tracker (feature-019)
- Symptom logger (feature-025)
- AI health engine (feature-057)
- Daily dashboard (feature-010)

## 📱 UX Note:
- Caffeine “bank” view: “You’ve used 250mg of your 400mg today”
- “Swap Suggestion”: “Try green tea (30mg) instead of energy drink (160mg)”
- Weekly report: “Avg. intake: 320mg — stable”
