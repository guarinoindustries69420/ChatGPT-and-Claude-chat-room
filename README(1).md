# ChatRoom · GPT

A minimal, browser-based chat interface for talking to ChatGPT, built as a single HTML file and hosted via GitHub Pages.

## Features

- Stream responses live as they are generated
- Choose from GPT-4o, GPT-4o mini, GPT-4 Turbo, or GPT-3.5 Turbo
- API key is stored in session memory only — never written to disk or sent anywhere except directly to OpenAI
- No backend, no server, no dependencies to install

## Usage

1. Visit the live page at: `https://yourusername.github.io/your-repo-name`
2. Click **SET API KEY** and paste your OpenAI API key
3. Select your preferred model from the dropdown
4. Start chatting

You can get an OpenAI API key at [platform.openai.com/api-keys](https://platform.openai.com/api-keys).

## Privacy

Your API key is held in browser memory for the duration of your session only. Closing or refreshing the tab clears it entirely. No data is collected, logged, or stored by this application.

## Hosting Your Own Copy

1. Fork or download this repository
2. Go to **Settings > Pages** in your GitHub repo
3. Set the source to the `main` branch, root folder
4. GitHub will publish it at `https://yourusername.github.io/your-repo-name`

---

© 2026 [Your Name]. All Rights Reserved. Unauthorized use, copying, or distribution is strictly prohibited.
