# Telegram Bill Generator Bot

## Overview
This is a Telegram bot that helps generate billing PDFs based on user inputs. The bot interacts with users via Telegram, provide your billing details on the bot chatbox and then with that details bot then generates a bill in PDF format.
## Try the Telegram Bot

Click [here](https://t.me/Busineesss_bill_bot) to start using the bot.

## Features
- Choose a billing template (Bramhadev or Ganesh)
- enter the bill details 
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
```make sure u have the templates(.docx) with the help of that our bot will generate the bill ```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/telegram-bill-generator.git
   cd telegram-bill-generator
   ```
2.  Run the bot:
   ```bash
   python main.py
   ```

## Configuration
- Replace `bot_token` in `main.py` with your Telegram bot token.
- Update template1.docx and template.docx with your template(template should consist placeholders)

## Deployment on PythonAnywhere
1. Install LibreOffice:
   ```bash
   sudo apt install libreoffice
   ```
2. Set up a web app and configure the bot to run persistently.

## Usage
- Start the bot using `/start` command.
- Select a billing template.
- send the billing details as bot asks.
- Receive a PDF bill after submission.
