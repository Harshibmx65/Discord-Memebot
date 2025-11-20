# Discord Meme Bot 🤖😂

A simple Discord bot that sends random memes using the Meme API.
Built using discord.py, hosted on Render, and written in Python.

# 🚀 Features

Sends a fresh meme every time you use the command

Uses the public meme-api.com

Easy to deploy and customize

Beginner-friendly code

# 🛠 Tech Stack

Python

discord.py

Requests

JSON

Render (Deployment)

# 📦 Installation
1️⃣ Clone this repository
git clone https://github.com/Harshibmx65/Discord-Memebot.git
cd Discord-Memebot

2️⃣ Install required libraries
pip install -r requirements.txt

⚙️ Setup
1️⃣ Create a Discord Bot

Go to the Discord Developer Portal → Create Bot → Copy the Token.

2️⃣ Enable Intents

Go to Bot section

Turn on Message Content Intent

3️⃣ Add your Bot Token

Inside your code:

client.run("YOUR_BOT_TOKEN")


# ✔ Never push your real token publicly!

▶️ Run Locally
python bot.py

📢 Commands
👉 Send a Meme

Type:

$meme


Bot will reply with a random meme URL.

# ☁️ Deployment (Render)

Upload your project to GitHub

Go to Render → New Web Service

Connect repo

Set:

Runtime: Python

Start Command: python bot.py

Deploy

# 🧩 Project Structure
📁 Discord-Memebot
├── bot.py
├── requirements.txt
└── README.md
