Local ChatGPT App
This project uses Llama 3.2 Vision and Chainlit to create a fully local ChatGPT app.

Setup Instructions
1. Install Ollama:
To set up Ollama on Linux, run the following command:

bash
Copy code
curl -fsSL https://ollama.com/install.sh | sh
Then, download the Llama 3.2 Vision model:

bash
Copy code
ollama pull llama3.2-vision
2. Install Dependencies:
Make sure you have Python 3.11 or later installed. Then, install the required packages:

bash
Copy code
pip install pydantic==2.10.1 chainlit ollama
3. Run the App:
Start the Chainlit app using this command:

bash
Copy code
chainlit run app.py -w
That's it! Your local ChatGPT app is now ready to use.
