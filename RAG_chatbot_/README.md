Llama2 and Gradio-based PDF RAG ChatBot
PDFChatBot is a chatbot developed in Python, designed to respond to queries based on the content of uploaded PDF files. It leverages the Gradio library to build a user-friendly interface and LangChain for natural language processing.

Utilized Technologies 🚀
Langchain
Llama2
ChromaDB
Hugging Face
Gradio
Key Features ⭐
Processes PDF files and extracts information to answer questions.
Retains chat history and provides comprehensive explanations.
Generates responses using a Conversational Retrieval Chain.
Displays specific pages of PDF files relevant to the answer.
Preparations 📋
Before launching the ChatBot, make sure to install the necessary dependencies. You can do this using the following command:

pip install -r requirements.txt

Setup ⚙️
The ChatBot employs a configuration file (config.yaml) to define Hugging Face model and embeddings details. If you wish to use a different model or embeddings, ensure to update the configuration file with the correct values.

How to Use 📚
Use the "📁 Upload PDF" button to upload a PDF file.
Type your questions into the text box.
Press the "Send" button to submit your question.
The chat history and responses can be viewed in the interface.
Local Execution 💻
To run the PDF Interaction ChatBot, use the following command:

cd src

python app.py
