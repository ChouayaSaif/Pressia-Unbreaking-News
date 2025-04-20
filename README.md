# Pressia: Unbreaking News

Pressia is a Django-based **fact-checking platform** designed to empower users and journalists in the fight against misinformation. With a clean user interface, smart AI-powered tools, and robust role-based functionality, Pressia provides a trusted space for verifying facts, creating truth-based content, and securely collaborating in real-time.

---

## 🚀 Features

### 👤 User Roles

- **Normal User**  
  - Submit any type of data (text, links, images, videos) to be fact-checked.

- **Journalist User**  
  - Fact-check any kind of input submitted by users.  
  - Create and publish factual content: articles, images, videos, and more.  
  - Access a smart **AI-powered Notebook** to draft notes.  
  - **Securely share** notes with other verified journalists for collaboration.

---

## 🤖 AI Capabilities

- The AI Notebook assists journalists in drafting accurate notes using natural language generation.
- Designed to boost productivity and help maintain high-quality, fact-based journalism.

---

## 🔐 Secure Collaboration

- Notes shared between journalists are encrypted and access-controlled.
- Designed with confidentiality and professional collaboration in mind.

---

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: Django Templates / (optional JS Framework for interactivity)
- **Database**: PostgreSQL / SQLite (Dev)
- **Authentication**: Django's built-in auth system with custom roles
- **AI Integration**: OpenAI / HuggingFace (optional/custom model)
- **Security**: HTTPS, role-based access, note-sharing permissions

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/ChouayaSaif/Pressia-Unbreaking-News.git
cd Pressia-Unbreaking-News

# Create a virtual environment and activate it
python3 -m venv env
source env/bin/activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run the development server
python manage.py runserver
