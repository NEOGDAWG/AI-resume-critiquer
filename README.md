# 📑 AI Resume Critiquer

An interactive Streamlit web app that analyzes resumes with the power of OpenAI’s GPT models.  
Upload your resume (PDF or TXT), specify a target job role, and receive structured, AI-driven feedback to improve clarity, skills presentation, and job alignment.

---

## 🚀 Features
- Upload resumes in **PDF** or **TXT** format
- Extracts text using [pypdf](https://pypi.org/project/pypdf/)
- Generates **constructive, tailored feedback** powered by OpenAI
- Optional input for the **job role** you’re targeting
- User-friendly **Streamlit interface**

---

## 🛠️ Tech Stack
- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/) – frontend for the app
- [pypdf](https://pypi.org/project/pypdf/) – PDF parsing
- [python-dotenv](https://pypi.org/project/python-dotenv/) – environment variable management
- [OpenAI Python SDK](https://pypi.org/project/openai/) – GPT-powered analysis

---

## 📦 Installation

Clone the repo:
```bash
git clone https://github.com/NEOGDAWG/AI-resume-critiquer.git
cd AI-resume-critiquer

Create a virtual environment (optional but recommended):
python -m venv .venv
source .venv/bin/activate   # Mac/Linux
.venv\Scripts\activate      # Windows

Install dependencies:
pip install -r requirements.txt

Or if using uv:
uv sync

🔑 Setup
Create a .env file in the root of the project:

OPENAI_API_KEY=your_openai_api_key_here


Never commit your .env file (it’s already in .gitignore).

▶️ Usage

Run the app locally:

streamlit run main.py


Then open the URL printed in your terminal (usually http://localhost:8501).