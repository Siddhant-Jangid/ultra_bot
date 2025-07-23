**Apolo: Streamlit Query Bot with Gemini API**

Apolo is a simple web-based query bot built with Streamlit that leverages Google’s Gemini generative AI API. Users can input questions through a friendly UI, and receive AI-generated responses in real time.

*Features*
-> Streamlit-powered interactive web interface  
-> Integration with Google Generative AI (Gemini) via API key  
-> Easy configuration using .env for API credentials  
-> Docker-ready setup for easy deployment  

*Getting Started*
1. Clone the repository.
2. Add your Google API key to the .env file.
3. Install dependencies from requirements.txt or pyproject.toml.
4. Run the app with:
   streamlit run app.py
5. Access the app in your browser at http://localhost:8501.

*Project Structure*
-> app.py: Main Streamlit application.  
-> main.py: Simple entry point script.  
-> requirements.txt, pyproject.toml: Dependency management.  
-> .env: Store your Google API key.  
-> steps.txt: Step-by-step setup and Docker instructions.  
