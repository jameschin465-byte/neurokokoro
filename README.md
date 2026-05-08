# NeuroKokoro Landing Page

**By EduMatrix · neurokokoro.edumatrix.asia**

A mobile-first landing page for the NeuroKokoro cognitive brain training program by EduMatrix.
Designed for parents scanning a QR code at live roadshow events.

---

## Deploy to GitHub Pages (5 steps)

### Prerequisites
- A GitHub account (free at github.com)
- Git installed on your computer

### Steps

1. **Create a new GitHub repository**
   - Go to github.com → click the "+" icon → "New repository"
   - Name it: `neurokokoro` (or any name you prefer)
   - Set to Public
   - Do NOT initialize with README (we already have one)
   - Click "Create repository"

2. **Open your terminal and navigate into this folder**
   ```
   cd "/path/to/neurokokoro-site"
   ```

3. **Push to GitHub**
   ```
   git init
   git add .
   git commit -m "Launch NeuroKokoro landing page"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/neurokokoro.git
   git push -u origin main
   ```
   Replace `YOUR-USERNAME` and `neurokokoro` with your actual GitHub username and repo name.

4. **Enable GitHub Pages**
   - On GitHub, go to your repo → **Settings** → **Pages**
   - Under "Source", select: **Deploy from a branch**
   - Branch: **main** | Folder: **/ (root)**
   - Click **Save**

5. **Your page is live!**
   - Wait ~60 seconds, then visit:
     `https://YOUR-USERNAME.github.io/neurokokoro/`
   - Bookmark this URL

---

## Generate Your QR Code

Use any of these free tools to create a QR code from your live URL:
- **qr.io** (recommended — free, no account needed)
- **qrcode-monkey.com** (customisable with logo)
- **goqr.me**

Tip: Use a short URL service like bit.ly to make the QR code less dense and easier to scan.

---

## How to Add an Upcoming Event

1. Open `index.html`
2. Search for: `TO ADD AN EVENT`
3. You will see a commented-out `.event-card` block
4. Copy that block, paste it ABOVE the `.event-placeholder` div
5. Fill in the date, event name, venue, time, and registration link
6. Save, commit, and push to GitHub — your page updates automatically

```html
<!-- Paste this above the .event-placeholder div and fill in details -->
<div class="event-card">
  <div class="event-date">📅  Saturday, 21 June 2025</div>
  <div class="event-title">NeuroKokoro Sharing Session</div>
  <div class="event-venue">📍 Venue Name, Johor Bahru, Malaysia</div>
  <div class="event-time">🕐 10:00am – 1:00pm</div>
  <a href="https://YOUR-REGISTRATION-LINK" class="btn btn-primary" target="_blank" style="margin-top:8px;">Register Now →</a>
</div>
```

---

## Key Links (for quick reference)

| Purpose | URL |
|---|---|
| Contact / Booking | https://hendshake.com/jameschin |
| Facebook | https://www.facebook.com/edumatrixasia |
| Instagram | https://www.instagram.com/edumatrixasia/ |

---

## File Structure

```
neurokokoro-site/
├── index.html              ← The entire landing page
├── README.md               ← This file
└── assets/
    ├── images/             ← All photos and graphics
    └── videos/             ← Parent testimonial videos
```

---

*NeuroKokoro by EduMatrix · Preparing Minds For Life*
