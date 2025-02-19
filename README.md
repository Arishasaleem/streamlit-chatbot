Streamlit Chatbot with Llama 2 (Replicate API)

🚀 Introduction

This project is a Streamlit-powered chatbot that utilizes Llama 2, an open-source large language model (LLM), via Replicate API. The chatbot provides conversational AI capabilities and can be deployed as a web app with an intuitive UI.

🏗️ Features

💬 Interactive Chat Interface – User-friendly chat-based UI powered by Streamlit.

🦙 Llama 2 Model Integration – Uses Llama 2 (7B & 13B) via Replicate API.

⚙️ Customizable Parameters – Adjust temperature, top-p, and max token length for better responses.

🔒 Secure API Handling – API keys are managed securely using Streamlit secrets.

☁️ Easy Deployment – Can be deployed to Streamlit Cloud or other hosting platforms.

📦 Installation

To get started, clone this repository and install the required dependencies:

# Clone the repository
git clone https://github.com/Arishasaleem/streamlit-chatbot.git
cd streamlit-chatbot

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

🔑 API Key Setup

To use the Replicate API, store your API key securely:

Create a .streamlit/secrets.toml file in the root directory.

Add your API key:

[secrets]
REPLICATE_API_TOKEN = "your-api-key-here"

🚀 Running the App

Start the chatbot locally with:

streamlit run app.py

This will launch the chatbot in your default web browser.

📌 Usage

Open the web app in your browser.

Enter a message in the chat input.

The chatbot will generate a response using Llama 2.

Adjust parameters in the sidebar to fine-tune responses.

📤 Deployment

To deploy the chatbot on Streamlit Cloud:

Push your code to a GitHub repository.

Go to Streamlit Cloud and log in.

Click New App, select your repository, and deploy.

Add your API key under Settings > Secrets in Streamlit Cloud.

🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

📄 License

This project is licensed under the MIT License. See LICENSE for details.

📧 Contact

For questions or feedback, reach out via GitHub Issues.

💡 Built with ❤️ using Streamlit, Replicate, and Llama 2.

