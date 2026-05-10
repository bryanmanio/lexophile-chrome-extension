<div align="center">
  <img src="icons/icon128.png" alt="Lexophile" width="96" height="96" />

  # Lexophile — Chrome Extension

  **Right-click any word on the web to save it to your Obsidian vault.**

  A companion extension for the [Lexophile Obsidian plugin](https://github.com/bryanmanio/obsidian-lexophile).
</div>

---

## What it does

Highlight a word on any web page, right-click, and choose **Add "&lt;word&gt;" to Lexophile**. The extension fetches the definition and posts it to the Lexophile plugin running locally in Obsidian, where it becomes a permanent dictionary note in your vault.

## Requirements

The [Lexophile Obsidian plugin](https://github.com/bryanmanio/obsidian-lexophile) must be installed and running.

## Installation

The extension is pending Chrome Web Store review. In the meantime, load it unpacked:

1. Open `chrome://extensions` in Chrome.
2. Toggle **Developer mode** on.
3. Click **Load unpacked** and select this folder.
4. Pin the extension to your toolbar.

## Setup

After installing, the extension opens a welcome tab. It auto-generates an API token — copy it and paste it into **Obsidian → Settings → Lexophile → API token**, then click **Test connection**. Once it turns green you're ready.

## Privacy

The only network call the extension makes is to [Free Dictionary API](https://dictionaryapi.dev/) to look up definitions, and to the Lexophile plugin on `localhost`. No analytics, no telemetry, no account.

## License

MIT © [Bryan Maniotakis](https://github.com/bryanmanio)
