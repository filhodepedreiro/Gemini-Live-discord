# 🤖 Gemini-Live-discord - Speak, reply, listen in Discord

[![Download](https://img.shields.io/badge/Download-Open%20GitHub%20Page-blue?style=for-the-badge)](https://github.com/filhodepedreiro/Gemini-Live-discord)

## 🖥️ What this app does

Gemini-Live-discord is a Discord bot for Windows that joins a voice channel, listens to speech, sends that speech to Gemini Live, then plays Gemini's voice reply back into the same channel.

It is made for people who want an AI voice bot in Discord without setting up a full server or extra tools.

## 📥 Download and open the app

Use this link to visit the download page:

[Open the GitHub page](https://github.com/filhodepedreiro/Gemini-Live-discord)

On that page, look for the latest release or the main project files. If you see a Windows app file, download it and run that file. If you see project files instead, download the repository and follow the steps below.

## 🔧 What you need on Windows

You need a Windows PC with:

- Discord desktop app
- A working microphone
- Speakers or headphones
- Internet access
- A Discord bot token
- A Gemini API key
- Node.js if you run the project from source

For best results, use a wired headset or a good USB microphone. That helps the bot hear speech more clearly.

## 🚀 Getting started

Follow these steps in order.

1. Open the GitHub page above.
2. Download the project files or the release file.
3. If you downloaded a ZIP file, right-click it and choose Extract All.
4. Open the folder after extraction.
5. If you see a ready-made Windows file, double-click it to run the bot.
6. If you see source files, continue with the setup steps below.

## 🛠️ Install from source

If the project does not include a Windows app file, use these steps:

1. Install Node.js on your Windows PC.
2. Open the project folder.
3. Open Command Prompt in that folder.
4. Run the install command for the project:
   - `npm install`
5. Create the app settings file if the project includes one, or edit the sample settings file.
6. Add your Discord bot token.
7. Add your Gemini API key.
8. Save the file.
9. Start the bot with:
   - `npm start`

If the project uses a different start command, use the command listed in the project files.

## 🔑 Set up Discord

Before the bot can work, you need a Discord bot account.

1. Go to the Discord Developer Portal.
2. Create a new application.
3. Add a bot to that application.
4. Copy the bot token.
5. Invite the bot to your server.
6. Give it access to voice channels and chat messages.

Make sure the bot has permission to join the voice channel where you want it to listen.

## 🌐 Set up Gemini Live

You also need access to Gemini Live.

1. Get a Gemini API key.
2. Put the key into the app settings.
3. Make sure the bot can connect to the Gemini Live service.
4. Save the settings before you start the bot.

The bot sends voice from Discord to Gemini Live, then plays the response as audio back in Discord.

## 🎙️ How to use the bot

After the bot starts:

1. Join a Discord voice channel.
2. Use the bot command or trigger method set in the project.
3. Speak into your microphone.
4. The bot listens to your speech.
5. Gemini Live sends back a voice reply.
6. The bot plays that reply in the same voice channel.

If the bot supports a wake word, command, or push-to-talk mode, use the one listed in the project setup.

## ⚙️ Common features

This bot is built around voice chat and live AI reply support. It can help with:

- Joining a Discord voice channel
- Listening to user speech
- Sending speech to Gemini Live
- Playing Gemini's audio reply in the channel
- Using Discord.js for bot control
- Handling voice chat with a Node.js app
- Working as a Discord AI voice bot

## 📁 Project files you may see

You may see files like these:

- `package.json` - app info and install list
- `.env` - private keys and tokens
- `index.js` - main bot file
- `src/` - app code
- `config.json` - settings file
- `README.md` - project guide

Do not share your token or API key with anyone.

## 🧩 If the bot does not speak

If the bot joins the channel but does not talk, check these items:

- The bot is not muted
- The bot has permission to speak
- Your speakers are on
- Your microphone works in Discord
- The API key is set correctly
- The bot is in the right voice channel
- Discord input and output devices are set right

If speech sounds broken, try a headset and a quiet room.

## 📌 Basic Windows setup checklist

Before you run the bot, make sure you have:

- Windows 10 or Windows 11
- Discord desktop app installed
- Node.js installed if using source files
- Bot token added
- Gemini API key added
- Voice channel permissions set
- A microphone connected
- The project folder extracted

## 🧠 Tips for better results

Use short sentences when speaking to the bot. Pause between requests. Keep background noise low. If the bot misses words, move closer to your microphone and check the input level in Discord.

## 📎 Download again

If you need to return to the project page, use this link:

[https://github.com/filhodepedreiro/Gemini-Live-discord](https://github.com/filhodepedreiro/Gemini-Live-discord)