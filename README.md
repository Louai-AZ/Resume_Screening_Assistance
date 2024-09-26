# Resume_Screening_Assistance


## Overview : 

Developed a tool for HR professionals called "Resume Screening Assistance." Built using Python and Streamlit, this application automates the tedious process of screening resumes by leveraging cutting-edge NLP techniques. By integrating OpenAI's language models, Pinecone vector stores, and Sentence Transformers, the tool efficiently extracts information from PDF resumes and matches them with job descriptions, significantly streamlining the hiring process.


## How to run the code :

1. Clone this repository :
```ini
git clone https://github.com/Louai-AZ/Resume_Screening_Assistance.git
```
2. Create a virtual environment and activate it :
```ini
conda create -n HRenv python=3.10 -y 
conda activate HRenv 
```
3. Install the dependencies : 
```ini
pip install -r requirements.txt
```
4. Create a `.env` file in the root directory and add your Pinecone credentials as follows :

```ini
PINECONE_API_KEY = ""
PINECONE_API_ENV = ""
index_name=""
```

5. Run :
```ini
streamlit run app.py
```


## TechStack Used : 
- Python
- LangChain
- Streamlit
- OpenAI
- Pinecone Vector Database
