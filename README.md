# 🎯 AI Chatbot with Django

A conversational AI chatbot built using Django, integrated with the OpenAI API for natural language processing, OMDb API for movie data, and JokeAPI for fun jokes. Designed with a simple web interface, this project demonstrates how to blend AI with external APIs in a full-stack Python web app.

---

## 🚀 Features

- 🤖 AI responses powered by OpenAI GPT (text-davinci-003)
- 🎬 Movie information lookup via OMDb API
- 🨂 Fetch random jokes using JokeAPI
- 💬 Chat memory for a more contextual experience
- 🌐 Built with Django for web integration

---

## 💠 Tech Stack

- Python 3.8+
- Django
- OpenAI GPT API
- OMDb API
- JokeAPI
- HTML/CSS (Django Templates)
- JavaScript (optional, for UI interactivity)

---

## 📁 Project Structure

```
chatbot_project/
├── chatbot_app/
│   ├── templates/
│   │   └── chatbot_app/
│   │       └── chatbot.html
│   ├── views.py
│   ├── urls.py
│   └── ...
├── chatbot_project/
│   └── settings.py
├── manage.py
└── requirements.txt
```

---

## 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ai-chatbot-django.git
   cd ai-chatbot-django
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set your API keys**

   Create a `.env` file in the root of your project with the following:

   ```
   OPENAI_API_KEY=your_openai_key
   OMDB_API_KEY=your_omdb_key
   ```

   Or add these to your Django settings directly.

5. **Run database migrations**
   ```bash
   python manage.py migrate
   ```

6. **Run the development server**
   ```bash
   python manage.py runserver
   ```

7. **Visit in browser**
   ```
   http://127.0.0.1:8000/
   ```

---

## 🧪 Example Prompts

- `Tell me a joke`
- `Tell me about the movie Inception`
- `What can you do?`

---

## ✨ Future Features

- User authentication
- Persistent chat history
- Voice recognition (speech-to-text)
- Text-to-speech output
- More API integrations (weather, news, dictionary, etc.)
- 
---
