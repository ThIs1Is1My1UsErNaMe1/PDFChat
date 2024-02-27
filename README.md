# PDFChat

What you will need to do:

1) Install all dependencies:
    pip install streamlit pypdf2 langchain python-dotenv faiss-cpu openai huggingface_hub

    pip install -r requirements.txt


2) To use other chat vector embedders from HuggingFace (not openai, e.g. llama2):
    pip install InstructorEmbedding sentence_transformers

3) create a .env file, in it upload your hugging face api key, and open ai key to use open ai models:

   HUGGINGFACEHUB_API_TOKEN =
   OPENAI_API_KEY=

5) Run the app using:
   streamlit run app.py

