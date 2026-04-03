# 🎤 AI Meeting Minutes Generator

### 👨‍💻 Developed by *Your Name*

An AI-powered application that converts meeting audio into structured, professional meeting minutes including summaries, key points, decisions, and action items.

---

## 🚀 Features

* 🎧 **Speech-to-Text** using Whisper
* 🧠 **AI Summarization** using LLM (LLaMA / Hugging Face models)
* 📝 **Structured Meeting Minutes**

  * Summary
  * Key Discussion Points
  * Decisions
  * Action Items
  * Timeline
  * Sentiment
* 📥 **Download as PDF**
* 🎙️ Supports **audio upload or recording**
* ⚡ Built with an interactive **Gradio UI**

---

## 🧩 Tech Stack

* Python
* Transformers (Hugging Face)
* Whisper (Speech Recognition)
* LLaMA / LLM
* Gradio (UI)
* ReportLab (PDF generation)

---

## 📂 Project Structure

```
├── meeting_minutes.py     # Main application
├── meeting_minutes.pdf    # Generated output
```

---


## 🔑 Setup

Set your Hugging Face token:

```python
from huggingface_hub import login
login("your_token_here")
```

---

## ▶️ Run the App

```bash
meeting_minutes.py
```

Then open the local Gradio link in your browser.

---

## 🖥️ Usage

1. Upload or record meeting audio
2. Click **Generate Minutes**
3. View:

   * Transcript
   * Structured meeting minutes
4. Download the report as **PDF**

---

## 🧠 How It Works

```
Audio Input
   ↓
Whisper (Speech → Text)
   ↓
Timestamp Processing
   ↓
LLM (Summarization + Structuring)
   ↓
Formatted Meeting Minutes
   ↓
PDF Export
```

---

## 🌟 Future Improvements

* 👥 Speaker diarization (who said what)
* 📊 Meeting analytics dashboard
* 🌐 Cloud deployment
* 🗂️ Meeting history storage
* 🧾 DOCX export option

---


---
