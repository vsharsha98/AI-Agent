# AI-Agent
An AI Agent made on Google's Gemini LLM.
This is a simple AI Agent that takes the prompt through Browser Use WebUI and performs the automation tasks using Play Playwright repository.

Steps :
1. pip3 install browser-use
2. playwright install
3. Create a folder named ai-agent 
4. Go inside the ai-agent folder - cd desktop and go to cd ai-agent
5. Git clone https://github.com/browser-use/web-ui...
6. Go to cd web-ui and install uv - curl -LsSf https://astral.sh/uv/install.sh | sh
7. Clear the command terminal and open it again until web-ui folder
8. Creates an environment - uv venv --python 3.11
9. Activate the env - source .venv/bin/activate
10. uv pip install -r requirements.txt
11.  python webui.py --ip 127.0.0.1 --port 7788
12. You will get the ip and copy and paste the ip
13. Go to Google Studio and get the gemini api and paste into the browser-ui
14. Run Agent
