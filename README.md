# AI-Enhanced Health & Wellness Application

## 📌 Project Overview

The **AI-Enhanced Health & Wellness Application** is designed to transform personal health management by integrating **meal planning, dietary tracking, and fitness recommendations** into a single AI-powered platform. The application leverages **OpenAI API, Google Cloud Platform (GCP), and Streamlit** to provide **personalized meal and fitness plans** based on user preferences, health goals, and dietary restrictions.

This project was developed as part of **BCIS 5140 - AI in Business**, under the guidance of **Dr. Anna Sidorova** at the **G. Brint Ryan College of Business, UNT**.

## 🎯 Objectives

- Provide users with **AI-powered meal and fitness recommendations**.  
- Enhance **health management through personalized weekly plans**.  
- Utilize **machine learning and natural language processing (NLP)** to improve health and fitness engagement.  
- Deploy the application on **Google Cloud** for scalability and accessibility.  

---

## 🚀 Key Features
![image](https://github.com/user-attachments/assets/0413a8f8-aa6d-4419-9dfa-6450f2279719)


### 🍽️ **Personalized Meal Plans**
- AI-driven **meal recommendations** based on dietary preferences (vegetarian/non-vegetarian, high protein, low carb).  
- Calorie-aware **meal planning** aligned with BMI, age, and user goals.  
- **Dynamic cooking suggestions** for healthier meal preparation.  

### 🏋️ **Fitness Activity Recommendations**
- Tailored **workout suggestions** categorized by intensity (light, moderate, vigorous).  
- AI-powered **caloric burn estimation** based on weight and activity.  
- **GPT-generated exercise descriptions** for motivation and understanding.  

### 📅 **AI-Powered Weekly Planner**
- Automatically generates a **7-day meal and fitness plan**.  
- Ensures variety in daily meal and workout recommendations.  
- Uses **GPT-generated recipes and fitness instructions** for better user engagement.  

### 💡 **User-Friendly Interface**
- **Built using Streamlit** for an interactive experience.  
- Easy-to-use options for exclusions, meal preferences, and calorie goals.  
- **Real-time BMI calculations** for better personalization.  

### ☁️ **Cloud-Based Deployment**
- Utilizes **Google Cloud Storage and Vertex AI** for data processing.  
- Serverless hosting with **Google Cloud Run**.  
- **Docker containerization** for easy deployment.  

---

## 🛠️ Technology Stack

- **Backend**: Python, OpenAI API, Pandas  
- **Frontend**: Streamlit  
- **Cloud Services**: Google Cloud Platform (Vertex AI, Cloud Storage, Cloud Run)  
- **Machine Learning**: NLP, Collaborative Filtering  
- **Database**: Google Cloud Storage  
- **Deployment**: Docker, Google Cloud Run  

---

## 📊 Data Sources & Preparation

### 🥗 **Nutrition Dataset**
- Contains detailed nutritional information about food items.  
- Features include **calories, fat, protein, carbohydrates, sugar, and dietary fiber**.  
- Used **data cleaning techniques** to classify vegetarian vs. non-vegetarian items.  

### 🏃 **Fitness Dataset**
- Contains **various physical activities and calorie burn estimates**.  
- Categorized into **indoor and outdoor** exercises.  
- Integrated **caloric expenditure rates** based on user weight and activity duration.  

### 🔄 **Data Processing**
- **Cleaning & Feature Engineering**:
  - Removed **irrelevant columns and missing values**.  
  - Standardized **calorie calculations and activity classifications**.  
- **Google Cloud Storage** used for **data access and scalability**.  

---

## 🔧 Implementation Process

### **1️⃣ Cloud Storage**
- Uploaded fitness and nutrition datasets to **Google Cloud Storage**.  
- Stored pre-processed data for **real-time AI model access**.  

### **2️⃣ AI Model Processing**
- Utilized **OpenAI GPT API** for meal and fitness recommendations.  
- **Collaborative filtering and NLP techniques** to improve personalization.  

### **3️⃣ Streamlit Web Application**
- Created an interactive web UI using **Streamlit**.  
- **Real-time user inputs** for calorie tracking and fitness suggestions.  

### **4️⃣ Deployment on Google Cloud**
- Packaged the application using **Docker**.  
- Deployed to **Google Cloud Run** for **serverless, scalable hosting**.  
- Ensured **authentication and secure API calls** for OpenAI integration.  

---
![image](https://github.com/user-attachments/assets/d3ccda8a-0495-48c4-901c-76160d62bcd8)
![image](https://github.com/user-attachments/assets/f6e5f2da-8e39-421b-87ef-5a8530e42a2e)
![image](https://github.com/user-attachments/assets/40b5d2af-60b0-48e7-bcd0-7f5b895c5d95)
![image](https://github.com/user-attachments/assets/ad1f6853-354a-4bc8-8d6f-8014a27f9ff2)
![image](https://github.com/user-attachments/assets/42b2415e-3a76-44fa-9751-c2e9048e6216)








