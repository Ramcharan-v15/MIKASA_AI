# MIKASA_AI

A JARVIS-inspired AI assistant interface built with HTML, CSS, and JavaScript. Deployed on GitHub Pages.

## What It Does

MIKASA_AI is a web-based assistant interface that provides:

- **Chat interface** — text-based interaction with an AI backend
- **Voice input** — speech-to-text using the browser's Web Speech API
- **Quick actions** — one-click shortcuts for YouTube, Gmail, Google, Maps, GitHub, Spotify, WhatsApp
- **System tools** — time/date queries, entertainment commands
- **PowerPoint builder** — presentation creation mode
- **Live status panel** — recent tasks and system status display

The assistant uses **Groq** as its AI backend. Users provide their own free Groq API key through the interface; the key is stored locally in the browser.

## Live Demo

[https://ramcharan-v15.github.io/MIKASA_AI/](https://ramcharan-v15.github.io/MIKASA_AI/)

## Technology

| Component | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| AI Backend | Groq API |
| Voice | Web Speech API |
| Deployment | GitHub Pages |

## Usage

1. Open the [live demo](https://ramcharan-v15.github.io/MIKASA_AI/)
2. Paste your Groq API key in the banner at the top
3. Get a free key at [console.groq.com](https://console.groq.com)
4. Type a message or click the microphone for voice input
5. Use the sidebar for quick actions

## Local Setup

```bash
# Clone the repository
git clone https://github.com/Ramcharan-v15/MIKASA_AI.git

# Open directly in a browser
open index.html
```

No build step or server required — this is a static single-page application.

## Limitations

- Requires a Groq API key for AI responses
- API key is stored in browser localStorage only
- Best experienced on desktop Chrome/Edge for Web Speech API support
- No backend server; all AI requests go directly to Groq

## License

MIT
