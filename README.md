# CV_Handler

🚀 A cloud-based tool for analyzing and managing large sets of CVs and documents. It supports document **uploading**, **title-based sorting**, **text-based searching** with highlighting, and **classification** using custom categories.

---

## 🔧 Tech Stack
- **Python** – Backend logic
- **Jupyter Notebook** – Development and testing
- **Supabase** – Cloud backend for storage
- **pdfminer.six / python-docx** – PDF and DOCX parsing
- **Scikit-learn** – Optional classification
- **Hugging Face Datasets** – For NER-labeled resume data

---

## 📂 Dataset

This project uses an annotated Named Entity Recognition (NER) dataset of resumes from Hugging Face:

**Dataset:** [Mehyaar/Annotated_NER_PDF_Resumes](https://huggingface.co/datasets/Mehyaar/Annotated_NER_PDF_Resumes)  
**Direct ZIP:** [ResumesPDF.zip](https://huggingface.co/datasets/Mehyaar/Annotated_NER_PDF_Resumes/blob/main/ResumesPDF.zip)

The dataset is included in the repository under the `data/` folder for demonstration and testing.

---

## 💡 Features

- 📁 Upload documents (PDF, DOCX) to the cloud (Supabase)
- 🔍 Search inside documents for text with keyword highlighting
- 🔃 Sort documents by actual document titles
- 🧠 Classify documents based on category tree or NER tags
- 📊 View analytics: number of documents, storage usage, processing time

---

## 🧪 How to Run Locally

```bash
git clone https://github.com/SamerAlshaer1991/CV_Handler.git
cd CV_Handler
jupyter notebook cv_handler_cleaned.ipynb
