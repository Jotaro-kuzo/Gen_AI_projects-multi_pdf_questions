# Gen_AI_projects-multi_pdf_questions
This is a model that can answer questions by taking multiple pdfs as input

Used GEMINI-PRO model for LLM.

FAISS, embedding-001 for embedding purpose.

Storing in local as of now as embedded files


# note : Before executing, get an API key from this [link](https://aistudio.google.com/app/apikey) and create a '.env' file and paste inside with variable name "GOOGLE_API_KEY".

# steps to execute:
1. Create a conda environment
     ```
     conda create -p venv python=3.10 -y
     ```
2. Install requirements.txt file
   ```
   pip install -r requirements.txt
   ```
3. Run the applicatioon
   ```
   streamlit run app.py
   ```
