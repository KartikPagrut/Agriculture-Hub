# 🌾 AGRI HUB - End-to-End Agriculture Management Platform

**AI-Powered Crop & Soil Management System**

A comprehensive agricultural platform that leverages artificial intelligence and machine learning to provide smart farming solutions for modern agriculture.

![AGRI HUB](https://img.shields.io/badge/AGRI%20HUB-AI%20Agriculture-green?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-2.0+-red?style=for-the-badge&logo=flask)
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge)
![AI](https://img.shields.io/badge/AI-Google%20Gemini-purple?style=for-the-badge)

## 🚀 Features

### 🌱 **Smart Crop Recommendation**
- **AI-powered crop suggestions** based on soil parameters (N, P, K, pH, rainfall)
- **Weather integration** for real-time temperature and humidity data
- **22 crop types supported** including cereals, pulses, fruits, and cash crops
- **99.55% accuracy** with retrained Random Forest model

### 🧪 **Soil Optimizer (Fertilizer Recommendation)**
- **Intelligent fertilizer suggestions** based on soil nutrient analysis
- **Crop-specific recommendations** for optimal nutrient balance
- **NPK deficiency detection** with actionable solutions
- **22 supported crops** with detailed fertilizer guidance

### 🔬 **Disease Detection AI**
- **Computer vision-based** plant disease identification
- **38 plant diseases** across multiple crop types
- **Deep learning model** for accurate disease classification
- **Treatment recommendations** for identified diseases

### 🌤️ **Weather-Aware Recommendations**
- **7-day weather forecast** with agricultural insights
- **Smart farming advice** based on weather patterns
- **Activity planning** for planting, harvesting, and spraying
- **Risk alerts** for extreme weather conditions

### 📊 **Crop Comparison Dashboard**
- **Profit analysis** and ROI calculations
- **Market trends** and price comparisons
- **Water and labor requirements** analysis
- **Regional suitability** recommendations

### 🤖 **AI Agriculture Assistant**
- **Google Gemini-powered** chatbot for farming queries
- **Floating widget design** for easy access
- **Agriculture-focused responses** with expert advice
- **Real-time assistance** for farming decisions

## 🛠️ Technology Stack

### **Backend**
- **Python 3.8+** - Core programming language
- **Flask 2.0+** - Web framework
- **Scikit-Learn** - Machine learning models
- **PyTorch** - Deep learning for disease detection
- **Pandas & NumPy** - Data processing

### **Frontend**
- **HTML5 & CSS3** - Modern responsive design
- **Bootstrap 5** - UI framework
- **JavaScript** - Interactive features
- **AOS** - Scroll animations

### **AI & ML**
- **Random Forest** - Crop recommendation
- **CNN** - Disease detection
- **Google Gemini API** - AI chatbot
- **OpenWeatherMap API** - Weather data

### **Database**
- **CSV files** - Lightweight data storage
- **Pickle models** - Serialized ML models

## 📁 Project Structure

```
AGRI-HUB/
├── app/
│   ├── models/                 # ML models
│   │   ├── RandomForest.pkl   # Crop recommendation model
│   │   └── plant_disease_model.pth # Disease detection model
│   ├── Data/                  # Datasets
│   │   ├── fertilizer.csv     # Fertilizer recommendations
│   │   └── ...
│   ├── Data-processed/        # Processed datasets
│   │   └── crop_recommendation.csv
│   ├── templates/             # HTML templates
│   │   ├── index.html         # Homepage
│   │   ├── crop.html          # Crop recommendation
│   │   ├── fertilizer.html    # Fertilizer recommendation
│   │   ├── disease.html       # Disease detection
│   │   ├── weather_recommendations.html
│   │   ├── crop_comparison.html
│   │   └── layout.html        # Base template
│   ├── static/                # Static files
│   │   ├── css/              # Stylesheets
│   │   ├── js/               # JavaScript files
│   │   └── images/           # Images
│   ├── utils/                 # Utility functions
│   │   ├── disease.py        # Disease detection utils
│   │   └── fertilizer.py     # Fertilizer recommendations
│   ├── app.py                # Main Flask application
│   ├── config.py             # Configuration settings
│   └── crop_data.py          # Crop comparison data
├── notebooks/                 # Jupyter notebooks
├── requirements.txt          # Python dependencies
└── README.md                # Project documentation
```

## 🚀 Quick Start

### **Prerequisites**
- Python 3.8 or higher
- pip package manager
- Git

### **Installation**

1. **Clone the repository**
```bash
git clone https://github.com/dhanushm18/end-to-end-agriculture-hub.git
cd end-to-end-agriculture-hub
```

2. **Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Configure API keys**
```python
# Edit app/config.py
weather_api_key = "your_openweathermap_api_key"
google_ai_api_key = "your_google_gemini_api_key"
```

5. **Run the application**
```bash
cd app
python app.py
```

6. **Access the application**
Open your browser and navigate to `http://localhost:5000`

## 🔧 Configuration

### **API Keys Required**
- **OpenWeatherMap API**: For weather data
- **Google Gemini API**: For AI chatbot functionality

### **Environment Setup**
The application is optimized for:
- **Development**: Flask development server
- **Production**: WSGI server (Gunicorn recommended)

## 📊 Model Performance

### **Crop Recommendation Model**
- **Algorithm**: Random Forest Classifier
- **Accuracy**: 99.55%
- **Features**: N, P, K, temperature, humidity, pH, rainfall
- **Classes**: 22 crop types

### **Disease Detection Model**
- **Architecture**: Convolutional Neural Network (CNN)
- **Classes**: 38 plant diseases
- **Input**: Plant leaf images
- **Performance**: High accuracy disease classification

## 🌟 Key Highlights

- ✅ **Complete End-to-End Solution** for agriculture management
- ✅ **AI-Powered Recommendations** using state-of-the-art ML models
- ✅ **Modern Responsive Design** suitable for all devices
- ✅ **Real-time Weather Integration** for informed decisions
- ✅ **Intelligent Chatbot** for instant farming assistance
- ✅ **Comprehensive Analytics** with profit and ROI analysis
- ✅ **Production Ready** with proper error handling

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



## 🙏 Acknowledgments

- OpenWeatherMap for weather API
- Google for Gemini AI API
- Scikit-Learn community for ML tools
- Flask community for web framework

---

**Made with ❤️ for sustainable agriculture and smart farming**
