# Smart ML Chatbot Assignment

This is a modern Long Language Model (LLM) based chatbot using Google's Gemini API and the Streamlit web framework. This makes for an impressive piece of coursework that demonstrates understanding of modern API integrations and Python web apps.

## Setup Instructions

### 1. Prerequisites
You need to have Python installed on your computer.

### 2. Install Required Libraries
Open your terminal (Command Prompt or PowerShell), navigate to this folder, and run:
```bash
pip install -r requirements.txt
```

### 3. Get a Gemini API Key (Free)
1. Go to Google AI Studio: [https://aistudio.google.com/](https://aistudio.google.com/)
2. Sign in with your Google account.
3. Click "Get API key" and create a new key.
4. Copy the key.

### 4. Configure Your Key
You can configure the key in two ways:
- **Option A (Easier):** Just run the app and paste the key into the app's sidebar interface when it loads.
- **Option B (Better):** Rename the `.env.example` file to `.env` and paste your key inside it: `GEMINI_API_KEY=your_actual_key_here`

### 5. Run the Chatbot
To start the chatbot interface yourself at any time, simply follow these steps in your Command Prompt:

1. Open a new Command Prompt (cmd)
2. Travel to the project folder by running:
   ```cmd
   cd C:\Users\Vaibhavi\.gemini\antigravity\scratch\ml_chatbot
   ```
3. Activate the Python virtual environment (this is where all the libraries are stored):
   ```cmd
   .\venv\Scripts\activate
   ```
4. Start the app:
   ```cmd
   streamlit run app.py
   ```

It will automatically open a browser window with your new, smart AI chatbot!
