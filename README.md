# 📘 AI-Driven Assignment Evaluation and Scoring System
#### Automated PDF Extraction • LLM-Based Evaluation • Zero Manual Effort

**🚀 Overview**
In academic settings like Innomatics, faculty receive dozens of assignment ZIP files every day. Each ZIP contains multiple PDFs, and every PDF includes Python questions with handwritten or typed student answers.
Manually evaluating these submissions is time-consuming, repetitive, and often inconsistent.

To solve this, I built an end-to-end automated assignment evaluation pipeline that uses LLMs to accurately grade each question and generate structured reports — with no manual intervention.

#### 🎯 Features
**🔍 1. ZIP File Handling**
- Accepts ZIP files uploaded by faculty or students
- Automatically extracts all PDFs
- Supports deeply nested folders inside ZIPs

**📄 2. PDF → Text Conversion**
- Converts every PDF into clean, structured text
- Removes noise, headers, footers, watermarks
- Optimized for both handwritten and typed submissions

**🧩 3. Intelligent Q&A Extraction**
- Splits text into:
 - Question
 - Student Answer
- Handles inconsistent formatting across submissions

**🤖 4. LLM-Powered Evaluation**
- Each Q&A pair is sent to an evaluation LLM
- Returns:
- Score (0–10)
- Detailed feedback
- Error analysis & improvement suggestions

**📊 5. Automated Score Aggregation**
- Summarizes question-wise marks
- Computes total score
- Organizes final data into clean structures

**🛠️ Tech Stack**
- Python
- PyPDF2 / PDFPlumber – PDF parsing
- LangChain / LLM API (Gemini / OpenAI / Claude)
- Regex for question segmentation
- JSON for structured scoring

**📸Screenshot**
<img width="1268" height="547" alt="Screenshot 2025-11-21 162928" src="https://github.com/user-attachments/assets/65421950-1216-4f6a-9fb5-57422f9d1961" />

FastAPI / Flask (optional) for API deployment
