# PDF_Chatbot--Python--OpenAI--NLP

# Introduction
The MultiPDF Chat App is a Python application that allows you to chat with multiple PDF documents. You can ask questions about the PDFs using natural language, and the application will provide relevant responses based on the content of the documents. This app utilizes a language model to generate accurate answers to your queries. Please note that the app will only respond to questions related to the loaded PDFs.

The chatbot follows these steps to provide responses to your questions:
  1. PDF Loading: The chatbot reads and extracts text content from multiple PDF documents.
  2. Text Chunking: The extracted text is segmented into smaller, manageable portions for efficient processing.
  3. Language Model Utilization: The chatbot employs a language model to create vector representations (embeddings) of these text segments.
  4. Semantic Matching: When you pose a question, the chatbot evaluates it against the text segments, identifying those with the highest semantic similarity.
  5. Response Generation: The chosen text segments are then fed into the language model, which subsequently generates a response based on the pertinent content within the PDFs.

# Usage
To use the MultiPDF Chat App, follow these steps:
  1. Clone the repository to your local machine.
  2. Install the required dependencies by running the following command: `pip install -r requirements.txt`
  3. Obtain an API key from OpenAI and add it to the .env file in the project directory : `OPENAI_API_KEY=your_secrit_api_key`
  4. Run the app.py file using the Streamlit CLI. Execute the following command: `streamlit run app.py`
  5. The chatbot will open in your web browser by default, presenting the user interface.
  6. You can load several PDF documents and ask questions in natural language about the loaded PDFs using the chat interface.
      

