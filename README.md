# 🎤 AI Meeting Minutes Generator

An AI-powered application that converts meeting audio into structured meeting minutes using a step-by-step workflow.

---

## 🚀 Features

* 🎧 **Audio to Transcript** (Speech-to-Text using Whisper)
* 📝 **Transcript to Meeting Minutes** (LLM-based summarization)
* 📊 Generates:

  * Summary
  * Key Discussion Points
  * Decisions
  * Action Items
  * Next Steps
* 📥 **Download as PDF**
* 🔄 **Step-by-step UI flow** (easy to use and debug)

---

## 🧩 Workflow

```text
Audio Input
   ↓
Transcription (Whisper)
   ↓
Meeting Minutes Generation (LLM)
   ↓
PDF Export
```

---

## 🖥️ User Flow

1. Upload or record meeting audio 🎤
2. Click **"Transcribe Audio"** → View transcript
3. Click **"Generate Minutes"** → Get structured summary
4. Click **"Download PDF"** → Export results

---

## ⚙️ Tech Stack

* Python
* Transformers (Hugging Face)
* Whisper (Speech Recognition)
* LLaMA / LLM
* Gradio (UI)
* ReportLab (PDF generation)

---

## 📂 Project Structure

```text
├── meeting_minutes.ipynb              # Main Gradio app
├── meeting_minutes.pdf                # Generated output
```

---

## ▶️ Run the App

```bash
meeting_minutes.ipynb
```

---

## 🎬 Demo

### ▶️ Download and Watch Demo Video

![App Screenshot](/demo/demo.png)

---

### 📽️ What the Demo Shows

* 🎤 Uploading / recording meeting audio
* 📝 Transcription using AI
* 📊 Generating structured meeting minutes
* 📥 Downloading PDF report
* 🖥️ Built with Gradio

---

## 🌟 Future Improvements

* 🕒 Timestamp-based navigation
* 📊 Meeting analytics dashboard
* 🌐 Cloud deployment
* 🧾 Export to DOCX

---

