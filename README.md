# 📊 CSV AI Agent (Groq + LangChain + Streamlit)

> 🚀 Chat with your CSV data and generate visualizations using AI — in real time.

## ✨ Features

* 💬 Ask questions about your CSV using natural language
* 📊 Generate charts automatically (bar, line, histogram, etc.)
* ⚡ Powered by Groq (Llama 3.3 70B)
* 🧠 Built with LangChain Pandas DataFrame Agent
* 🎨 Interactive UI using Streamlit
* 🔍 Instant insights without coding

---
## LIVE DEMO
<img width="1872" height="841" alt="Screenshot 2026-04-22 at 14 53 24" src="https://github.com/user-attachments/assets/8394cfdf-2e5a-466d-8957-cce1ca416d28" />

## 📂 Project Structure

```
csv-ai-agent-streamlit/
│── app.py
│── requirements.txt
│── demo.gif
│── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/csv-ai-agent-streamlit.git
cd csv-ai-agent-streamlit
```

---

### 2. Create virtual environment

#### Mac / Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Create `requirements.txt` (if not present)

```
streamlit
pandas
matplotlib
seaborn
langchain
langchain-experimental
langchain-groq
```

---

## 🔑 Get API Key

Get your Groq API key here:
https://console.groq.com/

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## 🧠 How to Use

1. Enter your Groq API key in the sidebar
2. Upload your CSV file
3. Ask questions like:

   * "What is the average sales?"
   * "Show top 5 categories"
4. Generate charts:

   * "Create a bar chart of revenue by region"

## 🛠️ Tech Stack

* Streamlit
* LangChain
* Groq (Llama 3.3 70B)
* Pandas
* Matplotlib
* Seaborn

---

## ⚠️ Notes

* Requires Groq API key
* Works best with clean CSV files
* Large datasets may take time

---

## 🤝 Contributing

Pull requests are welcome. Feel free to improve features or UI.

---

## 📜 License

MIT License

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

