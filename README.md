# SoftBot-AI-Campus-Assistant-
SoftBot is an AI-powered campus assistant built using Python, Streamlit, LangChain, LangGraph, and the Groq API. It helps students with common campus-related queries such as fees, hostel, library, exams, and Wi-Fi while also performing calculations and word counting using built-in tools.

The chatbot uses a ReAct Agent architecture with LangGraph MemorySaver, allowing it to remember conversations within the same session. It routes requests to the appropriate tool, executes the task, and displays a transparent “How I got this” trace so users can understand how each answer was generated.

✨ Features

* AI-powered campus assistant
* Conversation memory using LangGraph
* ReAct Agent with tool calling
* Campus handbook search
* Calculator tool
* Word count tool
* “How I got this” reasoning trace
* Interactive Streamlit interface
* Powered by Groq Llama models

🛠️ Tech Stack

* Python
* Streamlit
* LangChain
* LangGraph
* Groq API
* python-dotenv

📁 Project Structure

SoftBot/
│── app.py
│── step6_softbot.py
│── requirements.txt
│── .gitignore
│── README.md
│── .env (not uploaded)

⚙️ Installation

git clone https://github.com/Tushar1752/SoftBot-AI-Campus-Assistant-.git
cd SoftBot
python -m venv venv
# macOS/Linux
source venv/bin/activate
# Windows
venv\Scripts\activate
pip install -r requirements.txt

Create a .env file:

GROQ_API_KEY=your_groq_api_key

Run the application:

streamlit run app.py

🚀 Example Questions

* What is the semester fee?
* What do 4 semesters cost?
* What are the hostel charges?
* How many words are in this paragraph?
* Tell me the library timings.

🔮 Future Improvements

* Multiple chat sessions
* File upload support
* Voice assistant
* Database integration
* Authentication
* Conversation export

👨‍💻 Author

Tushar Verma

B.Tech CSE (Artificial Intelligence)

⭐ Support

If you like this project, don’t forget to give it a ⭐ on GitHub.
