# 🤖 GenAI Data Analysis Assistant

This project uses **Google Gemini AI** to help you:
- Ask questions about your dataset
- Get valid SQL queries (automatically)
- Understand query results in plain English

## 💡 Features

- 📁 Upload your own CSV or use a built-in Kaggle dataset
- 🧠 Few-shot prompting to suggest analysis directions
- 🧾 AI-generated SQL queries
- 🗣️ Natural language explanations of query results
- 🧪 Interactive agent loop: Chat with your data

## 📍 How to Run
Run directly in [Kaggle](https://www.kaggle.com/code/yanelly/querywhiz-ai-powered-data-questions-insights) or Jupyter Notebook.
Just upload a CSV file, or skip and use the Amazon sales dataset.

⚠️ Note:
This notebook was originally developed in Kaggle.
If you're running it locally in VSCode or another environment, a few adjustments are needed:

- Add your Google Gemini API key manually.

- Replace the Kaggle file path with a local dataset path.

- Adjust the file upload widget (or replace with standard file handling in Python).

## 🔧 Stack
- Google Generative AI (Gemini)
- Pandas
- SQLite
- IPyWidgets
