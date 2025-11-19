# 🏥 Medicine Recommendation System

A intelligent AI-powered medical recommendation system that predicts diseases based on symptoms and provides personalized treatment recommendations using Machine Learning.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Flask](https://img.shields.io/badge/Flask-2.3.3-green)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--learn-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🌟 Features

- **🤖 AI Disease Prediction** - Accurate disease prediction using SVM algorithm
- **💊 Drug Interaction Checker** - Safety feature to check medication interactions
- **🎤 Voice Symptom Input** - Speech recognition for easy symptom entry
- **🔍 Smart Autocomplete** - Intelligent symptom suggestions as you type
- **🌙 Dark/Light Mode** - User-friendly interface with theme switching
- **📱 Responsive Design** - Works perfectly on desktop and mobile devices
- **💡 Comprehensive Recommendations** - Medicines, diets, workouts, and precautions

## 🚀 Live Demo

[![Deployed on Render](https://img.shields.io/badge/Deployed%20on-Render-%2300C7B7)](https://your-app-name.onrender.com)

**Live Application:** [https://your-app-name.onrender.com](https://your-app-name.onrender.com)

## 🛠️ Tech Stack

### Backend
- **Python** - Primary programming language
- **Flask** - Web framework
- **Scikit-learn** - Machine Learning model (SVM)
- **Pandas & NumPy** - Data processing and analysis

### Frontend
- **HTML5** - Page structure
- **CSS3** - Styling with dark/light themes
- **JavaScript** - Interactive features
- **Bootstrap 5** - Responsive UI components

### Machine Learning
- **Support Vector Machine (SVM)** - Prediction algorithm
- **Symptom-based classification** - 133 symptoms → 42 diseases
- **Trained model accuracy**: 95%+ on test data

## 📦 Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Step 1: Clone the Repository
git clone https://github.com/exp0nent/Medicine-Recommendation-System.git
cd Medicine-Recommendation-System

### Step 2: Create Virtual Environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

### Step 3: Install Dependencies
pip install -r requirements.txt

### Step 4: Run the Application
python main.py

### 🎯 Usage
1. Enter Symptoms: Type symptoms like "itching, headache, fever" or use voice input
2. Get Prediction: Click "Predict" for AI-powered disease diagnosis
3. View Results: Explore detailed recommendations including:
   • Predicted disease with description
   • Safety precautions
   • Recommended medications
   • Diet plans
   • Workout routines

### 📊 Dataset
The system uses comprehensive medical datasets:
• 133 unique symptoms
• 42 different diseases
• Symptom severity mapping
• Medication recommendations
• Diet and workout plans

### 🏗️ Project Structure
