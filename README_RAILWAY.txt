RAILWAY HOSTING PACKAGE

Files included:
- hosting.py
- requirements.txt
- Procfile
- railway.toml

Deploy:
1. Upload/push this folder to your GitHub repository.
2. Create a Railway service from the repository.
3. Railway will install requirements.txt automatically.
4. Start command: python hosting.py

IMPORTANT:
The original hosting.py contains a Telegram bot token. Do not publish that token
to GitHub or share it publicly. Revoke/regenerate the exposed token and use a
Railway environment variable for the replacement token after updating the code.
