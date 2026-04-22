📊 CSV AI Agent (Groq + LangChain + Streamlit)
🚀 AI-powered Streamlit app to chat with and visualize CSV data in real time.
✨ Features
💬 Chat with your CSV data using natural language
📊 Generate smart visualizations (bar charts, histograms, etc.)
⚡ Powered by Groq LLM (Llama 3.3 70B)
🧠 Built using LangChain CSV Agent
🎨 Interactive UI with Streamlit
🔍 Instant insights without writing code
🖥️ Demo
📂 Project Structure
├── app.py              # Main Streamlit application
├── requirements.txt    # Dependencies
└── README.md           # Project documentation
⚙️ Installation
1. Clone the repository
git clone https://github.com/your-username/csv-ai-agent-streamlit.git
cd csv-ai-agent-streamlit
2. Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
3. Install dependencies
pip install -r requirements.txt
🔑 Setup
Get your Groq API Key from:
👉 https://console.groq.com/
▶️ Run the App
streamlit run app.py
🧠 How It Works
Upload a CSV file 📁
Ask questions about your data 💬
Generate visualizations 📊
Get instant AI-powered insights ⚡
📸 Example Prompts
"What is the average sales?"
"Show top 10 categories"
"Plot a histogram of age"
"Which column has highest correlation?"
🛠️ Tech Stack
Streamlit – UI framework
LangChain – AI agent orchestration
Groq (Llama 3.3 70B) – LLM backend
Pandas – Data processing
Matplotlib & Seaborn – Visualization
⚠️ Notes
Make sure your CSV is clean and properly formatted
Large files may take longer to process
API key is required for AI responses
🤝 Contributing
Pull requests are welcome! Feel free to open issues or suggest improvements.
📜 License
MIT License
