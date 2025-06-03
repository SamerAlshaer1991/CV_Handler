# CV_Handler

🚀 A cloud-based tool for analyzing and managing large sets of CVs and documents. It supports document **uploading**, **title-based sorting**, **text-based searching** with highlight, and **classification** using custom categories.

## 🔧 Tech Stack
- **Python** – Backend processing
- **Jupyter Notebook** – Development and demo
- **Supabase** – Cloud-based backend (PostgreSQL + Storage)
- **pdfminer / python-docx** – Document parsing
- **Streamlit / Gradio** (optional) – For interactive UI
- **Scikit-learn** – For classification
- **SQL** - for database handling

## 💡 Features

- 📁 Upload documents (PDF, DOCX) to the cloud (Supabase)
- 🔍 Search inside documents with keyword highlighting
- 🗂 Sort documents by actual document titles (not filenames)
- 🧠 Classify documents by topic or category
- 📊 Show analytics (storage usage, classification time, etc.)

## 🔗 Live Link
**Supabase Project Dashboard**  
[https://supabase.com/dashboard/project/vsshxukcoezxurinrzou](https://supabase.com/dashboard/project/vsshxukcoezxurinrzou)

## 🧪 How to Run Locally

```bash
git clone https://github.com/SamerAlshaer1991/CV_Handler.git
cd CV_Handler
jupyter notebook CV_Handler.ipynb
