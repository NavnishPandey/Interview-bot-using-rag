🤖 AI Interviewer Bot using RAG (Retrieval-Augmented Generation)
This project explores how Retrieval-Augmented Generation (RAG) can be used to build an AI-powered interviewer that dynamically asks questions based on a candidate's CV and a given job description.

The bot reads a candidate’s PDF resume, understands the job requirements, and conducts an interactive interview, generating context-aware and follow-up questions intelligently.

Goal: To experiment with combining RAG + LLMs to simulate real-world AI interviewing scenarios

✨ Key Features
📄 PDF CV Parsing — Extracts structured text from uploaded CVs.

🔍 Knowledge Base Creation — Splits both CV and job description into meaningful chunks.

🧠 Embedding & Retrieval — Embeds chunks using SentenceTransformer and retrieves the most relevant information via a FAISS index.

🎯 Context-Aware Question Generation — Dynamically generates initial and follow-up questions using Google's Gemma-3-4b-it LLM.

🗝️ Keyword Extraction — Focuses the interview around important skills or topics using NLTK-based keyword extraction.

🔥 Conversational Flow — Understands previous responses and tailors next questions accordingly.

🛠️ Error Handling & User Friendly — Smooth fallbacks if any errors occur during generation or parsing.

Built-in functions are functions that are part of the Python language itself. They are not defined by the programmer; they are part of the language's design. They are available directly from the interpreter.
For example, `print()` is a built-in function that displays output to the screen. Other built-in functions include `len()`, `range()`, `input()`, `str()`, `int()`, `float()`, `list()`, `tuple()`, `dict()`.

### Explanation:
*   **Definition:** Built-in functions are parts of the Python language.
*   **Availability:** They are available directly from the interpreter.
*   **Purpose:** They perform specific operations or provide access to data.
*   **Example:** `print("Hello, world!")` uses the `print()` function, which is a built-in function.

### Further Reading:
[https://docs.python.org/3/tutorial/intro.html](https://docs.python.org/3/tutorial/intro.html)

### Conclusion:
Built-in functions are essential tools in Python, providing convenient ways to perform common tasks.

### Summary:
Python provides a rich set of built-in functions, making it easy to accomplish various tasks.  Understanding these functions is crucial for effective Python programming.

### Additional Notes:
*   Python's documentation is comprehensive and readily accessible online.
*   There are numerous tutorials and resources available to help you learn Python.
