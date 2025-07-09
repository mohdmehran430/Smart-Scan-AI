# Smart Scan AI
![Alt Text](https://www.foodscan.app/static/media/hero_image.d37800b08ee2b47461b6.png){: width="100px" height="100px"}
A Flutter application that helps users track their nutritional intake by analyzing food product labels and meals using AI.

## Features
- 📸 Scan product labels and food items using your device's camera
- 🔍 AI-powered nutrition analysis using Google's Gemini API
- 📊 Track daily nutrient intake with detailed breakdowns
- 📅 View historical food consumption data
- 📈 Visual representations of macronutrient distribution
- ⚡ Real-time nutritional insights and recommendations

### Prerequisites
- Flutter SDK (>=3.4.3)
- Dart SDK
- Google Gemini API key

cd Smart Scan AI
```
. Create a .env file in the root directory and add your Gemini API key:
```bash
GEMINI_API_KEY=your_api_key_here
```
. Install dependencies
```bash
flutter pub get
```
. Run the app
```bash
flutter run --no-enable-impeller
```

## Technologies Used
- Flutter SDK (>=3.4.3)
- Dart SDK
- Google Gemini API key
- Flutter & Dart
- Google Generative AI (Gemini)
- SharedPreferences for local storage
- Various Flutter packages:
-   image_picker for camera integration
-   flutter_dotenv for environment variables
-   fl_chart for data visualization
-   rive for animations
-   And more...

## Acknowledgments
- Google Generative AI for the Gemini API
- Flutter team for the amazing framework

