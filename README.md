<h1 align="center">
  TikTok Auto Commenter Bot
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Author-L7N-blue?style=flat-square" alt="author">
  <img src="https://img.shields.io/badge/Language-Python-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Status-Working-success?style=flat-square">
</p>

<p align="center">
  A simple TikTok bot that automatically comments on videos using your <strong>Session ID</strong>.
</p>

---

## ⭐ Features

- Automatically fetches user-related videos
- Sends custom comments (Arabic or English)
- Uses TikTok's signature methods: <code>Gorgon</code>, <code>Argus</code>, and <code>Ladon</code>, <code>Khronos</code>
- Stores comments in a JSON file for reuse

---

## ⚙️ Requirements

- Python 3.7+
- Internet connection
- TikTok valid Session ID

---

## 🧪 How It Works

1. The user provides their TikTok `sessionid`
2. The bot fetches video IDs from the TikTok API
3. Random comments are picked from `comments.json`
4. Comments are automatically posted to each video

---

## 📁 Files Structure

```
├── main.py              # Main script to run the bot
├── comments.json        # Stores your custom comments
├── MedoSigner/          # TikTok signature generation (Gorgon, Argus, Ladon, Khronos)
└── README.md            # Project documentation
```

---

## ▶️ Usage

```bash
$ git clone https://github.com/is-L7N/tiktok-auto-commenter.git
$ cd tiktok-auto-commenter
$ pip install -r requirements.txt
$ python main.py
```

---

## ✍️ Author

- [![Telegram](https://img.shields.io/badge/Telegram-PyL7N-0088cc?style=flat-square&logo=telegram)](https://t.me/PyL7N)
- [![GitHub](https://img.shields.io/badge/GitHub-is--L7N-181717?style=flat-square&logo=github)](https://github.com/is-L7N)

---
