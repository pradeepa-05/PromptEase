📄 PromptEase – AI Middleware Advanced

PromptEase is a Streamlit-based AI Middleware App that allows users to interact with multiple LLMs (via OpenRouter) with customizable parameters such as task, tone, style, depth, persona, and more.

It comes with user authentication (SQLite-based) where users can store their OpenRouter API key securely.

🚀 Features

• 🔐 User Authentication (Signup/Login with SQLite DB)
• 🗝️ Secure API Key storage per user
• 🤖 Multiple Model Support
○ ChatGPT (openai/gpt-oss-20b:free)

○ Gemini (google/gemma-3-27b-it:free)

○ Mistral (z-ai/glm-4.5-air:free)

○ LLaMA (meta-llama/llama-3.3-70b-instruct:free)

○ DeepSeek (deepseek/deepseek-r1-0528-qwen3-8b:free)

○ NVIDIA (nvidia/llama-3.1-nemotron-ultra-253b-v1:free)

• ⚙️ Customizable Parameters

○ Task, Mode, Style, Persona, Depth, Format, Language, Tone, Domain

○ Creativity, Bias Filter, Speed/Quality, Memory Mode

• 🟪 Persistent Chat History (per session)

• 🖼️ Modern Streamlit UI

📁 Project Structure

📦 project-folder
├── 📜 app.py            # Main Streamlit app
├── 📜 users.db          # SQLite database (auto-created)
├── 📜 README.md         # Documentation
└── 📜 requirements.txt  # Python dependencies

🛠️ Installation & Setup

1. Clone Repository

git clone https://github.com/your-username/promptease.git
cd promptease

2. Create Virtual Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate      # On Mac/Linux
venv\Scripts\activate         # On Windows

3. Install Dependencies

pip install -r requirements.txt

4. Run the App

streamlit run app.py

📦 requirements.txt

streamlit
sqlite3    # (comes with Python, no need to install)
requests

🔑 API Key Setup

1. Sign up at OpenRouter.
2. Generate your API key from https://openrouter.ai/keys.
3. Use the key while signing up in the app.

💡 Usage

• Signup/Login using the sidebar.
• Choose model & parameters (task, tone, style, etc.).
• Enter prompt and hit 🚀 Submit.
• Responses will appear in a chat-like interface.

🎨 UI Preview

• Sidebar for login, logout, and parameter selection.
• Chat area with conversation history.
• Smooth authentication flow.

🤝 Contributing

Contributions are welcome!
Feel free to fork, create an issue, or submit a PR to improve functionality/UI.

📜 License

MIT License © 2025
Free to use and modify.

⭐ Acknowledgements

• Streamlit
• OpenRouter
• SQLite

Made with ❤️ using Python + Streamlit
