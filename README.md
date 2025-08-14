# 🎤 PPT-Generator-AI-Agent-with-LLMs
🔧 Project Overview:
Technologies Used: Python, Google Gemini AI, python-pptx, Pillow, and more!
Features: AI-powered content generation, professional slide layouts, error handling, and easy customization.
Interactive Notebook: Follow along with the Jupyter notebook for hands-on learning.

This project generates **AI-powered PowerPoint presentations** using:
- **Gemini API** → for creating slide text content
- **Pexels API** → for fetching free high-quality images
- **Python-pptx** → for building `.pptx` presentations

It allows you to give a topic (e.g., *AI Agents*), and the system automatically generates slides with text + images.

---

## 🚀 Features
- 📖 **Automated Slide Content** – Text generated using Google's Gemini models.
- 🖼 **Image Integration** – Pulls relevant stock images from Pexels API.
- 📊 **PPTX File Export** – Creates a ready-to-use PowerPoint presentation.
- 🔐 **Environment Variables** – Keeps API keys safe via `.env` file.
- 📝 **Customizable** – Change topics, number of slides, or styling.

---

## 🛠 Tech Stack
- **Python 3.9+**
- [Google Gemini API](https://ai.google.dev/)
- [Pexels API](https://www.pexels.com/api/)
- [python-pptx](https://python-pptx.readthedocs.io/)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

---

## 📦 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/pptgenerator-ai-agent.git
cd pptgenerator-ai-agent

2️⃣ Create Virtual Environment (Recommended)
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Configure Environment Variables

Copy .env.example into a new .env file:

cp .env.example .env


Open .env and add your keys:

GEMINI_API_KEY=your_real_gemini_key_here
PEXELS_API_KEY=your_real_pexels_key_here

5️⃣ Run the Notebook
jupyter notebook pptgenerator_AI_Agent_.ipynb
