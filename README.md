# Ai-nutrition_assistant

An AI-powered nutrition assistant that helps users analyze meals, extract nutrition from images or voice, and get personalized meal plans.

## 🌟 Features

- ✅ Input via **text**, **voice**, or **image** (e.g., food photos or labels)
- ✅ Uses **Groq (LLaMA3)** for nutrition analysis
- ✅ Personalized meal plans based on:
  - Fitness goals
  - Medical conditions
  - Dietary preferences
- ✅ Explains **why certain foods are better**
- ✅ Learns from your feedback and improves recommendations

## 📦 Tech Stack

- **Python**, **Flask**
- **Groq API** (LLaMA3)
- **Tesseract OCR** (for reading images)
- **JavaScript** (for voice input)
- **HTML/CSS**

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-nutrition-assistant.git
   cd ai-nutrition-assistant
2. Install dependencies:
     pip install -r requirements.txt
3. Add a .env file:
     GROQ_API_KEY=your_groq_api_key_here
4.Run the app:
    python app.py
