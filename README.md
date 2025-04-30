# 🧳 Travel Agent AI — Google GenAI Capstone Project (2025)

An India-focused Travel Planner AI built using **Gemini 2.0 Flash API**, **Google Search Grounding**, and **Retrieval-Augmented Generation (RAG)** via **ChromaDB**. It uses few-shot prompting and chain-of-thought reasoning to generate personalized travel plans, answer trip-related questions, and recommend food, sights, and transport tips.

---

## 📌 Project Metadata

- **Project Title**: Travel Agent AI with Google GenAI  
- **Submitted by**: Pervaz Md Shoriful Hussain  
- **Date**: April 19, 2025  
- **Platform**: Kaggle  
- **Tech Stack**: Gemini 2.0 Flash, Google Search, ChromaDB, Python, LangChain

---

## ✨ Features

- 🧠 Few-shot + Chain-of-Thought Prompting for multi-day travel plans  
- 🔍 Google Search Tool for real-time grounding  
- 📚 ChromaDB for custom RAG-based knowledge (e.g., India travel guide)  
- 🤖 Interactive AI assistant for answering travel queries  
- 📅 Plans include day-wise itineraries, cost estimates, food tips, and local advice  
- 🇮🇳 Optimized for travel within India (Jaipur, Delhi, Varanasi, etc.)

---

## 🚀 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/travel-agent-ai.git
cd travel-agent-ai
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Set Up Gemini API
Get Your API Key
Visit Google AI Studio

Copy your API key

In Notebooks:
python
Copy
Edit
import os
os.environ['GEMINI_API_KEY'] = 'your-api-key-here'
OR Using a .env File:
Create a file called .env:

ini
Copy
Edit
GEMINI_API_KEY=your-api-key-here
Then load it in your code:

python
Copy
Edit
from dotenv import load_dotenv
load_dotenv()
📂 Project Structure
bash
Copy
Edit
travel-agent-ai/
├── Travel_Agent_AI.ipynb         # Kaggle/Colab notebook
├── requirements.txt              # Python dependencies
├── README.md                     # This documentation
├── .env (optional, local only)   # Environment variables
└── /docs or /assets (optional)   # Resume, screenshots, etc.
🧠 How It Works
Few-shot + CoT Prompt Example
css
Copy
Edit
You are an Indian travel agent AI...
Plan a 3-day solo cultural trip to Jaipur in February (budget)
...
Gemini Response Sample
Day-wise itinerary (Morning, Afternoon, Evening)

Local food (e.g., Pyaz Kachori, Dal Baati Churma)

Cost breakdown (in INR)

Safety, transport, and cultural tips

RAG Example (with ChromaDB)
Guide chunks: Food, Sightseeing, Transport, Safety

User query: "What are good local foods to try in Delhi?"

Gemini answers based on retrieved guide data

Google Search Grounding
Adds live, real-time search-based results to Gemini answers

Tool: google.genai.types.GoogleSearch

🔗 Run the Notebook on Kaggle
👉 Open in Kaggle

Supports full execution in Kaggle’s free cloud environment


📄 License
MIT License – Free to use and modify for educational or non-commercial use.

🌐 Acknowledgments
Google GenAI Studio

Kaggle Notebooks

ChromaDB

💡 This project can also be bundled as a downloadable zip or deployed to GitHub directly from Colab/Kaggle using GitHub CLI.
