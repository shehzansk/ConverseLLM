# ConverseLLM Chrome Extension

<p align="center">
  Seamlessly integrate ConverseLLM into Google Chrome.
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#installation">Installation</a> •
  <a href="#development">Development</a> •
  <a href="#usage">Usage</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a>
</p>

## Features

- 🔗 Connect to your ConverseLLM instance with a simple connection string or automatic browser extension registration
- 📑 Save selected text to ConverseLLM directly from any webpage
- 📄 Upload entire web pages to ConverseLLM for processing
- 🗂️ Embed content into specific workspaces
- 🔄 Automatic logo synchronization with your ConverseLLM instance

## Installation

1. Clone this repository or download the latest release.
2. Open Chrome and navigate to `chrome://extensions`.
3. Enable "Developer mode" in the top right corner.
4. Click "Load unpacked" and select the `dist` folder from this project.

## Development

To set up the project for development:

1. Install dependencies:

   ```
   yarn install
   ```

2. Run the development server:

   ```
   yarn dev
   ```

3. To build the extension:
   ```
   yarn build
   ```

The built extension will be in the `dist` folder.

## Usage

1. Click on the ConverseLLM extension icon in your Chrome toolbar.
2. Enter your ConverseLLM browser extension API key to connect to your instance (or create the API key inside AnythingLLM and have it automatically register to the extension).
3. Right-click on selected text or anywhere on a webpage to see ConverseLLM options.
4. Choose to save selected text or the entire page to ConverseLLM.


Copyright © 2024 [Vedant Kohad](https://github.com/kohadved). <br />
This project is [MIT](../LICENSE) licensed.
