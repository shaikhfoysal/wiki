# 📚 Wiki Demo (Tailwind + Vanilla JS)

A lightweight, responsive wiki-style documentation interface built using **Tailwind CSS** and **Vanilla JavaScript**.  
This project demonstrates how to create a simple documentation system with navigation, search, and markdown rendering — all in a single HTML file.

---

## 🚀 Features

- 📂 Nested sidebar navigation
- 🔍 Live search filtering for topics
- 📝 Markdown-based content rendering
- 📋 Copy-to-clipboard for code snippets
- 🎨 Clean UI with Tailwind CSS
- ⚡ Smooth panel transitions and animations
- 📱 Fully responsive (mobile-friendly sidebar toggle)

---

## 📸 Preview

> Simple wiki interface with sidebar navigation and content panels.

---

## 🛠️ Tech Stack

- **HTML5**
- **Tailwind CSS (CDN)**
- **Vanilla JavaScript**

---

## 📂 Project Structure

---

## ⚙️ How It Works

### 1. Navigation System
- Sidebar contains grouped topics
- Clicking a topic switches content panels dynamically
- Active state is managed via JavaScript

### 2. Markdown Rendering
- Markdown content is stored in `data-markdown` attributes
- A custom `markdownToHtml()` function converts it to HTML

### 3. Search Feature
- Filters sidebar topics in real-time
- Automatically expands matching groups

### 4. Copy Code Snippets
- Click "Copy" button to copy code blocks
- Uses `navigator.clipboard`

---

## ▶️ Getting Started

### Option 1: Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/wiki-demo.git
