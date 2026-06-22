# 🗺️ Malaysia Crime Dashboard

Interactive data visualisation exploring crime trends across Malaysia, built with Vega-Lite.

**[View Live Dashboard →](https://tahiya-c.github.io/Malaysia-crime-dashboard/)**

---

## 📊 What's Inside

- **Time series analysis** of crime rates across multiple years
- **Regional breakdowns** by state across Malaysia
- **Crime category comparisons** across different offence types
- Interactive charts built entirely in Vega-Lite — no backend, runs in the browser

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| [Vega-Lite](https://vega.github.io/vega-lite/) | Declarative visualisation grammar |
| HTML / CSS | Layout and styling |
| GitHub Pages | Hosting |

---

## 📁 Project Structure

```
malaysia-crime-dashboard/
├── index.html       # Main dashboard entry point
├── vega/            # Vega-Lite chart specifications (.json)
└── data/            # Crime dataset (CSV/JSON)
```

---

## 🚀 Running Locally

No install needed — just open `index.html` in a browser.

If charts don't load due to local file restrictions, serve it with Python:

```bash
python -m http.server 8000
# Visit http://localhost:8000
```

---

## 📂 Data Source

Crime statistics sourced from the Royal Malaysia Police (PDRM) and official government datasets covering reported crime rates by state and category across multiple years.

---

## 📄 License

MIT

---

