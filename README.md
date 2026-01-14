MittiSeva: Sustainable Fertilizer Usage Optimizer for Higher Yield 🌱🚜

Introduction

MittiSeva is an AI-driven system designed to optimize fertilizer usage for higher crop yields while promoting sustainable farming practices. By leveraging real-time soil data, crop-specific nutrient requirements, and environmental conditions, the system provides precise fertilizer recommendations to reduce waste, improve productivity, and minimize environmental impact.

Key Benefits:

✅ Enhanced Crop Productivity – Accurate, data-driven fertilizer recommendations.

✅ Environmental Sustainability – Prevents soil and water pollution.

✅ Cost-Effective Farming – Optimizes input usage, reducing unnecessary expenses.

Features

Real-time, personalized fertilizer recommendations.

Multi-crop support with location-specific guidance.

Integration with weather APIs for dynamic decision-making.

User-friendly mobile interface (Flutter) with local language support.

Historical data tracking and analytics.

AI/ML-based ensemble models (Random Forest + XGBoost) for high accuracy.

PDF report generation for record-keeping and sharing with agricultural experts.

System Architecture

MittiSeva follows a modular and scalable architecture:

Modules:

User Input Module: Crop type, soil nutrients (N, P, K), pH, farm area.

GPS Location Module: Fetches farm coordinates for local environmental data.

Weather Data Module: Real-time weather information via OpenWeatherMap API.

Recommendation Engine: Machine learning models process inputs for fertilizer prediction.

Database Module: Firebase/MySQL stores user data, historical predictions, and logs.

Admin Dashboard: Analytics, user management, and system performance monitoring.

Architecture Layers:

Presentation Layer: Mobile interface (Flutter)

Application Layer: Business logic & ML integration

Data Layer: Database management (Firebase/MySQL)

Integration Layer: API & GPS connectivity

Technology Stack

Frontend: Flutter (Mobile App)

Backend: Flask (Python)

Machine Learning: XGBoost, Random Forest

Database: Firebase Realtime Database / MySQL

APIs: OpenWeatherMap for real-time weather data

Languages: Python 3.8+, Dart (Flutter)

Installation

Clone the repository:

git clone https://github.com/yourusername/MittiSeva.git
cd MittiSeva


Set up Python environment:

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
pip install -r requirements.txt


Configure Firebase / MySQL for database integration.

Set up OpenWeatherMap API key for weather data.

Run Flask backend:

python app.py


Launch Flutter app:

flutter run

Usage

Register/Login in the app.

Enter farm details: soil N, P, K values, pH, crop type, and farm area.

View real-time fertilizer recommendation based on ML predictions.

Generate a downloadable PDF report for record-keeping.

Machine Learning Model

Input Features: N, P, K, soil pH, temperature, humidity/rainfall, soil type, crop type.

Output: Fertilizer type (20+ categories).

Model: XGBoost multi-class classifier + Random Forest ensemble.

Performance:

Accuracy: ~95%

Precision: ~0.94

Recall: ~0.95

F1-score: ~0.94

Feature Importance: Nitrogen, Phosphorus, and Potassium dominate predictions, validating agricultural relevance.

Results

Accurate, real-time fertilizer recommendations.

Reduced fertilizer wastage and input costs.

Enhanced crop productivity and soil health.

User-friendly mobile app interface tested with farmers for usability.

Future Enhancements

Integration with IoT-based soil sensors for automatic nutrient monitoring.

Multi-language support for regional accessibility.

Addition of new crop types and region-specific fertilizer guidelines.

AI-driven predictive analytics for crop yield forecasting.

Contributors

Mali Vrushali Sahebrao – Development & ML Model

Gavali Neha Rama – Frontend & Backend Integration

Surywanshi Unnati Sudhakar – Data Collection & Preprocessing

Patil Chetan Yadnyeshwar – Database & System Architecture

Guide: Prof. Dr. U. M. Patil



<img width="1918" height="942" alt="Screenshot 2025-12-30 132757" src="https://github.com/user-attachments/assets/efd0ec62-4669-4c23-af9e-7f164ae5acfb" />


<img width="1919" height="659" alt="Screenshot 2025-12-30 132825" src="https://github.com/user-attachments/assets/cd34bdeb-6498-4fd0-bff7-c16b144bf700" />

<img width="1919" height="900" alt="Screenshot 2025-12-30 132852" src="https://github.com/user-attachments/assets/1ba66435-292d-4679-a131-4d33634cdf3b" />

<img width="1915" height="930" alt="Screenshot 2025-12-30 133220" src="https://github.com/user-attachments/assets/2fa6df8f-dd1d-4561-9e54-e8d5860f59b6" />

<img width="1910" height="929" alt="Screenshot 2025-12-30 133139" src="https://github.com/user-attachments/assets/ef994b1c-af6c-4c66-a509-2433a4c9633e" />

<img width="1917" height="491" alt="Screenshot 2025-12-30 140318" src="https://github.com/user-attachments/assets/24f3407b-3cb4-4e6c-94ff-0b5ad219d060" />

<img width="1910" height="510" alt="Screenshot 2025-12-30 132928" src="https://github.com/user-attachments/assets/d936f133-a442-450d-a15b-fa0f0209201c" />

<img width="501" height="804" alt="res" src="https://github.com/user-attachments/assets/5c42e6e4-52d2-44c5-9d28-670aa32ee27d" />




