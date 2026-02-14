# 🧠 AI-Powered English Grammar Exam Preparation Tool

This is an AI-powered tool designed for English grammar exam preparation (IELTS, TOEFL, etc.). Built with Django, Bootstrap, and OpenAI GPT-3, it helps learners improve grammar, vocabulary, and comprehension through interactive exercises and NLP-driven feedback.

## 🚀 Features
- ✅ **Grammar Check** – AI-powered correction.
- ✅ **Fill in the Blanks** – Smart sentence completion.
- ✅ **Synonyms & Antonyms** – Vocabulary enhancement.
- ✅ **Comprehension** – AI-assisted passage understanding.
- ✅ **Speech Change** – Active/passive conversion.
- ✅ **Summary Generator** – Passage summarization.

## 🛠 Tech Stack
- **Backend**: Django, MySQL
- **Frontend**: Bootstrap, JavaScript
- **AI**: OpenAI GPT-3

## 🚀 Getting Started

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd <project-folder>
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Database & API Key**
   ```bash
   python manage.py migrate
   echo "OPENAI_API_KEY=your-api-key-here" > .env
   ```

4. **Run Server**
   ```bash
   python manage.py runserver
   ```
   Access the application at `http://127.0.0.1:8000/`.

