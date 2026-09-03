<div align="center">

<img src="assets/extractor-banner.gif" width="100%" alt="Extractor Pro X Animated Banner">

<br><br>

<img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Telegram-BOT-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
<img src="https://img.shields.io/github/stars/princepiamotox/Extractor_Pro_x?style=for-the-badge&logo=github" alt="GitHub Stars">
<img src="https://img.shields.io/github/forks/princepiamotox/Extractor_Pro_x?style=for-the-badge&logo=github" alt="GitHub Forks">

</div>

---

# ⚡ Extractor Pro X

**Extractor Pro X** is a Telegram-based TXT extraction bot built with **Python + Pyrogram**.

### 🔄 Simple Workflow

`📄 TXT File` → `🤖 Telegram Bot` → `⚙️ Processing` → `✅ Result`

---

## ✨ Features

| Feature | Description |
|---|---|
| 📄 TXT Processing | Process TXT files through Telegram |
| 🤖 Telegram Bot | Simple Telegram-based workflow |
| ⚡ Fast Processing | Built for quick file handling |
| 📱 Termux Support | Run on Android with Termux |
| 🐍 Python Powered | Built with Python and Pyrogram |
| 🧩 Modular | Organized project structure |
| 🌐 Flask Server | Includes web-server support |
| 🔧 Configurable | Bot settings can be customized |

---

# 🚀 Termux Installation

### 01 — Update Termux
```bash
pkg update -y && pkg upgrade -y
```

### 02 — Install required packages
```bash
pkg install python git rust clang make pkg-config openssl libffi -y
```

### 03 — Clone the project
```bash
git clone https://github.com/princepiamotox/Extractor_Pro_x.git
```

### 04 — Open the project
```bash
cd Extractor_Pro_x
```

### 05 — Upgrade Python tools
```bash
pip install --upgrade pip setuptools wheel
```

### 06 — Install Maturin
```bash
pip install maturin
```

### 07 — Install dependencies
```bash
pip install -r requirements.txt
```

### 08 — Start the bot
```bash
python -m Extractor
```

---

# ⚙️ Configuration

Configure the required bot values before starting the project.

```text
API_ID
API_HASH
BOT_TOKEN
BOT_USERNAME
OWNER_ID
CHANNEL_ID
CHANNEL_ID2
MONGO_URL
PREMIUM_LOGS
THUMB_URL
```

> 🔐 **Security:** Never publish real API keys, bot tokens, database URLs, or other private credentials in a public repository.

If credentials were previously exposed, revoke/rotate them immediately.

---

# 🧩 Project Structure

```text
Extractor_Pro_x/
│
├── Extractor/
│   ├── core/
│   ├── html_converter/
│   ├── modules/
│   ├── thumbs/
│   ├── __init__.py
│   └── __main__.py
│
├── app.py
├── config.py
├── run.py
├── server.py
├── secure.py
├── requirements.txt
├── Dockerfile
├── Procfile
├── heroku.yml
└── README.md
```

---

# 🛠️ Troubleshooting

### ❌ `main.py` not found

Do not run:
```bash
python main.py
```

Run:
```bash
python -m Extractor
```

### ❌ `pydantic-core` / `maturin` build error

```bash
pkg install rust clang make pkg-config openssl libffi -y
pip install --upgrade pip setuptools wheel
pip install maturin
pip install -r requirements.txt
```

### ❌ Configuration / Syntax Error

```bash
nano config.py
```

Check quotes and configuration values carefully.

---

# 🎬 Full Video Tutorial

<div align="center">

<a href="https://youtu.be/_2RnbRwjfQY">
<img src="https://img.shields.io/badge/▶_WATCH_FULL_TUTORIAL-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch Tutorial">
</a>

<br><br>

**Complete Termux Setup • Installation • Bot Launch**

</div>

---

# 📺 CoreTech AI

<div align="center">

<a href="https://youtube.com/@coretechai">
<img src="https://img.shields.io/badge/SUBSCRIBE_CORETECH_AI-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="CoreTech AI">
</a>

<br><br>

`AI` • `AUTOMATION` • `TELEGRAM` • `TECH`

</div>

---

# ⭐ Support

⭐ Star the repository  
🍴 Fork the project  
📢 Share it with others

---

## 📜 Disclaimer

This project is provided for educational and development purposes.

Use it responsibly and make sure your implementation follows Telegram's rules and applicable laws/policies.

---

<div align="center">

### 💙 Built with Python + Telegram

**CoreTech AI**

</div>
