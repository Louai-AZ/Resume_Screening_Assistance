# Resume_Screening_Assistance

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
