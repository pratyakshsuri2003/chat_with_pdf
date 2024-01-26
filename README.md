# LangChain PDF Questioning-Answering Flask Application

This is a Flask application that uses LangChain to load PDFs, chunk the text, create a vector database, and answer questions based on the text.

## Cloning the Repository

1. Open your terminal.
2. Change the current working directory to the location where you want the cloned directory.
3. Enter ```bash git clone https://github.com/pratyakshsuri2003/chat_with_pdf.git``` into your terminal.
4. Note: Please ensure that you have Git installed on your system before you try to clone the repository.

## Dependencies

- run the ```bash pip install -r requirements.txt``` command into your terminal to install all dependencies

## Setup

1. Install the required dependencies.
2. Set up LangChain by setting the `OPENAI_API_KEY` environment variable.

## Usage

The application has two routes:

- `/`: Renders the index page.
- `/ask`: Accepts a POST request with a question, uses LangChain to find the answer, and renders the index page with the question and answer.

## Running the Application

Run the application with `python app.py`.

## Note

Please replace the path to the PDF file and the OpenAI API key with your own.

## Copyright
@PratyakshSuri
