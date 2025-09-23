# Feature 015: Healthy Food Substitutions

## 🧑‍💻 Category:
- Patient-Centered

## 📝 Description:
Suggests healthier alternatives to unhealthy foods the patient logs or scans.

Examples:
- “Instead of white bread → try whole grain (lower glycemic index)”
- “Instead of soda → try sparkling water with lemon”
- “Instead of fried chicken → try baked with herbs”

## 🧠 AI Logic:
- Based on user’s conditions:
  - Diabetes → lower sugar/carbs
  - Hypertension → lower sodium
  - High cholesterol → lower saturated fat
- Considers taste preferences & cultural foods
- Prioritizes accessible, affordable swaps

## 📱 Interaction Methods:
- Manual: “I ate pizza” → AI suggests cauliflower crust version
- Camera scan: Point phone at food package → AI suggests better option (see feature-117)
- Meal planner integration (feature-011): “Swap this meal” button

## 🔄 Dependencies:
- Medical profile (feature-017)
- Meal suggestions (feature-011)
- AI nutrition engine (feature-055)
- Food database with nutritional labels
- OCR/Computer Vision (future feature-117)

## 🌍 Localization Note:
- Respects regional diets (e.g., “Instead of ful medames with oil → try with lemon & olive oil spray”)
- Avoids unrealistic swaps (e.g., won’t suggest quinoa in rural areas)
