# 🕷️ SEO Spider

> A powerful, cross-platform desktop SEO crawler — built with Electron + FastAPI + Playwright.  
> Crawl any website, audit 20+ SEO signals, visualise your internal link graph, and export everything to Excel in one click.

---

## ✨ What It Does

SEO Spider gives you a Screaming-Frog-style audit experience as a self-contained desktop app — no subscription, no cloud, no limits.

Enter a URL, hit **Start**, and watch it crawl in real time. When it's done you get a full SEO report, internal link map, inlinks breakdown, and (optionally) your Google Search Console data merged right in.

---

## 🎬 Demo

> https://github.com/nawanirakshit/SEO-Crawler-Public/blob/main/demo.mov

---

## 📋 Features

| Category | What's included |
|---|---|
| 🕷️ **Crawler** | Async multi-threaded crawl with live WebSocket progress |
| 🌐 **JS Rendering** | Full Chromium rendering via Playwright — SPA-friendly |
| 📊 **SEO Audit** | 20+ checks across titles, meta descriptions, H1s, canonicals, redirects, indexability, structured data, and more |
| 📈 **PageRank** | Internal PageRank calculation on the full link graph |
| 🔗 **Link Analysis** | Internal link graph, inlinks per page, anchor text audit |
| 🖼️ **Image Audit** | Alt text, file size (>100 KB), missing dimension attributes |
| 📂 **GSC Merge** | Upload a Google Search Console export to enrich crawl data with clicks, impressions, and position |
| 📁 **Excel Export** | One-click export: SEO audit sheet, internal pages, inlinks, GSC data |
| ⚙️ **Settings** | Crawl depth, concurrency, JS toggle, custom headers, basic auth, robots.txt respect |
| 🔴 **Live UI** | Status bar with crawled / errors / HTML / images counts updated in real time |

---

## 🔧 Tech Stack

| Layer | Technology |
|---|---|
| Desktop shell | Electron 34 |
| Backend API | FastAPI + Uvicorn |
| JS Rendering | Playwright (Chromium) |
| Crawler | aiohttp + BeautifulSoup4 |
| Reports | pandas + openpyxl |
| Packaging | PyInstaller + electron-builder |
| CI/CD | GitHub Actions |

## 📄 License

MIT — see [LICENSE](LICENSE) for details.
