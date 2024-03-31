# Gemini Copilot

Gemini Copilot is a Python application that utilizes the Gemini API to run locally on a server. It provides functionalities to interact with the Gemini platform.

## Installation

1. Clone the repository

2. Navigate to the project directory

3. Create a file named `api_key.env` and add your Gemini API key:

   ```plaintext
   GEMINI_API_KEY=<YOUR-KEY>
   ```

   Replace `<YOUR-KEY>` with your actual Gemini API key, which can be obtained from [ai.google.dev](https://ai.google.dev).

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the application with the following command:

```bash
streamlit run copilot.py
```

If you encounter any errors while running the application, please read the error message and install the appropriate dependencies. Some common dependencies to install include `python-dotenv`, `ipython`, and `streamlit-extras`.

Ensure that you have a stable internet connection to use the application effectively.