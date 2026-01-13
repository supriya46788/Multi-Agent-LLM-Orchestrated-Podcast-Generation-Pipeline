# Agentic AI Podcast Generator.

An **end-to-end Agentic AI application** that transforms a single blog or article URL into a **complete podcast episode with downloadable AI-generated voice audio**.

The system accepts a URL, autonomously extracts its content, generates a podcast-style narrative, and produces realistic spoken audio — all in **one click**.

---

## Features
- Extracts blog content using ```FirecrawlScrapeWebsiteTool```.
- Summarizes blog content using ```Gemini LLM```.
- Converts summaries into speech using ```ElevenLabs```.
- Provides a user-friendly interface via ```Gradio```.

---

## 🛠️ Technology Stack

* **Programming Language:** Python
* **Agent Orchestration:** CrewAI
* **Large Language Model:** Google Gemini
* **Web Crawling / Scraping:** Firecrawl
* **Text-to-Speech:** ElevenLabs
* **Frontend UI:** Gradio

---

## 🔐 Environment Variables:

Create a `.env` file in the project root and add the following keys:

```
GOOGLE_API_KEY=your_gemini_api_key
FIRECRAWL_API_KEY=your_firecrawl_api_key
ELEVENLABS_API_KEY=your_elevenlabs_api_key
```

---

## ⚙️ How to Run the Project

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Start the application:

```
python app.py
```

3. Open the local Gradio URL shown in the terminal
4. Paste a blog/article URL
5. Click **Generate Podcast**
6. Listen to or download the generated audio












