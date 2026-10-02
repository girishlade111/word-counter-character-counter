# Word & Character Counter

A fast, free, privacy-friendly text analysis tool that counts words, characters, sentences, paragraphs, and reading time in real time as you type — all in a single self-contained HTML file.

## Features

- **Real-time word counter** — words update instantly as you type or paste
- **Character count** — with and without spaces
- **Sentence & paragraph counts**
- **Estimated reading time**
- **Progress bars** — visual limits (e.g. green / orange / red zones) so you can stay under a target length
- **Copy to clipboard** and **clear text** buttons
- **Dark mode toggle** (if supported by this version)
- **100% client-side** — no tracking, no cookies, no backend; your text never leaves your browser
- **Single-file build** — just `index.html`, works offline

## Tech Stack

- HTML5, CSS3 (custom properties / variables, responsive layout)
- Vanilla JavaScript (no frameworks, no dependencies)
- Deploys as a static site — GitHub Pages

## Quick Start

```bash
git clone https://github.com/girishlade111/word-counter-character-counter.git
cd word-counter-character-counter
# then open index.html in any browser
```

No build step, no dependencies, no server required.

## Project Structure

```
word-counter-character-counter/
├── index.html   # the entire app (markup + styles + logic)
└── README.md    # this file
```

## Deploy

The site is a static page hosted on GitHub Pages. Any static host works — just serve `index.html`.

## Roadmap Ideas

- Keyword density analysis
- Readability score (Flesch–Kincaid)
- Export stats as text / CSV
- Persistent settings via localStorage

---

Built by Girish Lade — https://ladestack.in
