<p align="center">
  <img src="https://img.shields.io/badge/Suffolk_University-SCM_Program-0a1628?style=for-the-badge&labelColor=c9a84c&color=0a1628" alt="Suffolk University SCM"/>
</p>

<h1 align="center">📋 SCM Content Generator</h1>

<p align="center">
  <strong>AI-powered social media content generator for Suffolk University's Supply Chain Management Program</strong>
</p>

<p align="center">
  <em>Generate LinkedIn posts & Instagram captions from articles — with weekly content planning, auto-research, and one-click publishing.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/No_Install_Required-green?style=flat-square" alt="No Install"/>
  <img src="https://img.shields.io/badge/Works_Offline-blue?style=flat-square" alt="Offline"/>
  <img src="https://img.shields.io/badge/Single_File-orange?style=flat-square" alt="Single File"/>
  <img src="https://img.shields.io/badge/Powered_by-Claude_AI-blueviolet?style=flat-square" alt="Claude AI"/>
</p>

---

## ⬇️ Download

<table>
<tr>
<td align="center" width="50%">

### 🍎 Mac

**[Download for Mac](../../raw/main/index.html)**

1. Click the link above → **Right-click** → **Save As** → save as `SCM-Generator.html`
2. Open the file with **Safari**, **Chrome**, or **Firefox**
3. Go to **Settings** tab → paste your Anthropic API key
4. Start generating!

</td>
<td align="center" width="50%">

### 🪟 Windows

**[Download for Windows](../../raw/main/index.html)**

1. Click the link above → **Right-click** → **Save As** → save as `SCM-Generator.html`
2. **Double-click** the file to open in your default browser
3. Go to **Settings** tab → paste your Anthropic API key
4. Start generating!

</td>
</tr>
</table>

> **💡 Tip:** You can also **[use it online via GitHub Pages](../../)** without downloading — just bookmark the link.

---

## ✨ Features

### 📝 Quick Post Generator
- Paste article text or URL → get a ready-to-post LinkedIn/Instagram summary
- **Strictly grounded** — only summarizes what's in the article, never adds or invents information
- One-click **"Post on LinkedIn"** with pre-filled text
- Auto-copy caption for Instagram

### 📅 Weekly Content Planner
- Enter your **weekly theme, target audience, and content goals**
- AI generates **7 post ideas** (Monday → Sunday)
- Auto-searches for **source articles** via web search
- Generates **all 7 posts** in one batch
- **Daily queue** — open the app each day, click "Post" on today's content
- Posts auto-delete after **30 days** to save storage

### ⚙️ Self-Training Settings
- **Writing style** — describe the tone you want
- **Post format** — bullet points vs paragraphs, structure preferences
- **Post length** — control how long posts should be
- **Example post** — paste a sample to match its style
- **Things to avoid** — blacklist specific words or patterns

### 📚 Reference Library
- Save example LinkedIn & Instagram posts as style references
- Referenced posts are injected into AI prompts for consistent voice

### 📜 Post History
- Last 50 generated posts saved automatically
- Click any past post to reload and reuse

---

## 🔑 Setup

You need an **Anthropic API key** to use this tool:

1. Go to [console.anthropic.com](https://console.anthropic.com/) and create an account
2. Generate an API key (starts with `sk-ant-...`)
3. Open the app → **Settings** tab → paste your key → **Save**

> Your API key is stored **only in your browser's local storage**. It is never sent anywhere except directly to Anthropic's API.

---

## 🛠 Technical Details

| Spec | Detail |
|---|---|
| **Architecture** | Single HTML file, zero dependencies |
| **AI Model** | Claude Haiku (claude-haiku-4-5-20251001) |
| **API** | Anthropic Messages API with streaming |
| **Storage** | Browser localStorage (settings, history, references, plans) |
| **Compatibility** | Chrome, Edge, Firefox, Safari (Mac & Windows) |
| **Internet** | Required only for AI generation; all data stored locally |

---

## 📄 License

Built for Suffolk University's Supply Chain Management Program.

---

<p align="center">
  <sub>Made with ❤️ for Suffolk University SCM</sub>
</p>
