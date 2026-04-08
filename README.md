# 💼 Job Application Tracker

A clean, minimal, single-file job tracker to manage your entire job search — applications, recruiter calls, interview dates, follow-ups, and more. Built with vanilla HTML/CSS/JS. Zero dependencies. Works offline.

**[Live Demo →](https://harshalkumar-ishi.github.io/job-tracker/)**

---

## Features

- Track applications with status: Applied → Screening → Interview → Offer → Rejected
- Log recruiter name, contact, and call date
- Schedule and track interview date & time (highlights upcoming interviews)
- Record follow-up actions taken
- Filter by status and source (LinkedIn, Naukri, Indeed, Referral, etc.)
- Search across company, role, and recruiter
- Export all data to CSV
- All data stored locally in your browser (localStorage) — nothing leaves your device
- Responsive — works on mobile too

---

## Getting Started

### Run locally

Just open the file in any browser — no server needed:

```bash
git clone https://github.com/harshalkumar-ishi/job-tracker.git
cd job-tracker
# Open index.html in your browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

### Host on GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your tracker will be live at `https://<your-username>.github.io/job-tracker/`

---

## Usage Tips

- **Log every application the day you apply** — don't let them pile up
- Use the **Follow-up** field to note your last action (e.g. "Sent reminder Apr 7, no reply yet")
- Interview dates highlighted in **amber** = happening within the next 7 days
- Use **Export CSV** periodically as a backup

---

## Tech Stack

- Pure HTML5, CSS3, JavaScript (ES6+)
- Google Fonts: DM Sans + DM Mono
- localStorage for persistence
- Zero build tools, zero frameworks

---

## License

MIT — free to use and modify.
