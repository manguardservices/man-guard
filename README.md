# Man Guard Security Services UK — Static Website

**Client:** Man Guard Security Services UK Ltd  
**Domain:** https://www.man-guard.co.uk  
**Built by:** FatStar Web Design  
**Type:** Static HTML/CSS/JS — zero dependencies, Vercel-ready

---

## Pages

| File | Route | Page |
|------|-------|------|
| `index.html` | `/` | Home |
| `services.html` | `/how-we-protect-you` | Services Overview |
| `asset-security.html` | `/how-we-protect-you/asset-security` | Asset Security |
| `office-concierge-security.html` | `/how-we-protect-you/office-concierge-security` | Office & Concierge Security |
| `manned-guarding.html` | `/how-we-protect-you/manned-guarding` | Manned Guarding |
| `close-protection.html` | `/how-we-protect-you/close-protection` | Close Protection |
| `security-consultant.html` | `/how-we-protect-you/security-consultant` | Security Consultant |
| `property-management.html` | `/how-we-protect-you/property-management` | Property Management Security |
| `about.html` | `/about` | About Us |
| `jet-set-travel.html` | `/jet-set-travel` | Jet Set Travel |
| `contact.html` | `/contact` | Contact Us |
| `privacy-policy.html` | `/privacy-policy` | Privacy Policy |
| `terms-and-conditions.html` | `/terms-and-conditions` | Terms & Conditions |
| `404.html` | 404 fallback | Not Found |

---

## Deploy to Vercel (Recommended)

### Option A — Via GitHub (Recommended)

1. Push all files to a GitHub repository (public or private)
2. Log in to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repository
4. Framework preset: **Other**
5. Build command: *(leave blank)*
6. Output directory: *(leave blank / root)*
7. Click **Deploy**

Clean URLs are handled automatically by `vercel.json` — e.g. `/about` serves `about.html`.

### Option B — Vercel CLI

```bash
npm i -g vercel
cd /path/to/manguard-site
vercel --prod
```

---

## ⚠️ Before Going Live — Replace Formspree Endpoint

The contact form on `contact.html` uses a **placeholder** Formspree endpoint.

**You must replace it before deployment:**

1. Go to [formspree.io](https://formspree.io) and create a free account
2. Create a new form → copy your form ID (e.g. `xpwzabcd`)
3. Open `contact.html` and find:
   ```
   https://formspree.io/f/YOUR_FORM_ID
   ```
4. Replace `YOUR_FORM_ID` with your actual form ID:
   ```
   https://formspree.io/f/xpwzabcd
   ```
5. Save and redeploy

---

## Tech Stack

- Pure HTML5 / CSS3 / Vanilla JS — no build step required
- Google Fonts: Gilda Display, Libre Franklin, Geist Mono
- Images hosted on Supabase CDN + Unsplash
- Form handling: Formspree (POST)
- Scroll reveal: custom IntersectionObserver
- Mobile nav: custom drawer with accordion submenu

---

## Contact

Man Guard Security Services UK Ltd  
📞 08007 999 200  
📱 07534 980288  
✉ info@man-guard.co.uk  
🌐 www.man-guard.co.uk
