# bill-generator-telegram-bot
A Telegram bot that allows users to generate bills in PDF format using predefined templates. Users can choose between Bramhadev and Ganesh templates, fill out a Google Form, and receive the generated PDF directly in the chat.
🚀 Telegram Bill Generator Bot

A Telegram bot that allows users to generate bills in PDF format using predefined templates. Users can choose between Bramhadev and Ganesh templates, fill out a Google Form, and receive the generated PDF directly in the chat.

📌 Features

Supports multiple templates (Bramhadev & Ganesh)

User-friendly input collection via Google Forms

Automatic generation of PDF invoices

Integration with LibreOffice or alternative cloud-based conversion

Sends the PDF invoice directly to the user

🔧 Installation

1️⃣ Clone the Repository

git clone https://github.com/yourusername/telegram-bill-generator.git
cd telegram-bill-generator

2️⃣ Install Required Dependencies

pip install -r requirements.txt

3️⃣ Set Up Your Telegram Bot

Create a bot using BotFather

Get the API token and replace it in main.py

bot_token = "YOUR_TELEGRAM_BOT_TOKEN"

4️⃣ (Optional) Set Up Google Drive API for DOCX to PDF Conversion

If using Google Drive for DOCX to PDF conversion:

Enable Google Drive API at Google Cloud Console

Download credentials.json and place it in the project folder

📜 Usage

1️⃣ Start the Bot

python main.py

2️⃣ Interact with the Bot

Send /start to begin.

Select the template (Bramhadev or Ganesh).

Receive a Google Form link and fill in your details.

Upon form submission, the bot automatically generates the PDF and sends it back.

⚙️ Technology Stack

Python (Telegram Bot API, Google API)

Google Forms & Google Drive API

LibreOffice / CloudConvert API (DOCX to PDF conversion)

📜 License

This project is licensed under the MIT License. Feel free to modify and use it as needed.

🙌 Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

📞 Contact

For any queries or support, reach out:

Telegram: YourTelegramHandle

Email: your.email@example.com

