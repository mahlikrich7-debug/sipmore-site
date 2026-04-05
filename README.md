# Sip More LLC — Website Go-Live Guide
**sipmore.wine**

---

## What's In This Folder

```
sipmore-site/
├── index.html        → Homepage
├── events.html       → Events page
├── services.html     → Services page
├── about.html        → About page
├── contact.html      → Contact / Inquiry page
├── images/
│   ├── logo.png      → Sip More burgundy logo
│   └── mahlik-rich.jpg → About page photo
└── README.md         → This file
```

---

## Before You Go Live — Checklist

Complete these quick swaps in the HTML files before deploying.
Open each file in any text editor (TextEdit on Mac, Notepad on Windows)
and use Find & Replace (Cmd+H / Ctrl+H) to make updates.

### All Pages
- [ ] Replace `hello@sipmore.wine` with your actual email address (if different)
- [ ] Replace `#` in Instagram link with your real IG URL
- [ ] Replace `#` in TikTok link with your real TikTok URL
- [ ] Replace `#` in LinkedIn link with your real LinkedIn URL

### events.html
- [ ] Replace `https://universe.com` links with your real Universe BoxOffice event URLs
      (e.g. `https://universe.com/events/velvet-sessions-xyz`)
- [ ] Swap gallery placeholder frames with real event photos when ready
- [ ] Remove "Video Coming Soon" badges and add video embeds when ready

---

## Step 1 — Deploy to Netlify (Free)

1. Go to **netlify.com** and click "Sign Up" — use your email or Google account
2. Once logged in, you'll see a dashboard with a box that says
   **"Drag and drop your site folder here"**
3. Open Finder (Mac) or File Explorer (Windows), find this `sipmore-site` folder,
   and drag the entire folder into that Netlify box
4. Netlify will deploy in about 30 seconds and give you a temporary URL like:
   `https://random-name-123.netlify.app`
5. Click that URL to confirm everything looks right in a real browser

---

## Step 2 — Connect sipmore.wine to Netlify

### In Netlify:
1. Go to **Site Settings → Domain Management → Add Custom Domain**
2. Type `sipmore.wine` and click Verify
3. Netlify will show you two nameserver addresses — copy them, they look like:
   `dns1.p01.nsone.net`
   `dns2.p01.nsone.net`

### In Squarespace (your domain registrar):
1. Log into Squarespace and go to **Domains**
2. Click on `sipmore.wine`
3. Click **DNS Settings** or **Nameservers**
4. Replace the existing nameservers with the two Netlify gave you
5. Save

### Wait:
- DNS changes take **30 minutes to 2 hours** to fully propagate
- Once done, `sipmore.wine` will load your Netlify site automatically
- Netlify also adds a **free SSL certificate** (the padlock in the browser) automatically

---

## Step 3 — Test on Live Site

Once your domain is connected, check these on your phone and desktop:

- [ ] All five pages load correctly
- [ ] Navigation links between pages work
- [ ] Your photo loads on the About page
- [ ] Logo loads on the Homepage
- [ ] Contact form submits and shows success message
- [ ] Newsletter signup works
- [ ] Universe BoxOffice ticket links open correctly
- [ ] Site looks good on mobile

---

## Making Future Updates

Any time you want to update the site:
1. Make your changes to the HTML files on your computer
2. Go to Netlify → your site → **Deploys**
3. Drag the updated `sipmore-site` folder into the deploy box again
4. Netlify re-deploys in seconds — your live site updates immediately

For bigger changes (new pages, design updates, new events),
reach back out and we can build them the same way we built these.

---

## Pages & What to Update Over Time

| Page | When to Update |
|------|---------------|
| index.html | New events added, stats grow (30+ → 50+, etc.) |
| events.html | New event dates, swap video placeholders, add gallery photos |
| services.html | Pricing adjustments, new add-on services |
| about.html | New credentials, updated bio, new photo |
| contact.html | Email address, social links |

---

## Quick Reference — Files to Edit for Common Tasks

**Add a new event:**
→ Open `events.html`, duplicate an existing event card block and update the text and Universe link

**Update your Instagram link:**
→ Find & Replace `href="#"` near "Instagram" across all files

**Change your email:**
→ Find & Replace `hello@sipmore.wine` across all files

**Update pricing:**
→ Open `services.html`, find the tier price sections and update

---

*Built by Claude for Sip More LLC · sipmore.wine · 2026*
