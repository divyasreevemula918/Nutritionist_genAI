# 🥗 Nutritionist GenAI

An AI-powered Nutritionist application built using **Google Gemini**, **Streamlit**, and **Python**. The application analyzes food images and provides nutritional insights, helping users make informed dietary decisions.

## 🚀 Features

* 📷 Upload an image of a meal.
* 🤖 AI-powered food analysis using Google Gemini.
* 🍽️ Identifies food items present in the image.
* 📊 Provides estimated calories and nutritional information.
* 💡 Generates healthy dietary suggestions and recommendations.
* 🖥️ Simple and interactive Streamlit interface.

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Google Gemini Pro Vision
* Google Generative AI SDK
* Pillow (PIL)
* dotenv

---

## 📂 Project Structure

```
Nutritionist_genAI/
│── app.py
│── requirements.txt
│── .env
│── README.md
│── assets/
└── images/
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/divyasreevemula918/Nutritionist_genAI.git
cd Nutritionist_genAI
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / Mac**

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Key

Create a `.env` file and add:

```env
GOOGLE_API_KEY=YOUR_API_KEY
```

### 5. Run the application

```bash
streamlit run app.py
```

---

## 📖 How It Works

1. Upload a food image.
2. The image is sent to the Gemini Vision model.
3. The AI identifies food items.
4. Nutritional information and calorie estimates are generated.
5. The application provides dietary suggestions and health recommendations.

---

## 💡 Future Enhancements

* Meal planning
* Personalized diet recommendations
* Daily calorie tracking
* Nutritional dashboard
* PDF report generation
* Multi-language support

---

## 👩‍💻 Author

**Divya Sree**

Aspiring AI Engineer passionate about Generative AI, LLMs, RAG applications, and intelligent AI solutions.

GitHub: https://github.com/divyasreevemula918
