# The Drafting Room

Luxury bespoke tailoring landing page with invitation-only assessment quiz.

## Features

- **Interactive Assessment Quiz**: 6-question segmentation tool that qualifies prospects into 3 tiers
- **3-Tier Qualification System**:
  - Blueprint Tier: Instant calendar booking
  - Signature Tier: Email capture for review
  - Essential Tier: Waitlist signup
- **Facebook Pixel Integration**: PageView and Lead tracking
- **GoHighLevel Integration**: Calendar booking widget
- **Responsive Design**: Mobile-first, glassmorphism aesthetic
- **Blueprint Grid Texture**: Sophisticated architectural branding

## Tech Stack

- Pure HTML/CSS/JavaScript (no framework)
- Facebook Conversions API ready
- GoHighLevel calendar widget
- Vercel deployment ready

## Deployment

This site is configured for Vercel deployment:

1. Import this repository to Vercel
2. Vercel will auto-detect it as a static site
3. Deploy!

The `index.html` will serve as the root page automatically.

## Project Structure

```
/
├── index.html              # Main landing page
├── privacy-policy.html     # Privacy policy page
├── public/                 # Images and assets
│   ├── hero.webp
│   ├── section-1.png
│   └── logo files
├── vercel.json            # Vercel configuration
└── README.md
```

## Facebook Pixel Events

- **PageView**: Fires on page load
- **Lead**: Fires when user completes assessment and takes action

## Local Development

Simply open `index.html` in a browser or run a local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`

---

© 2024 The Drafting Room. All rights reserved.
