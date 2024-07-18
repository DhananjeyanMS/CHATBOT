# ChatBot Project

Welcome to the ChatBot Project repository. This project contains a simple web-based chatbot interface built using HTML, CSS, and JavaScript, with a backend powered by Python and Flask. The chatbot reads and processes text from PDF and DOCX files and answers user queries using OpenAI's language model.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites
- Python 3.7+
- Flask
- docx
- PyPDF2
- langchain
- OpenAI API key
- Jupyter Notebook (for exploratory data analysis)

### Steps

1. Clone the repository:

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Set up environment variables:
    - Create a `.env` file in the project root directory.
    - Add your OpenAI API key:
      ```env
      OPENAI_API_KEY=your_openai_api_key
      ```

5. Run the Flask application:
    ```sh
    python flask_app.py
    ```

6. Open your browser and navigate to `http://127.0.0.1:5000` to access the chatbot.

## Usage

- Open the web application in your browser.
- Enter your query in the input box and press "Send".
- The chatbot will respond based on the content of the processed documents.

## Project Structure

```plaintext
chatbot-project/
├── static/
│   ├── style.css
│   ├── script.js
├── templates/
│   ├── index.html
├── file_reading.py
├── flask_app.py
├── text_processing.py
├── exploratory_data_analysis.ipynb
├── requirements.txt
└── README.md
```

### Files Description

- **static/style.css**: Contains CSS styles for the chatbot interface.
- **static/script.js**: Contains JavaScript code for handling user input and displaying chatbot responses.
- **templates/index.html**: HTML template for the chatbot interface.
- **file_reading.py**: Contains functions to read and extract text from PDF and DOCX files.
- **flask_app.py**: The main Flask application file that handles routes and requests.
- **text_processing.py**: Contains functions for processing text and querying the language model.
- **exploratory_data_analysis.ipynb**: Jupyter Notebook file for exploratory data analysis.
- **requirements.txt**: Lists the Python dependencies for the project.
- **README.md**: Project documentation.

