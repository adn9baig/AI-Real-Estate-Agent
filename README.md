📄 AI Real Estate Agent
🚀 AI Real Estate Agent is an intelligent real estate assistant powered by Firecrawl's Extract API, Agno, OpenAI GPT-4o, and Streamlit. It helps users find, analyze, and interact with real estate listings efficiently.

📌 Features
✅ Extracts real estate data using Firecrawl's Extract API
✅ Provides intelligent property insights via OpenAI GPT-4o
✅ User-friendly Streamlit interface for seamless interaction
✅ Supports natural language queries for property searches
✅ Fetches and processes property images & metadata

🛠️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/adn9baig/AI-Real-Estate-Agent.git
cd AI-Real-Estate-Agent
2️⃣ Create a Virtual Environment (Optional)
python -m venv venv
source venv/bin/activate   # For macOS/Linux
venv\Scripts\activate      # For Windows
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Set Up API Keys
Create a .env file and add:
FIRECRAWL_API_KEY=your_firecrawl_api_key
AGNO_API_KEY=your_agno_api_key
OPENAI_API_KEY=your_openai_api_key
5️⃣ Run the Application
streamlit run app.py

!(https://github.com/user-attachments/assets/35c4d3a5-8223-4cc5-8500-a8ad31c25383)


📝 Usage
Enter a property address or keyword.
The AI extracts relevant listings and details.
Ask AI-powered questions about the property.
Get insights, comparisons, and recommendations.
📌 Tech Stack
Frontend: Streamlit, HTML, CSS
Backend: Python, FastAPI (if used)
APIs: Firecrawl Extract API, Agno, OpenAI GPT-4o
🤝 Contributing
Want to improve this project?

Fork the repository
Create a new branch: git checkout -b feature-branch
Commit changes: git commit -m "Your changes"
Push to the branch: git push origin feature-branch
Open a Pull Request
