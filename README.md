## Leech Bot

Telegram bot for downloading videos from educational platforms (YouTube, VisionIAS, Classplus, PW, Google Drive, etc.)

## Deploy on Render

1. Fork this repository
2. Go to [Render.com](https://render.com)
3. Click "New +" → "Web Service"
4. Connect your GitHub repository
5. Configure:
   - **Name**: leech-bot
   - **Environment**: Docker
   - **Dockerfile Path**: ./Dockerfile
   - **Plan**: Free
6. Add Environment Variables:
   - `API_ID` - Your API ID from https://my.telegram.org/apps
   - `API_HASH` - Your API Hash from https://my.telegram.org/apps
   - `BOT_TOKEN` - Your Bot Token from @BotFather
7. Click "Deploy"

## Local Setup

1. Install Python 3.10+
2. Install dependencies: `pip install -r requirements.txt`
3. Edit `config.py` with your credentials
4. Run: `python main.py`
