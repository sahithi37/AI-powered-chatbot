# AI-Powered Chatbot for Lecture Note Retrieval and Summarization

This AI-powered chatbot is designed to assist users with:
- Fetching lecture notes based on queries.
- Summarizing uploaded PDF or PowerPoint files.
- Answering general questions using a pre-trained LLaMA model.


## Features
- **Lecture Note Retrieval**: Fetches the most relevant lecture notes based on user input.
- **Document Summarization**: Summarizes uploaded PDF or PowerPoint files in simple terms.
- **Question Answering**: Provides answers to user queries using advanced natural language processing techniques.

  ## Technologies Used

- **Transformers Library**: For pre-trained LLaMA model integration.
- **Gradio**: To create a user-friendly chatbot interface.
- **PyMuPDF (fitz)**: For extracting text from PDF files.
- **python-pptx**: For extracting text from PowerPoint slides.
- **BitsAndBytesConfig**: For efficient model quantization.


1.Clone the Repository
Download the project files from the GitHub repository using the following command:
- git clone https://github.com/sahithi37/AI-powered-chatbot.git
 
2.Navigate to the Project Directory
Move into the cloned project folder:
- cd AI-powered-chatbot
  
3.Set Up the Environment
Ensure you have Python installed (version 3.7 or later). If you don't, download and install it from python.org.
- pip install notebook

4.Install Jupyter Notebook or JupyterLab if not already installed:
Install the Required Python Libraries
Install all dependencies needed to run the chatbot. Use the requirements.txt file for easy setup:
- pip install -r requirements.txt
  
5.Open the Jupyter Notebook
Launch Jupyter Notebook or JupyterLab and open the file:
- jupyter notebook "AI Powered academic chatbot.ipynb"

6.Run the Notebook
In Jupyter Notebook, navigate to the directory where the .ipynb file is located.
Open the AI Powered academic chatbot.ipynb file.
Run each cell sequentially by clicking "Run" or pressing Shift + Enter.

7.Interact with the Chatbot
Once the notebook is running, a Gradio interface link will appear in the output of one of the cells. Click on the link to access the chatbot in your browser.

8.Use the chatbot for:

Lecture Note Retrieval: Type queries like "notes for RNN" to fetch relevant lecture notes.
Document Summarization: Upload a PDF or PowerPoint file for summarization.
Question Answering: Ask questions like "What is an LSTM?" for detailed explanations.

## Future Enhancements

- Add support for more file types like Word documents.
- Integrate voice input and output capabilities.
- Improve accuracy for lecture note retrieval with semantic matching.
