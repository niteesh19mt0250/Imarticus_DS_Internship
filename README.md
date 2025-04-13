# Imarticus_DS_Internship

# ML Dashboard & PDF Chatbot Application

This is a dual-purpose Streamlit application built for the **Imarticus Data Science Internship – Assessment**. It combines a **machine learning dashboard** for predicting product clicks and a **PDF-based AI chatbot** that answers user questions from technical documents (Python, SQL, ML).


## Features

**Interactive Dashboard**  
- Upload CSV files and predict user engagement (clicks)  
- Supports features like `product_type`, `price`, and `timestamp` or `hour_of_day`  
- Visualizations include:
  - Average predicted clicks by product type
  - Time-series plot of predicted clicks
  - Actual vs. predicted clicks etc.

**PDF Q&A Chatbot**  
- Ask natural language questions from domain PDFs  
- Documents include: `python.pdf`, `sql.pdf`, and `ml.pdf`  
- Powered by FAISS + HuggingFace Transformers  
- Extracts accurate answers with source and context


## Required libraries
pip install streamlit pandas numpy joblib scikit-learn faiss-cpu transformers sentence-transformers

**How to Run the App**
streamlit run main_app.py



