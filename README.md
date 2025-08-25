🚀 AI-Powered Career Guidance Platform

Welcome to the AI-Powered Career Guidance Platform! This interactive web application leverages the power of Google's Gemini API and LangChain to provide users with personalized career insights, detailed market analysis, and tailored learning roadmaps.
✨ Features
🔍 Career Discovery: Explore a wide range of career paths across different industries like Technology, Healthcare, Business, and Creative fields.

📊 In-Depth Analysis: Get a comprehensive overview of any selected career, including key responsibilities, required skills, and educational background.

📈 Real-Time Market Insights: Analyze current job market trends, salary ranges by experience level, job growth projections, and geographic hotspots for opportunities.

📚 Personalized Learning Roadmaps: Receive a custom-tailored learning plan based on your experience level, with recommended courses, resources, and timelines.

💬 AI Chat Assistant: Engage in a conversation with an AI-powered assistant to ask specific questions about your chosen career path.

👤 User Profile & Skills Assessment: Create a personal profile and rate your skills to receive more tailored recommendations.

🛠️ Tech StackBackend: PythonWeb Framework: StreamlitAI/LLM Orchestration: LangChainLanguage Model: Google Gemini APIWeb Search: SerpAPIData Visualization: Plotly

⚙️ Setup and InstallationFollow these steps to set up and run the project on your local machine.1. Clone the Repositorygit clone https://github.com/DhairyaGoel05/-AI-Powered-Career-Guidance-Platform.git

cd -AI-Powered-Career-Guidance-Platform

2. Create a Conda EnvironmentIt's recommended to use a Conda environment to manage dependencies.# Create a new environment with Python 3.10
conda create --name ai_career_env python=3.10

# Activate the environment
conda activate ai_career_env

3. Install DependenciesInstall all the required Python libraries from the requirements.txt file.pip install -r requirements.txt

4. Set Up API KeysYou need to provide your API keys for the application to function.Google API Key: Get your key from Google AI Studio.SerpAPI Key: Get your key from SerpAPI for real-time web search capabilities.The application will prompt you to enter these keys in the sidebar when you run it.
5. ▶️ How to Run the ApplicationOnce your environment is set up and you have your API keys, you can launch the application using Streamlit.streamlit run app.py

This will start a local server and the application should automatically open in your web browser.

📂 Project StructureHere is a brief overview of the key files in the project:app.py: The main Streamlit application file that handles the user interface, tabs, and user inputs.career_guidance_system.py: The backend logic for the CareerGuidanceSystem class. It initializes the language model, handles API calls, and runs the career analysis.career_chatbot.py: Contains the logic for the CareerChatAssistant, including the Retrieval-Augmented Generation (RAG) setup for the chat interface.requirements.txt: A list of all the Python libraries required for the project.
🖼️ More Screenshots(You can add more screenshots here to showcase different parts of your application)Market Analysis View(Placeholder for an image showing the job growth and salary charts)Chat Assistant Interface(Placeholder for an image showing a conversation with the AI chat assistant)
![WhatsApp Image 2025-08-25 at 19 00 32_957364d8](https://github.com/user-attachments/assets/107c8aab-6a3c-4c05-82db-a365f9357265)
![WhatsApp Image 2025-08-25 at 19 01 00_c859b2b9](https://github.com/user-att
![WhatsApp Image 2025-08-25 at 19 01 36_1f1361f4](https://github.com/user-attachments/assets/d3cd530c-22ef-4804-a432-762b5c94f28e)
achments/assets/790aca80-712c-46ec-bf6d-e1646782620d)
![WhatsApp Image 2025-08-25 at 19 02 12_bb673828](https://github.com/user-attachments/assets/ed889899-43ef-43ae-a291-281095135be4)
![WhatsApp Image 2025-08-25 at 19 02 39_4b6246cb](https://github.com/user-attachments/assets/1e26546a-02a5-47a5-8239-c3c163ba5300)
![WhatsApp Image 2025-08-25 at 19 02 58_9c1e59c7](https://github.com/user-attachments/assets/3424e106-e1e9-4d83-85c6-5687f920e68d)
![WhatsApp Image 2025-08-25 at 19 03 31_8c484a64](https://github.com/user-attachments/assets/d42ec628-5a81-451c-b771-1dc16393e927)
![WhatsApp Image 2025-08-25 at 19 03 59_099fe6e6](https://github.com/user-attachments/assets/765eefa3-04e7-47e8-9032-d1b4603e5516)
![WhatsApp Image 2025-08-25 at 19 04 38_99be9c8c](https://github.com/user-attachments/assets/ee65334e-3cac-43a6-b014-d51b33464dab)
![WhatsApp Image 2025-08-25 at 19 05 03_54adb891](https://github.com/user-attachments/assets/40b13285-515c-4d0f-85d9-5edb813b4f51)
![WhatsApp Image 2025-08-25 at 19 05 57_30ffcae5](https://github.com/user-attachments/assets/95b6b81e-5f09-45e8-9488-3c85e0ba7051)

