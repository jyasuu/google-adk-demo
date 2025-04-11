# google-adk-demo


```sh
# Create
python -m venv .venv
# Activate (each new terminal)
# macOS/Linux: source .venv/bin/activate
# Windows CMD: .venv\Scripts\activate.bat
# Windows PowerShell: .venv\Scripts\Activate.ps1

pip install google-adk

mkdir multi_tool_agent/
touch multi_tool_agent/__init__.py
touch multi_tool_agent/agent.py
touch multi_tool_agent/.env

echo "from . import agent" > multi_tool_agent/__init__.py

adk web
```