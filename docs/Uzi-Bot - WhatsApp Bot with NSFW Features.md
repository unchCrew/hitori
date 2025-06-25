# Uzi-Bot - WhatsApp Bot with NSFW Features

This is an improved version of the WhatsApp bot, now named Uzi-Bot, with added NSFW features and multi-platform compatibility.

## Features:
- **WhatsApp Web Latest Version Support:** Updated to work with the latest WhatsApp Web.
- **NSFW Features:**
  - Gelbooru: `.gelbooru <tags>` (e.g., `.gelbooru loli,cat_ears`)
  - Xvideos: `.xvideos <query>` (Currently a placeholder, requires paid API or complex scraping)
  - XNXX: `.xnxx <query>` (Currently a placeholder, requires Python script execution)
  - Rule34: `.rule34 <tags>` (Currently a placeholder, requires Python script execution)
- **YouTube Downloader (YTDL):** Existing functionality is maintained.
- **Multi-platform Compatibility:** Can be run on Termux, Ubuntu, SSH, etc.
- **Customizable Menu:** Updated menu list to include new NSFW commands.

## Installation and Usage:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/unchCrew/hitori.git
    cd hitori
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run the bot:**
    ```bash
    node index.js
    ```

4.  **Scan the QR code:**
    The bot will display a QR code in the terminal. Scan it with your WhatsApp app to link the bot.

## Important Notes:
-   The Xvideos, XNXX, and Rule34 features are currently placeholders. Implementing them fully requires either a paid API subscription (for Xvideos) or custom Python scripts (for XNXX and Rule34). These are beyond the scope of this current update but the commands are in place.
-   Ensure your environment has `ffmpeg` installed for video processing (e.g., YTDL features).

## Contributing:
Feel free to contribute to further improve Uzi-Bot!

