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

### Running Locally:
To run the project locally in environments like VSCode or Jupyter Notebook, follow these steps:

1. **Install Dependencies**:
    - Make sure to install the required Python packages:
      ```bash
      pip install google-generativeai pandas sqlite3 ipywidgets
      ```
2. **Set Up Your Google Gemini API Key**:
    - Add your Google Gemini API key manually in the code. Replace the placeholder with your API key:
      ```python
      GOOGLE_API_KEY = "your_api_key_here"
      ```

3. **Replace Dataset Path**:
    - If using a custom dataset, replace the Kaggle dataset path with your local file path.
    - Example:
      ```python
      data = pd.read_csv('path_to_your_local_file.csv')
      ```

4. **File Upload Widget**:
    - If you prefer to use the file upload widget, ensure that your environment supports `ipywidgets`. Otherwise, you can replace the widget with standard file handling in Python.

### ⚠️ Note:
This notebook was originally developed in Kaggle. To run it locally, you may need to make a few adjustments, as outlined above.

## 🔧 Stack
- Google Generative AI (Gemini)
- Pandas
- SQLite
- IPyWidgets