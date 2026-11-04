# Never publish these in this repository

This file is a reminder for anyone maintaining this public overview.

Do not add:

- `.env` files or any file containing tokens, secrets, passwords, or API keys
- Phone Number IDs, business account IDs, app secrets, or verify tokens
- Source code for the bot, webhook, or dashboard
- Customer phone numbers, names, tickets, or message contents
- Session/auth folders, database files, or deployment credentials

If a secret is ever pushed by mistake, revoke/rotate it immediately — deleting the file in a later commit does not remove it from Git history.
