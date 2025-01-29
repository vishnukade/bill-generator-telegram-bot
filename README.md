# Telegram Bill Generator Bot

## Overview
This is a Telegram bot that helps generate billing PDFs based on user inputs. The bot interacts with users via Telegram, collects necessary billing details through a Google Form, and then generates a bill in PDF format.

## Features
- Choose a billing template (Bramhadev or Ganesh)
- Get a Google Form link to enter billing details
- Automatically generate a PDF bill upon form submission
- Sends the generated PDF directly to the user

## Requirements
Make sure you have the following dependencies installed:
```
python-telegram-bot
python-docx
nest-asyncio
libreoffice
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/telegram-bill-generator.git
   cd telegram-bill-generator
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the bot:
   ```bash
   python main.py
   ```

## Configuration
- Replace `bot_token` in `main.py` with your Telegram bot token.
- Update Google Form links in the bot's responses.

## Deployment on PythonAnywhere
1. Install LibreOffice:
   ```bash
   sudo apt install libreoffice
   ```
2. Set up a web app and configure the bot to run persistently.

## Usage
- Start the bot using `/start` command.
- Select a billing template.
- Fill in the Google Form received.
- Receive a PDF bill after submission.
