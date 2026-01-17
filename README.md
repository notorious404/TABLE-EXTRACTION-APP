# TABLE-EXTRACTION-APP
📄 PDF / Document Table Extraction App automatically detects, extracts, and reconstructs tables from PDF and DOCX files, including scanned documents using OCR. It supports multi-page files, complex layouts, and generates a consolidated PDF report. This project focuses only on table extraction; comparison is handled separately.

## ABOUT 

## 🧑‍💻 Author

Shantanu Yadav 

## 📜 License

This project is licensed under the MIT License.

---

## 🚀 Features

- 📤 Upload **PDF** and **DOCX** files
- 🧠 Detect tables from:
  - Digitally generated PDFs
  - Scanned PDFs using **OCR**
- 📊 Accurate table extraction and reconstruction
- 🧩 Handles:
  - Pipe-based tables
  - Complex document layouts
- 📈 Real-time progress tracking using Streamlit
- 📄 Generates a **consolidated PDF report** of all extracted tables
- 🗂️ Supports multi-page documents

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – Web-based user interface
- **pdfplumber** – Table extraction from text-based PDFs
- **Tesseract OCR** – Table extraction from scanned PDFs
- **OpenAI API** – Intelligent table reconstruction
- **ReportLab** – PDF report generation

---

## 📌 Use Cases

- Financial and audit reports
- Research papers and academic documents
- Government and legal PDFs
- Invoices and statements
- Any document containing structured tables

---

## 📂 Project Workflow

1. Upload PDF or DOCX file
2. Detect whether the document is scanned or digital
3. Apply OCR if required
4. Identify table structures
5. Reconstruct tables using AI
6. Generate a consolidated PDF with extracted tables

---

## 📄 Output

- Clean, structured tables
- Consolidated PDF containing all extracted tables
- Readable and analysis-ready format

---

## 🧩 Scope Clarification

- ✅ This project focuses **only on table extraction**
- 🔗 Comparison logic exists in a **separate repository**

---

## ⚙️ Installation

-git clone https://github.com/your-username/table-extraction-app.git
-cd table-extraction-app
-pip install -r requirements.txt

## ▶️ Run the App
-streamlit run app.py

## 🔐 Environment Variables

-Create a .env file and add:

-OPENAI_API_KEY=your_api_key_here

## 📌 Limitations

-Accuracy depends on document quality

-Highly irregular tables may require manual review

-OCR performance depends on scan clarity

# END
