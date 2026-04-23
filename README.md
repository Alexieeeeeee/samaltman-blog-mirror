# Sam Altman Blog Mirror

A complete static mirror of [blog.samaltman.com](https://blog.samaltman.com) — Sam Altman's personal blog.

## 📊 Stats

- **121 articles** scraped (March 2013 – April 2026)
- **23 images** downloaded locally
- Fully static, zero dependencies

## 🏗️ Structure

```
├── index.html          # Homepage with all posts listed chronologically
├── style.css           # Stylesheet
├── app.js              # Client-side search/filter
├── all_posts.json      # Consolidated post data
├── posts/              # Individual article pages (121 .html files)
└── images/             # Downloaded article images
```

## 🚀 Run Locally

```bash
cd /var/www/samaltman-mirror
python3 -m http.server 8080
# Open http://localhost:8080
```

## 📝 Source

Mirrored from: https://blog.samaltman.com
Scraped via Atom feed: https://blog.samaltman.com/posts.atom

## License

This is a personal archival copy for offline reading. Blog content copyright Sam Altman.
