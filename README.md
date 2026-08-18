# AgriAssist Nigeria 🌾
# AgriAssist Nigeria - All States 🇳🇬

**Live App**: https://agriassist-nigeria.onrender.com

A DevOps capstone project for 3MTT NextGen. Helping farmers across all 36 States + FCT with weather data and crop calendar advice.

## 🚀 Features
- **Weather by State**: Real-time weather for all 36 States + FCT using OpenWeather API
- **Crop Calendar Advisor**: Planting and harvest advice for 20+ Nigerian crops
- **Mobile Responsive**: Works perfectly on phone and desktop

## 🛠️ Tech Stack & DevOps
- **Frontend**: HTML5, CSS3, JavaScript
- **Containerization**: Docker, Nginx
- **CI/CD**: GitHub Actions - Auto build and push to Docker Hub
- **Cloud Hosting**: Render.com
- **Version Control**: Git & GitHub

## ⚡ How to Run Locally
```bash
docker build -t agriassist-nigeria .
docker run -p 8080:80 agriassist-nigeria
