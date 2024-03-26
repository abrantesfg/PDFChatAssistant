# PDFChatAssistant

This repo contains the code for the PDFChatAssistant project. In the code, the system ingest and process information from PDF documents. A user is able to input a query, and the system should output the answer to the query based on the content of the documents.

## Pre-requisites

This code requires the installation of the packages: openai, PyMuPDF, PyPDF2 and gensim.

In addition, paste your OpenAI api key in the `config.json` file in order to be able to use the system. The `config.json` file must be located on the same directory as `main.py`.

## Using the chatbox

To interact with the system, run the command line

`python3 main.py`

First the system will as for the PDF path:

`Enter a PDF path to interact with or type 'exit' to quit:<path/to/pdf>`

Once loaded, the user can query on the PDF document. 
