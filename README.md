# **Data Insights AI Assistant** 

An **interactive and intelligent Streamlit-based data analysis tool** powered by **Google's Gemini AI via LangChain**. Upload your datasets, get instant statistics, visualizations, and ask natural language questions about your data — all in one app.

**Live Demo**: https://datalens-vmhvqbepcss7ka9jfjrqpz.streamlit.app/

---

## **Features**

### **Upload Support**

  - Upload .csv, .xlsx, or .xls files for analysis.

### **Overview Tab**

  - View dataset shape, data types, missing values, duplicate rows, correlation matrix, distributions, and more.

### **Chat Assistant**

  - Ask questions about your data using natural language.

  - Powered by Gemini 1.5 via LangChain.

### **Insights Tab**

  - Auto-generated basic and advanced statistical insights, categorical analysis, and ML preprocessing recommendations.

### **Interactive Graphs**

  - Create scatter plots, line charts, bar charts, histograms, box plots, violin plots, pair plots, and heatmaps.

  - Filter data interactively.

---

## **Powered By**

  - Gemini 1.5 (via LangChain)

  - Streamlit

  - Plotly

  - Seaborn / Matplotlib

  - Pandas / NumPy

---

## **Folder Structure**

  ```bash
├── app.py              # Main Streamlit app
├── .env                # Store your Google API key here
├── requirements.txt    # All required Python dependencies
└── README.md           # This file
```

---

## **Environment Setup** 

  - Create a .env file in the root directory with your Google API key:

  - GOOGLE_API_KEY=your_google_genai_key

  - You must have access to Google Gemini API via Google AI Studio or Vertex AI.

---

## **Installation**
### **Step-by-step**

  - Clone the repository:
    git clone <repository_url>
    cd <repository_name>

  - Create a virtual environment (optional but recommended):
    python -m venv venv
    source venv/bin/activate (Windows: venv\Scripts\activate)

  - Install dependencies: pip install -r requirements.txt

  - Run the app: streamlit run app.py

---

### **Example Prompts for Chat Assistant**

  - "What is the average salary across departments?"

  - "Suggest preprocessing steps for building a classification model."

  - "Are there any correlations between age and purchase amount?"

  - "Which categories have the highest frequency?"

---

## **Requirements**

  - streamlit

  - pandas

  - numpy

  - plotly

  - matplotlib

  - seaborn

  - langchain

  - langchain-google-genai

  - python-dotenv

  - openpyxl

---

## **Acknowledgements**

  - LangChain

  - Google Gemini

  - Streamlit

  - Plotly

---

## **Future Improvements**

  - Add support for uploading multiple files

  - Enable export of visualizations

  - Add session saving and report generation

  - Improve multilingual chat support
