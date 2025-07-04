## Aboout the Project
This is a Python application that allows you to load a PDF and ask questions about it using natural language. The application uses a LLM to generate a response about your PDF. The LLM will not answer questions unrelated to the document. The application reads the PDF and splits the text into smaller chunks that can be then fed into a LLM. It uses OpenAI embeddings to create vector representations of the chunks. The application then finds the chunks that are semantically similar to the question that the user asked and feeds those chunks to the LLM to generate a response. Here is the Proof of Concept.

## Required Libraries

 - tiktoken
 - faiss-cpu
 - langchain
 - PyPDF2
 - python-dotenv
 - streamlit
 
#  Installation 

This is make you understand how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps.

1. Clone the repo

 ```
 git clone https://github.com/KalyanMurapaka45/DocGenius-Revolutionizing-PDFs-with-AI.git
 ```
 
 2. Install the required libraries

```
pip install -r requirements.txt
```

```You will also need to add your OpenAI API key to the .env file.```

3. To use the application, run the ```app.py``` file with the streamlit CLI (after having installed streamlit):

```
streamlit run app.py
```


# Acknowledgements

We would like to express our gratitude to the open-source community for their invaluable inspiration and contributions. We also acknowledge the Python libraries used in this project and their respective contributors.
# chat-with-llm
