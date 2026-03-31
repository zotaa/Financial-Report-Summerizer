# Financial Report Summarizer (PDF → Insight)
Overview
Project ini bertujuan untuk mengekstrak data dari laporan keuangan berbentuk PDF dan mengubahnya menjadi insight perkembangan perusahaan secara otomatis.

Objectives
- Mengotomatisasi analisis laporan keuangan
- Mengurangi proses manual dalam membaca laporan PDF
- Menyediakan insight perkembangan perusahaan secara cepat

Features
- Ekstraksi teks dari PDF
- Parsing data keuangan (laba, aset, dll)
- Transformasi ke DataFrame (pandas)
- Analisis pertumbuhan bulanan (MoM Growth)
- Visualisasi data
- Auto-generated financial summary

Tech Stack
- Python
- pandas
- numpy
- pdfplumber
- matplotlib

Project Structure
financial-report-summarizer/
│
├── notebook.ipynb
├── dataset.csv
├── sample_pdf/
├── README.txt

Data Pipeline
PDF → Text Extraction → Data Parsing → Data Cleaning → Analysis → Summary

Variables Extracted
- Laba Bersih
- Pendapatan Bunga
- Total Aset
- Growth Laba (%)
- Growth Aset (%)

Example Summary
Pada bulan Februari 2026, perusahaan mencatat laba sebesar 9,228,168.
Terjadi pertumbuhan laba sebesar 84.61% dibanding bulan sebelumnya.
Total aset mencapai 1,563,219,350.

How to Run
1. Buka di Google Colab
2. Upload PDF dan notebook
3. Install dependencies: pdfplumber pandas numpy matplotlib
4. Jalankan notebook

Use Case
- Financial Analyst
- Data Analyst
- Investment Analyst
- Audit Automation

Future Improvements
- NLP summarization (AI-based)
- Dashboard (Streamlit)
- Integrasi database
- OCR support (Tesseract)

Author
Kavilla Zota Qurzian
