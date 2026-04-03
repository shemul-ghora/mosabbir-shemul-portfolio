# Mosabbir Hossain — Cybersecurity Portfolio

A complete, professional cybersecurity portfolio website with hacking/terminal aesthetics.

## ✅ Sections Included

- **Hero** — Terminal-style intro with live matrix background, glitch effect name, animated stats
- **About** — Bio, skill progress bars, tech stack tags
- **Expertise** — 6 core skill cards (Red Team, Web Pentest, SOC, Cloud, AD, OSINT)
- **Blog** — Tabbed Medium + HackToLive blog posts with direct links
- **YouTube** — Channel showcase + recent video list
- **Courses** — 6 courses with pricing (Hack To Live Academy)
- **Hire as Trainer** — 3-tier pricing cards (customizable)
- **Consulting + Calendar** — Service selector + date/time booking system → sends email
- **Community** — Facebook Group, WhatsApp Group/Channel, Discord, LinkedIn (personal + academy)
- **Contact Form** — Sends via email to mosabbirshemul@gmail.com

## 🚀 Deploy to Vercel (3 Steps)

### Option A: Drag & Drop (Easiest — No coding needed)

1. Go to **https://vercel.com** → Sign up / Log in (free)
2. Click **"Add New Project"**
3. Click **"Upload"** and drag the entire `portfolio` folder
4. Click **Deploy** → Your site is live in ~30 seconds!

### Option B: Via GitHub (Best for updates)

1. Create a free account at **https://github.com**
2. Create a new repository called `mosabbir-portfolio`
3. Upload all files from this folder to that repo
4. Go to **https://vercel.com** → "Add New Project" → Import from GitHub
5. Select your repo → Deploy
6. Every time you update files on GitHub, Vercel auto-redeploys ✅

## 🔧 Customizing Your Site

### Update Your Social Media Links
Open `index.html` and search for these placeholders and replace with your real URLs:

```
https://facebook.com/groups/hacktolive     → Your Facebook Group link
https://wa.me/+8801765603356               → Your WhatsApp link
https://discord.gg/hacktolive             → Your Discord invite link
https://youtube.com/@hacktolive           → Your YouTube channel
https://hacktolive.org                    → Your academy website
https://medium.com/@mosabbirshemul        → Your Medium profile
https://linkedin.com/company/hacktolive   → Academy LinkedIn
https://linkedin.com/in/mosabbirshemul    → Personal LinkedIn
```

### Add Your Profile Photo
Replace the `🛡️` emoji in the About section with an actual `<img>` tag:
```html
<img src="your-photo.jpg" style="width:100%;height:100%;object-fit:cover;" alt="Mosabbir Hossain">
```

### Update Course Prices
Search for `৳4,999`, `৳3,999` etc. and change to your actual prices.

### Custom Domain
In Vercel dashboard → your project → Settings → Domains → Add your domain (e.g., mosabbirshemul.com)

## 📁 Files
```
portfolio/
├── index.html      ← Main website (everything is in one file)
├── vercel.json     ← Vercel deployment config
└── README.md       ← This file
```
