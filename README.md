# Allez! 🇫🇷

A minimalist, AI-powered French vocabulary and pronunciation learning app.

## Features

- **Spaced Repetition (SRS)**: Study flashcards with smart interval scheduling (SM-2).
- **AI Enrichment**: Automatically generates translations, IPA phonetics, example sentences, and memory tricks for any French word.
- **Pronunciation Coach**: Listen to native French audio, record your voice, and get AI feedback.
- **Multi-Provider AI**: Supports Google Gemini, Anthropic Claude, Groq, and OpenRouter.

## Quick Start

> **Note**: A local HTTP server is required because modern browsers block microphone recording and API calls when opening files directly (`file://`).

1. **Start a local web server** in the project folder:
   ```bash
   # Using Node.js
   npx serve .

   # Or using Python 3
   python3 -m http.server 3000
   ```

2. **Open the app** in your browser at `http://localhost:3000`.

3. **Set up AI Features**:
   - Go to **Settings** (⚙️ icon in top navigation).
   - Select your preferred provider (**Google Gemini**, **Anthropic**, **Groq**, or **OpenRouter**).
   - Paste your API key and click **Save Key** *(saved locally in your browser)*.
