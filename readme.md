# Sneha Surprise — static site

Files:
- `index.html` — the full single-file site (HTML, CSS, JS).
- `song.mp3` — add the chosen MP3 here (repo root).

## How to deploy on Vercel (recommended)
1. Push this repo to GitHub (or Git provider).
2. Go to https://vercel.com, click "Import Project", choose your repo and follow prompts.
   - Framework: **Other / Static**
   - Build step: none (static)
   - Output directory: `/` (root)
3. Deploy. The site will serve `index.html` and `song.mp3`.

## Quick local test
You can test locally (simple static server). Example using `http-server`:
```bash
# install simple static server (if needed)
npm install -g http-server
# start it in this repo
http-server -c-1
# open http://localhost:8080 in your browser
