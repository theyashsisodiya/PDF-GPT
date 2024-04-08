Below is a sample README file for your project along with step-by-step instructions:

---

# PDF-GPT

PDF-GPT is a Streamlit application that allows users to interactively ask questions based on the content of PDF files using Google's Generative AI and Langchain technologies.

## Requirements

Make sure you have the following dependencies installed:

- `streamlit`
- `google-generativeai`
- `python-dotenv`
- `langchain`
- `PyPDF2`
- `chromadb`
- `faiss-cpu`
- `langchain_google_genai`



## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/theyashsisodiya/PDF-GPT.git
   ```

2. Navigate to the project directory:

   ```bash
   cd PDF-GPT
   ```

3. You can install these dependencies using the provided `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up your Google API key:

   Create a `.env` file in the PDF-GPT folder or in your project folder and add your Google API key from [Create API key](https://aistudio.google.com/app/apikey) :

   ```dotenv
   GOOGLE_API_KEY=<your_api_key>
   ```

5. Run the application:

   ```bash
   python -m streamlit run app.py
   ```

6. In the Streamlit app, upload your PDF files and click on the "Submit & Process" button.

7. Ask your questions in the text input field provided.

8. The application will generate responses based on the content of the uploaded PDF files.

## Code Overview

The main code file `app.py` contains the following functionalities:

- Reading text from PDF files.
- Splitting text into smaller chunks.
- Generating embeddings using Google's Generative AI.
- Creating a vector store using FAISS.
- Setting up a conversational chain for question-answering.
- Handling user input and generating responses.
- Setting up the Streamlit UI for user interaction.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize the README file further according to your project's specific details and requirements. Let me know if you need any further assistance!
