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
```
2. Install Dependencies
```bash
pip install -r requirements.txt
```
3. Set Up Gemini API
Get Your API Key
Visit Google AI Studio

Copy your API key

In Notebooks:
```bash
import os
os.environ['GEMINI_API_KEY'] = 'your-api-key-here'
```


## ⚙️ How It Works
```bash
1. User enters a travel query (destination, duration, budget)
2. Gemini processes the query using few-shot + chain-of-thought prompting
3. Relevant travel data is retrieved from ChromaDB (RAG)
4. Google Search adds real-time insights
5. Final response is generated with:
   - Day-wise itinerary
   - Cost estimation
   - Food & cultural tips
   - Travel advice
```
## 📸 Example
```bash
**Input:**
Plan a 3-day budget trip to Jaipur

**Output:**
- Day 1: City Palace, Hawa Mahal, Local Market
- Day 2: Amer Fort, Nahargarh Fort
- Day 3: Shopping & cultural spots
- Food: Dal Baati Churma, Pyaz Kachori
- Estimated Budget: ₹8,000–₹12,000
```
RAG Example (with ChromaDB)
Guide chunks: Food, Sightseeing, Transport, Safety

User query: "What are good local foods to try in Delhi?"

Gemini answers based on retrieved guide data

Google Search Grounding
Adds live, real-time search-based results to Gemini answers

Tool: google.genai.types.GoogleSearch

🔗 Run the Notebook on Kaggle
👉 Open in Kaggle https://www.kaggle.com/code/pervazhussain/travel-agent-ai

Supports full execution in Kaggle’s free cloud environment


📄 License
MIT License – Free to use and modify for educational or non-commercial use.

🌐 Acknowledgments
Google AI Studio

Kaggle Notebooks

ChromaDB

💡 This project can also be bundled as a downloadable zip or deployed to GitHub directly from Kaggle using GitHub CLI.
