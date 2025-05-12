Here's a concise and clear **`README.md`** draft for your GitHub project, describing the purpose and features of the Mermaid viewer you've created:

---

# 🧠 Mermaid Viewer

This project provides an **interactive, enriched viewer** for [Mermaid](https://mermaid-js.github.io/) diagrams rendered in the browser. It supports:

* 📊 **Multiple diagrams** on the same page
* 🔍 **Zoom in/out/reset** and auto-fit to container
* 🖱️ **Click-and-drag panning** within diagrams
* 📺 **Fullscreen toggle** for immersive editing or review
* 📉 **Collapse/expand** each diagram panel
* 🖼️ **Copy diagram as PNG** to clipboard
* 🧩 Lightweight, modular design (HTML + CSS + JavaScript)
* 🌐 CDN-based, no build tools required

> ✅ Built using [Mermaid v10](https://github.com/mermaid-js/mermaid), fully client-side, and portable.

---

## 🚀 Usage

1. Load the HTML file in any modern browser.
2. Add your Mermaid diagram inside a `<div class="mermaid-source">...</div>`.
3. The script auto-converts and wraps it in an interactive viewer.

Example diagram block:

```html
<div class="mermaid-source">
  graph TD
    A[Start] --> B{Is it working?}
    B -- Yes --> C[Great!]
    B -- No --> D[Fix it]
    D --> B
</div>
```

---

## 🧰 Features

* ⛶ Toggle fullscreen per diagram
* 🧭 Drag to scroll large diagrams
* 🔍 Zoom in/out/reset with buttons
* 🔁 Automatically scales to fit container
* 📂 Collapse/expand header bar with state toggle
* 🖼️ Copy rendered SVG to clipboard as PNG (via canvas)
* ⚙️ Designed to support future plugins and customization

---

## 📦 No Dependencies

* Uses [Mermaid](https://cdn.jsdelivr.net/npm/mermaid@10) from CDN
* Works offline after first load (if cached)
* Single self-contained HTML file

---

## 📜 License

MIT License — use freely and adapt for your needs.

---

Would you like to add a screenshot or GIF to show the interactivity in action?
