### \\ Author: W_Wachira 
### Learning outcomes

###  My Agent Architecture - my work agents in ADK
The Conductor (Root Agent)
Takes the user's topic and delegates tasks to the appropriate tools.
The Planner (Loop Agent)
Generates a structured blog outline
based on delegated tasks.
The Writer (Loop Agent)
Takes the structured outline and drafts a full, comprehensive blog post.

### Environment Setup 
Install the dependencies defined in your requirements.txt to equip your local workspace with the Google ADK:
setup virtual env-
pip install uv
pip install google-adk

###  Interact With Virtual Environment
Always install inside your virtual environment when working on a specific project, so that dependencies are isolated from your global Python environment.
python -m pip install --upgrade pip
python -m venv venv\  (you can use this too: *pipenv shell-wraps the folderproject*)
- optional
### Environment setup - this setup w***
python3 -m venv venv    |   python3.11 -m venv .venv
source venv/bin/activate   | source .venv/bin/activate   |  exit
pip install uv
pip install google-adk
pip install python-dotenv*
### Start the ADK Web UI
adk web
python3 agent.py

Virtual Env (venv)

# Python has the built-in venv module for creating virtual environments. 
The parentheses (()) surrounding your venv name indicate that you successfully activated the virtual environment. 
eg... 
(venv) PS>  pip3 --version
(venv) PS>  pip --version

## To leave or deactivate a virtual environment, you can simply run the following command in your terminal:
deactivate

### terminal
git init
git add .
git commit -m "..."
git remote add origin https://github.com/your_username/filename
git push -u origin main(it can bemaster depending on which branch you're @)

### …or push an existing repository from the command line
git remote add origin git@github.com:your_username/BlogWriterAgent.git
git branch -M main
git push -u origin main