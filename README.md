# 🤖 AI Interviewer Bot using RAG (Retrieval-Augmented Generation)
This project explores how Retrieval-Augmented Generation (RAG) can be used to build an AI-powered interviewer that dynamically asks questions based on a candidate's CV and a given job description.

The bot reads a candidate’s PDF resume, understands the job requirements, and conducts an interactive interview, generating context-aware and follow-up questions intelligently.

## Goal: To experiment with combining RAG + LLMs to simulate real-world AI interviewing scenarios.


### ✨ Key Features
**📄 PDF CV Parsing** — Extracts structured text from uploaded CVs.

**🔍 Knowledge Base Creation** — Splits both CV and job description into meaningful chunks.

**🧠 Embedding & Retrieval** — Embeds chunks using SentenceTransformer and retrieves the most relevant information via a FAISS index.

**🎯 Context-Aware Question Generation** — Dynamically generates initial and follow-up questions using Google's Gemma-3-4b-it LLM.

**🗝️ Keyword Extraction** — Focuses the interview around important skills or topics using NLTK-based keyword extraction.

**🔥 Conversational Flow** — Understands previous responses and tailors next questions accordingly.

**🛠️ Error Handling & User Friendly** — Smooth fallbacks if any errors occur during generation or parsing.


### 💡 Example Use Case
**Recruitment Process Automation:** Pre-screening candidates automatically.

**Career Services:** Helping students prepare for interviews based on their resumes.

**Mock Interviews:** Generating realistic interview questions dynamically.


### 📢 Future Improvements
Add support for multiple CV formats (docx, image-based PDFs with OCR).

Improve retrieval and chunking for longer documents.

Implement better conversational memory (full dialogue context tracking).

Integrate with Streamlit or Gradio for building an easy-to-use web app.

Support multi-turn dialogue with a more advanced conversational agent.


