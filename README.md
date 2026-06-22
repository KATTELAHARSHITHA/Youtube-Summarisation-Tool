# Youtube-Summarisation-Tool

# 🎥 YouTube Video Summarizer using LangChain

An AI-powered web application that extracts transcripts from YouTube videos and generates structured summaries, detailed articles, key points, and interview-style Q&A using **LangChain**, **Google Gemini**, and **Streamlit**.

---

## 📌 Features

- 📹 Extract transcripts from YouTube videos
- 🤖 AI-powered summarization using Google Gemini
- 📝 Generate concise summaries
- 📄 Create detailed article-style notes
- 🔑 Extract important key points
- ❓ Generate Question & Answer pairs
- ⏱️ Display timestamp-based navigation
- 🎨 User-friendly Streamlit interface

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Google Gemini API
- YouTube Transcript API
- LangChain Community
- Recursive Character Text Splitter

---

## 📂 Project Structure

```
Youtube_Summarization_LangChain/
│
├── app.py                     # Main Streamlit application
├── requirements.txt           # Required Python packages
├── .env.example               # Environment variable template
├── Summarizer_SK.ipynb        # Development notebook
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd Youtube_Summarization_LangChain
```

### 2. Create a Virtual Environment (Optional)

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Configure API Key

Create a `.env` file in the project directory.

```
GOOGLE_API_KEY=your_google_api_key
```

Or enter the API key directly from the Streamlit sidebar.

You can obtain a Google Gemini API key from **Google AI Studio**.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser at:

```
http://localhost:8501
```

---

## 🚀 How It Works

1. Enter your Google Gemini API Key.
2. Paste a YouTube video URL.
3. Click **Analyze Video**.
4. The application:
   - Extracts the transcript
   - Splits long text into chunks
   - Sends the content to Gemini through LangChain
   - Generates:
     - Executive Summary
     - Detailed Article
     - Key Points
     - Question & Answers
     - Timestamp Navigation

---

## 📸 Output

The application generates:

- ✅ Executive Summary
- ✅ Detailed Article
- ✅ Key Takeaways
- ✅ Interview-style Questions & Answers
- ✅ Timestamp Navigation

---

## 📦 Dependencies

- streamlit
- langchain
- langchain-google-genai
- langchain-community
- langchain-text-splitters
- youtube-transcript-api
- pytube
- python-dotenv
- requests
- beautifulsoup4
- google-generativeai

Install them using:

```bash
pip install -r requirements.txt
```

---

## 💡 Use Cases

- Summarize educational videos
- Create study notes
- Generate blog content
- Review technical tutorials
- Prepare interview questions
- Research and documentation

---

## 🛡️ Error Handling

The application handles:

- Invalid YouTube URLs
- Videos without subtitles
- API authentication errors
- Long transcript chunking
- Processing failures

---

## 🔮 Future Enhancements

- Support multiple LLM providers
- Export summaries as PDF
- Download Word documents
- Multilingual summarization
- Chat with YouTube videos (RAG)
- Voice-based interaction

## 📜 License

This project is developed for educational and learning purposes.
