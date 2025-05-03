Step-by-Step Guide to Set Up an OpenAI Agent with Gemini (Using uv)

1. Initialize the Project
   uv init --package hello-agent
2. Open Project in Cursor
3. Open the Terminal
   Terminal > New Terminal
4. Create a Virtual Environment
   uv venv
5. Activate the Virtual Environment
   .venv\Scripts\activate
6. Set the Python Interpreter
   press (Ctrl+shift+p) and (select recommended python interpreter)
7. Add the OpenAI Agents SDK
   uv add openai-agents
8. Create Agent Script
   Inside the src folder, create a new file: agent_hello.py
   Write Agent code in this file.

9. Get Gemini API Key
10. Create a .env File
    In the root of the project folder, create a file named .env.
    Add Gemini API key
11. Add .env to .gitignore
12. Install python-dotenv
    uv add python-dotenv
13. Add the Gemini base_url in Code
14. pyproject.toml Configuration
    Find the pyproject.toml file (created by uv init) and add this scripts:
    hello-agent1 = "hello_agent.agent_hello:my_first_agent"
"# Ass2-Agent" 
