# Feature 028: Physical Activity Tracking (Steps, Running, etc.)

## 🧑‍💻 Category:
- Patient-Centered

## 📝 Description:
Automatically tracks daily physical activity using device sensors or connected wearables, including:

- Steps walked
- Distance traveled (km/miles)
- Active minutes
- Floors climbed (if supported)
- Running, cycling, swimming (via workout modes)

## 📱 Data Sources:
- Built-in phone sensors (accelerometer, GPS)
- Sync with wearables: Apple Watch, Fitbit, Garmin (features 073–074)
- Manual entry (for non-connected devices)

## 📊 Visualization & Goals:
- Daily progress toward step goal (e.g., 8,000 steps)
- Weekly trends: “You walked 20% more this week!”
- Activity heat map by hour/day
- “Move Reminder”: “You’ve been sitting for 2 hours — take a walk!”

## 🤖 AI Insights:
- Correlates with health metrics:  
  “On high-activity days, your blood sugar is 15% lower.”  
  “Low steps + poor sleep → higher fatigue (see feature-019)”
- Adjusts goals based on recovery (e.g., post-surgery — feature-049)

## 🔄 Dependencies:
- Device integrations (features 071–074)
- Sleep tracking (feature-003)
- Blood sugar (feature-005)
- Mood tracking (feature-019)
- Post-surgery recovery (feature-049)

## 📱 UX Note:
- Dashboard widget (feature-010)
- Achievement badges (feature-082)
- Share weekly summary with doctor or coach
