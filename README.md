# 📡 JobRadar — AI Job Hunt Automation

> Paste any job description → get a tailored cover letter, email, LinkedIn message & follow-up in 10 seconds.  
> 100% free. Runs entirely in your browser. No sign-up. No data stored on any server.

**[🚀 Live Demo →](https://yourusername.github.io/jobradar)**

---

## What It Does

| Feature | Description |
|---------|-------------|
| 🔍 **Smart Job Fetch** | Enter keywords → AI finds relevant jobs + opens 5 job boards (Naukri, LinkedIn, Foundit, Indeed, Shine) with your filters pre-applied |
| ⚡ **10-Second Applications** | Click any job → AI generates a tailored cover letter, email, LinkedIn message, and follow-up using YOUR profile |
| 📋 **Paste Any JD** | Copy a job post from anywhere → paste it → get a full application instantly |
| 📧 **One-Click Gmail** | Opens Gmail with subject and body pre-filled — just hit Send |
| 📊 **Application Tracker** | Kanban pipeline (Saved → Applied → Screening → Interview → Offer) with CSV export |
| 💾 **Saves Your Data** | Profile and tracker saved in your browser — works across sessions |

---

## Screenshots

*(Add screenshots here after setup)*

---

## Getting Started

### Step 1 — Get a Free Google Gemini API Key (No Credit Card)

1. Go to **[aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)**
2. Sign in with your **Gmail account** (that's it — no payment needed)
3. Click **"Create API Key"** → **"Create API key in new project"**
4. Copy the key (starts with `AIzaSy...`)
5. Paste it into JobRadar's setup screen

**Gemini free tier limits:** 15 requests/minute, 1 million tokens/day — more than enough for a full job hunt.

### Step 2 — Open JobRadar

Option A — **Use the live version**: [yourusername.github.io/jobradar](https://yourusername.github.io/jobradar)

Option B — **Run locally**:
```bash
# No installation needed — just open the file
# Download index.html → double-click to open in Chrome/Firefox
```

### Step 3 — Enter Your API Key

Paste your `sk-ant-...` key on the setup screen. It's stored only in your browser's `localStorage` — never sent anywhere except Anthropic's API directly.

### Step 4 — Set Your Profile

Go to **Profile tab** → fill in your name, skills, target roles, location, summary. The more detail you add, the better the AI tailors your applications.

---

## How to Use (Daily Workflow)

```
1. Hunt Tab → pick keywords → click Fetch Jobs
   ↳ 5 job boards open in new tabs with your keywords pre-filtered
   ↳ AI generates scored job listings for reference

2. Click ⚡ Apply on any job
   ↳ Cover letter, email, LinkedIn message, follow-up generated in ~5 seconds

3. Click "Open in Gmail" → send email
   ↳ Subject and body are pre-filled — just click Send

4. Click "Mark Applied" → job moves to Tracker

5. Repeat daily. Target 10-15 applications/week.
```

---

## Important: What This Tool Can and Can't Do

✅ **What it does:**
- Generates perfectly tailored application content in seconds
- Opens real job boards with your searches pre-applied
- Tracks your entire job hunt pipeline
- Exports everything to CSV

❌ **What it can't do:**
- Auto-submit applications on Naukri/LinkedIn (they block this — doing so risks an account ban)
- Scrape live job listings directly (job boards block browser scraping via CORS)

The workflow is: **AI writes everything instantly → you click Submit on the job board.** This takes ~2 minutes per application vs 20+ minutes manually.

---

## Tech Stack

- Pure HTML + CSS + JavaScript (single file, no framework, no build step)
- **Google Gemini API** — free tier, no credit card, just a Gmail account
- Browser `localStorage` for data persistence
- No backend, no database, no server costs ever

---

## Privacy

- Your API key is stored in your browser's `localStorage` only
- Your profile data never leaves your device
- The only external call made is to Anthropic's API (`api.anthropic.com`) — directly from your browser
- No analytics, no tracking, no ads

---

## Roadmap

- [ ] Chrome Extension (read JD directly from the page)
- [ ] Multiple resume profiles
- [ ] Email follow-up scheduler
- [ ] Job board integrations (when APIs become available)
- [ ] Export applications as PDF

---

## Contributing

Pull requests welcome. If you find a bug or have a feature idea, open an issue.

---

## License

MIT — free to use, modify and share.

---

*Built by [Ravi Mishra](https://linkedin.com/in/ravimishhra) · Noida, India*  
*If this helped your job search, consider starring the repo ⭐*
