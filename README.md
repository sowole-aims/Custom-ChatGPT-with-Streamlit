
# Custom ChatGPT App with Streamlit

## Overview
This application is a custom ChatGPT interface built using Streamlit and the `langchain` package. It offers an interactive chat experience powered by OpenAI's GPT models.

## Features
- **Streamlit Interface**: A user-friendly web interface for easy interaction.
- **Customizable GPT Models**: Supports various GPT models, including GPT-3.5, allowing for flexibility in response styles and capabilities.
- **Environment Variables**: Secure handling of API keys using `.env` files.
- **Interactive Chat**: Real-time conversational capabilities with the chatbot.

## Installation

### Prerequisites
- Python 3.8 or higher
- An OpenAI API key

### Setup
1. **Clone the Repository**
   ```
   git clone https://github.com/sowole-aims/Custom-ChatGPT-with-Streamlit.git

   cd Custom-ChatGPT-with-Streamlit
   ```

2. **Install Dependencies**
   ```
   pip install -r requirements.txt
   ```

3. **Set up Environment Variables**
   - Create a `.env` file in the root directory.
   - Add your OpenAI API key: `OPENAI_API_KEY="your-api-key"`.

### Running the Application
Execute the following command in your terminal:
```
streamlit run project_streamlit_custom_chatgpt.py
```
The app should now be running on `http://localhost:8501`.

## Usage
- Open the provided URL in your web browser.
- Interact with the ChatGPT bot through the Streamlit interface.
- Customize model settings as needed for different response styles.



## License
This project is licensed under the [MIT License](LICENSE).


## Acknowledgments
This project utilizes the Langchain library, OpenAI API, and Streamlit Web Framework.

## Important Note
Please ensure that you have a valid OpenAI API key to use the application. If you don't have one, sign up for an API key at the OpenAI website before running the chatbot.


