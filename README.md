# Azure OpenAI PDF Reader and Question Answerer

The aim of this Proof of Concept (POC) is to demonstrate an application capable of reading content from both PDF and Word documents and utilizing Azure OpenAI's capabilities to answer questions based on the document's content. This tool leverages the GPT model deployed on Azure for extracting meaningful answers from the text contained within the documents.

This Python application reads text from a PDF file and uses an Azure OpenAI model to answer questions based on the PDF's content. It utilizes the Azure OpenAI API to interact with a GPT model deployed on Azure.

## Prerequisites

- Python 3.6 or higher
  1. Install python
  2. Install pip 
     py -m ensurepip --upgrade
     py get-pip.py
- An Azure account with an OpenAI service instance
- API key for the Azure OpenAI service

## Installation

1. Clone this repository to your local machine.
2. Install required Python libraries by running:

```sh
pip install pymupdf
pip install openai

python ./pdfExtract.py


References:
https://platform.openai.com/docs/api-reference/making-requests
https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/create-resource?pivots=web-portal
https://learn.microsoft.com/en-us/azure/ai-services/openai/quickstart?tabs=command-line%2Cpython&pivots=programming-language-java
