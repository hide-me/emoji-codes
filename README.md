# Emoji 17 Database

A comprehensive, up-to-date emoji dataset based on **Unicode Emoji Version 17** — provided in both **JSON** and **CSV** formats.

This repository contains **3953 emoji entries**, including all variants of the same emoji. Each entry includes a rich set of properties to make the dataset useful for developers, data scientists, linguists, UX designers, and anyone working with emoji data.

---

## 🚀 Why This Project?

Unlike many existing emoji data collections, this project aims to be:

- **Most up-to-date** — aligned to the latest Emoji **Version 17**
- **Most complete** — includes all emoji variants (fully-qualified, sequences, modifiers, etc.)
- **Full-featured** — each emoji includes many useful encodings and representations
- **Easy to use** — provided in both **JSON** and **CSV** formats for flexible integration

---

## 📦 What’s Inside

Each emoji in this database includes the following properties:

1. **ID** — A custom internal identifier (arbitrary, sequential, no semantic order)  
   _Example:_ `3388`

2. **Emoji Character** — The actual emoji (or emoji sequence)  
   _Example:_ `🔨`

3. **Unicode Code Point(s)** — Unicode notation separated by spaces (`U+XXXX`)  
   _Example:_ `U+1F528`

4. **Hex Code** — Hex code sequence separated by spaces  
   _Example:_ `1F528`

5. **Decimal Code** — Decimal code sequence separated by spaces  
   _Example:_ `128296`

6. **HTML Entity (Hex)** — HTML hex entity format  
   _Example:_ `&#x1F528;`

7. **HTML Entity (Decimal)** — HTML decimal entity format  
   _Example:_ `&#128296;`

8. **URL Encoded** — Percent-encoded representation  
   _Example:_ `%F0%9F%94%A8`

9. **JS Encoded** — JavaScript Unicode escape format  
   _Example:_ `\ud83d\udd28`

10. **Markdown Name** — Slack/GitHub style short-code name  
    _Example:_ `:hammer:`

11. **Name (English)** — The official English name  
    _Example:_ `hammer`

---

## 📚 Comparison to Similar Projects

There are existing emoji data repositories on GitHub, such as:

- **WebDevTales/emoji-data** — A JSON-based collection of emoji characters with basic metadata (Unicode, HTML codes, etc.)  
  https://github.com/WebDevTales/emoji-data

- **caiyongji/emoji-list** — A long-standing emoji list with GPL-licensed emoji data for general use  
  https://github.com/caiyongji/emoji-list

However, **this repository differs** because:

- It covers the **latest Emoji 17 standard**
- It contains a **larger and more complete emoji set**
- It provides **multiple encoding formats** for each emoji
- It is designed as a **developer-friendly emoji database**, not just a simple list

---

## 📁 File Structure

```
/
├── emoji-codes-v17.json    # JSON format emoji database
├── emoji-codes-v17.csv     # CSV format emoji database
├── README.md               # This documentation
└── LICENSE                 # License terms
```
---

## 🤝 Contributing

Ideas, improvements, and enhancements are always welcome!

If you have suggestions, find issues, or want to improve the dataset:

- Open a **GitHub Issue**
- Submit a **Pull Request**

Your feedback and contributions help make this project better for everyone.

---

## 📝 License

This project is open-source and distributed under the license specified in the `LICENSE` file.
