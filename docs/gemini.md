Sure! Here's a Markdown-formatted installation guide for the [Gemini CLI](https://github.com/google-gemini/gemini-cli/tree/main), the open-source AI agent that brings the power of Gemini directly into your terminal:

```markdown
# 🚀 Gemini CLI Installation Guide

Gemini CLI is a terminal-first AI agent that connects you to Gemini models with powerful built-in tools and integrations.

## 📦 Quick Installation

### Run Instantly (No Installation Required)
```bash
npx https://github.com/google-gemini/gemini-cli
```

### Install Globally with npm
```bash
npm install -g @google/gemini-cli
```

### Install with Homebrew (macOS/Linux)
```bash
brew install gemini-cli
```

## 🛠️ System Requirements
- Node.js version **20 or higher**
- Compatible with **macOS**, **Linux**, or **Windows**

## 🔄 Release Channels

| Channel   | Description                                      | Install Command                                      |
|-----------|--------------------------------------------------|------------------------------------------------------|
| Stable    | Fully vetted weekly release                      | `npm install -g @google/gemini-cli@latest`          |
| Preview   | Early access to upcoming features                | `npm install -g @google/gemini-cli@preview`         |
| Nightly   | Latest changes from `main` branch (experimental) | `npm install -g @google/gemini-cli@nightly`         |

## 🔐 Authentication Options

### Option 1: OAuth Login (Recommended)
```bash
gemini
# Follow browser authentication flow
```

Set your Google Cloud Project if using a paid license:
```bash
export GOOGLE_CLOUD_PROJECT="YOUR_PROJECT_NAME"
```

### Option 2: Gemini API Key
```bash
export GEMINI_API_KEY="YOUR_API_KEY"
gemini
```

### Option 3: Vertex AI (Enterprise)
```bash
export GOOGLE_API_KEY="YOUR_API_KEY"
export GOOGLE_GENAI_USE_VERTEXAI=true
gemini
```

## 📖 Documentation
- [Quickstart Guide](https://github.com/google-gemini/gemini-cli/tree/main)
- [Authentication Setup](https://github.com/google-gemini/gemini-cli/tree/main)
- [Configuration Guide](https://github.com/google-gemini/gemini-cli/tree/main)
- [Commands Reference](https://github.com/google-gemini/gemini-cli/tree/main)

---

Built with ❤️ by Google and the open source community.
```

Let me know if you'd like a version tailored for a specific OS or deployment environment!