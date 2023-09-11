![Logo](img/logo1.png "Logo")


**Try the app here:** [OmniChat on Streamlit Cloud](https://omnichat.streamlit.app/)

**Join the OmniChat Wait list here:** [OmniChat Landing page](https://yep.so/p/omnichat)

# PDF Analyzer App

PDF Analyzer App is a question-answering application that allows users to upload documents (PDF or TXT) and ask questions related to the content of those documents. The app utilizes various retrievers such as similarity search and support vector machines to provide relevant answers.

## Features

- Upload PDF or TXT documents
- Choose the type of retriever: Similarity Search or Support Vector Machines
- Generate sample question-answer pairs based on the uploaded documents
- Ask questions related to the content of the uploaded documents
- Get answers from the app using the selected retriever method

## Installation

Clone this repository:

```bash
git clone https://github.com/hbahuguna/pdf-analyze-streamlit.git
cd pdf-analyze-streamlit
```

Create a virtual environment and install the required packages:

```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## Usage
To run the app, simply execute the following command:

```bash
streamlit run chat_with_pdf_txt_file.py
```

After running the command, you can access the app through your web browser using the provided URL.

