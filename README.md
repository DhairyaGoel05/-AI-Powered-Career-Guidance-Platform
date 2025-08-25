🚀 AI-Powered Career Guidance Platform
Welcome to the AI-Powered Career Guidance Platform! This interactive web application leverages the power of Google's Gemini API and LangChain to provide users with personalized career insights, detailed market analysis, and tailored learning roadmaps.
✨ Features🔍 Career Discovery: Explore a wide range of career paths across different industries like Technology, Healthcare, Business, and Creative fields.
📊 In-Depth Analysis: Get a comprehensive overview of any selected career, including key responsibilities, required skills, and educational background.
📈 Real-Time Market Insights: Analyze current job market trends, salary ranges by experience level, job growth projections, and geographic hotspots for opportunities.
📚 Personalized Learning Roadmaps: Receive a custom-tailored learning plan based on your experience level, with recommended courses, resources, and timelines.
💬 AI Chat Assistant: Engage in a conversation with an AI-powered assistant to ask specific questions about your chosen career path.
👤 User Profile & Skills Assessment: Create a personal profile and rate your skills to receive more tailored recommendations.
🛠️ Tech StackBackend: PythonWeb Framework: StreamlitAI/LLM Orchestration: LangChainLanguage Model: Google Gemini APIWeb Search: SerpAPIData Visualization: Plotly⚙️ Setup and InstallationFollow these steps to set up and run the project on your local machine.1. Clone the Repositorygit clone https://github.com/DhairyaGoel05/-AI-Powered-Career-Guidance-Platform.git
cd -AI-Powered-Career-Guidance-Platform

2. Create a Conda EnvironmentIt's recommended to use a Conda environment to manage dependencies.# Create a new environment with Python 3.10
conda create --name ai_career_env python=3.10

# Activate the environment
conda activate ai_career_env

3. Install DependenciesInstall all the required Python libraries from the requirements.txt file.pip install -r requirements.txt

4. Set Up API KeysYou need to provide your API keys for the application to function.Google API Key: Get your key from Google AI Studio.SerpAPI Key: Get your key from SerpAPI for real-time web search capabilities.The application will prompt you to enter these keys in the sidebar when you run it.▶️ How to Run the ApplicationOnce your environment is set up and you have your API keys, you can launch the application using Streamlit.streamlit run app.py

This will start a local server and the application should automatically open in your web browser.📂 Project StructureHere is a brief overview of the key files in the project:app.py: The main Streamlit application file that handles the user interface, tabs, and user inputs.career_guidance_system.py: The backend logic for the CareerGuidanceSystem class. It initializes the language model, handles API calls, and runs the career analysis.career_chatbot.py: Contains the logic for the CareerChatAssistant, including the Retrieval-Augmented Generation (RAG) setup for the chat interface.requirements.txt: A list of all the Python libraries required for the project.🖼️ More Screenshots(You can add more screenshots here to showcase different parts of your application)Market Analysis View(Placeholder for an image showing the job growth and salary charts)Chat Assistant Interface(Placeholder for an image showing a conversation with the AI chat assistant)
