# Telegram AI Bot — Render

## Files
- bot.py — Telegram + OpenRouter bot
- requirements.txt — Python dependencies
- render.yaml — Render worker configuration

## Render setup
1. Upload these files to a GitHub repository.
2. Create a Render Background Worker from that repository.
3. Add Environment Variables:
   TELEGRAM_BOT_TOKEN = your BotFather token
   OPENROUTER_API_KEY = your OpenRouter key
   OPENROUTER_MODEL = openrouter/free
4. Deploy.

Never put either secret directly into GitHub or the Python file.

## Telegram
For messages to be received reliably, test the bot in a group/discussion chat first.
For a channel, add the bot as an administrator with the required posting permissions and configure the channel's discussion/comments if you want users to ask questions and receive replies there.

Note: Render's availability/pricing can change. The bot is configured as a Worker because it continuously runs Telegram polling.
