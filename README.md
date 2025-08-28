<img src="https://i.ibb.co/RQ28H2p/banner.png" alt="banner">
<h1 align="center"><img src="./dashboard/images/logo-non-bg.png" width="22px"> Goat Bot V2 - Chatbot Messenger (Fixed Version)</h1>

## Introduction

#### Join us in [Messenger Group](https://m.me/j/AbZX5he4yIFsgui_/) 🍪

If you encounter any issues or difficulties, don’t hesitate to ask for assistance here. Our team will help you with any problems you may face.

* For any questions or issues related to this project, feel free to reach out in our support groups.

<p align="center">
  <img align="center" alt="Preview" src="https://i.postimg.cc/Y2XShSm8/86678c65-896a-47fe-8256-3e8e76dd26d6.jpg"/>
</p>

## 📑 Table of Contents

* [📝 Note](#-note)
* [🚧 Requirement](#-requirement)
* [⚙️ Installation](#️-installation)
* [📝 Tutorial](#-tutorial)
* [🔔 Notifications](#-notifications)
* [🆙 Update Guide](#-update-guide)
* [🛠️ Create New Commands](#️-create-new-commands)
* [💭 Support](#-support)
* [📚 Supported Languages](#-supported-languages)
* [📌 Common Problems](#-common-problems)
* [❌ Warning](#-warning)
* [📸 Screenshots](#-screenshots)
* [✨ Copyright](#-copyright)
* [📜 License](#-license)

<hr>

## 📝 Note

* This bot uses a **personal Facebook account** with an [unofficial API](https://github.com/ntkhang03/fb-chat-api/blob/master/DOCS.md) ([Origin](https://github.com/Schmavery/facebook-chat-api)).
* Using this bot may cause your Facebook account to get locked due to spam or suspicious activity.
* ⚠️ **Always use a clone account** (one you’re willing to lose).
* We are **not responsible** for any issues caused by using this bot.

## 🚧 Requirement

* Node.js 16.x [Download](https://nodejs.org/dist/v16.20.0)
* Basic knowledge of **JavaScript, Node.js, and Facebook unofficial API**

## ⚙️ Installation

To set up the bot on your system:

```bash
# 1. Clone the repository
git clone https://github.com/frn-development/Goat-Bot-V2-Fixed.git

# 2. Navigate into the folder
cd Goat-Bot-V2-Fixed

# 3. Install dependencies
npm install

# 4. Start the bot
npm start
```

👉 **Tip:** If you want to run with special modes:

```bash
# Run with Personal-bot core
npm start

# Run with Goat.js mods
npm run start:goat
```

For configuration, check `config.json` file to set your preferences.

## 📝 Tutorial

Tutorial videos are available on YouTube:

* Mobile phone: [https://www.youtube.com/watch?v=grVeZ76HlgA](https://www.youtube.com/watch?v=grVeZ76HlgA)
* VPS/Windows: [https://www.youtube.com/watch?v=uCbSYNQNEwY](https://www.youtube.com/watch?v=uCbSYNQNEwY)

📌 Summary installation guide: [STEP\_INSTALL.md](https://github.com/frn-development/Goat-Bot-V2-Fixed/blob/main/STEP_INSTALL.md)

## 🔔 Notifications

* Click `Watch` → `Custom` → enable `Pull requests` + `Releases` → `Apply`.
* You’ll receive updates whenever a new release is published.

## 🆙 Update Guide

* Phone/Repl: [https://youtu.be/grVeZ76HlgA?t=1342](https://youtu.be/grVeZ76HlgA?t=1342)
* VPS/Computer: [https://youtu.be/uCbSYNQNEwY?t=508](https://youtu.be/uCbSYNQNEwY?t=508)

Or update manually:

```bash
# 1. Pull the latest version
git pull origin main

# 2. Re-install dependencies if needed
npm install

# 3. Restart the bot
npm start
```

## 🛠️ Create New Commands

* Documentation available here: [DOCS.md](https://github.com/frn-development/Goat-Bot-V2-Fixed/blob/main/DOCS.md)

## 💭 Support

* [Discord](https://discord.com/invite/DbyGwmkpVY) (recommended)
* [Facebook Group 1](https://www.facebook.com/groups/goatbot)
* [Facebook Group 2](https://www.facebook.com/groups/goatbot/permalink/493150412403231)
* [Messenger Group](https://m.me/j/AbYrIGusyc0M402z)

❌ **Telegram support is no longer available.**

⚠️ Please don’t DM admins privately — always ask in groups.

## 📚 Supported Languages

Currently supported:

* ✅ English (`en`)
* ✅ Vietnamese (`vi`)

To change language:

* Edit `config.json`
* Customize language files in `languages/`, `languages/cmds/`, `languages/events/`

## 📌 Common Problems

<details>
<summary>📌 Error 400: redirect_uri_mismatch</summary>
<p><img src="https://i.ibb.co/6Fbjd4r/image.png" width="250px"></p>
1. Enable Google Drive API ([Video](https://youtu.be/nTIT8OQeRnY?t=347))  
2. Add URI `https://developers.google.com/oauthplayground` (⚠️ **without trailing slash**) to **Authorized redirect URIs** ([Video](https://youtu.be/nTIT8OQeRnY?t=491))  
3. Select scopes: `https://www.googleapis.com/auth/drive` and `https://mail.google.com/` ([Video](https://youtu.be/nTIT8OQeRnY?t=600))
</details>

<details>
<summary>📌 Error: Invalid domain for site key</summary>
<p><img src="https://i.ibb.co/2gZttY7/image.png" width="250px"></p>
1. Go to [Google reCAPTCHA admin](https://www.google.com/recaptcha/admin)  
2. Add domain `repl.co` (⚠️ not `repl.com`) to **Domains** in reCAPTCHA v2 ([Video](https://youtu.be/nTIT8OQeRnY?t=698))
</details>

<details>
<summary>📌 GaxiosError: invalid_grant, unauthorized_client</summary>
<p><img src="https://i.ibb.co/n7w9TkH/image.png" width="250px"></p>
<p><img src="https://i.ibb.co/XFKKY9c/image.png" width="250px"></p>
<p><img src="https://i.ibb.co/f4mc5Dp/image.png" width="250px"></p>
- If the project is not published in Google Console, the refresh token will expire in 1 week. You’ll need to generate it again. ([Video](https://youtu.be/nTIT8OQeRnY?t=445))
</details>

<details>
<summary>📌 GaxiosError: invalid_client</summary>
<p><img src="https://i.ibb.co/st3W6v4/Pics-Art-01-01-09-10-49.jpg" width="250px"></p>
- Check if you entered the correct Google Project `client_id`. ([Video](https://youtu.be/nTIT8OQeRnY?t=509))
</details>

## ❌ Warning

⚠️ Do **NOT** use the original undergraduate version — it’s outdated and unsafe.

## 📸 Screenshots

📷 Coming soon!

## ✨ Copyright (C)

* Maintained by **FRN Development**
* Based on original work by [ntkhang03](https://github.com/ntkhang03/Goat-Bot-V2)

## 📜 License

This project is licensed under the [MIT License](LICENSE).
