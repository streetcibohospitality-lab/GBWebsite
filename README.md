# 🐒 Grub Monkeys — Website

> 1960s-inspired American diner. Bangalore, India.  
> Live site built with plain HTML, hosted on Vercel, source on GitHub.

---

## 🔗 Live Links

| What | Link |
|------|------|
| Live Website | `https://www.https://grubmonkeys.in/` |
| GitHub Repo | `https://github.com/streetcibohospitality-lab/GBWebsite` |
| Vercel Dashboard | `https://vercel.com/grubmonkeys/grubmonkey` |


---

## 🔐 Login Details

> ⚠️ Keep this file **private**. Do not make this README public if it contains real passwords.  
> Tip: move credentials to a private `.env` file or a password manager like 1Password / Bitwarden.

### GitHub
| Field | Value |
|-------|-------|
| Username | `streetcibohospitality@gmail.com ` |
| Email | ` streetcibohospitality@gmail.com` |
| Password | ` Streetcibo@2023` |
| 2FA | ` ` |

### Vercel
| Field | Value |
|-------|-------|
| Login method | ` login with email ` _(GitHub OAuth / Email)_ |
| Email | `streetcibohospitality@gmail.com ` |
| Password | `Streetcibo@2023 ` |
| Team / Org name | ` ` |

### Domain Registrar _(if applicable)_
| Field | Value |
|-------|-------|
| Registrar | ` GoDady ` _(GoDaddy / Namecheap / etc.)_ |
| Login email | `streetcibohospitality@gmail.com ` |
| Password | ` Streetcibo@2023` |
| Domain name | `grubmonkeys.in` |

---

## 📁 Repo Structure

```
grubmonkeys-website/
│
├── index.html       https://grubmonkeys.in/
└── README.md        ← this file
```

### Planned (add when ready)
```
├── assets/
│   └── images/
│       ├── logo/         ← logo-icon.png
│       ├── hero/         ← hero-bg.jpg
│       ├── about/        ← diner-interior.jpg
│       └── food/
│           ├── burgers/
│           ├── chicken/
│           ├── seafood/
│           ├── drinks/
│           └── sides/
```

---

## 🚀 How to Make Changes

This is the full workflow every time you want to update the site:

1. Go to your GitHub repo
2. Click `index.html` → click the **pencil icon** (Edit)
3. Make your changes
4. Scroll down → click **Commit changes**
5. Vercel detects the commit and **auto-deploys in ~30 seconds**
6. Check the live site to confirm

> No terminal, no build steps, no manual deploys needed.

---

## 🔄 Vercel ↔ GitHub Connection

- Vercel is connected to the `main` branch of this repo
- Every push to `main` triggers an automatic redeploy
- To check deploy status: Vercel Dashboard → your project → **Deployments** tab
- To roll back: click any previous deployment → **Promote to Production**

---

## 🎨 Brand Identity (Quick Reference)

| Token | Value | Usage |
|-------|-------|-------|
| Monkey Red | `#EB0000` | CTAs, highlights, primary |
| Monkey Teal | `#00DDC2` | Accents, hover states |
| Gorta Grey | `#3A3A3A` | Text, dark backgrounds |
| Gorta White | `#F0EFE9` | Page backgrounds, cards |
| Hero Font | **Jaro** | Headlines, buttons, nav |
| Body Font | **Lexend** | Descriptions, body copy |

---

## 📸 Adding Photos (When Ready)

1. Create the folder structure under `assets/images/` in GitHub
2. Upload your photos with these exact filenames:

| Photo | Path in repo |
|-------|-------------|
| Logo icon | `assets/images/logo/logo-icon.png` |
| Hero background | `assets/images/hero/hero-bg.jpg` |
| Diner interior | `assets/images/about/diner-interior.jpg` |
| Burger (gallery 1) | `assets/images/food/burgers/gallery-burger-1.jpg` |
| Burger (gallery 2) | `assets/images/food/burgers/gallery-burger-2.jpg` |
| Fried chicken | `assets/images/food/chicken/gallery-chicken-1.jpg` |
| Seafood | `assets/images/food/seafood/gallery-seafood-1.jpg` |
| Shake | `assets/images/food/drinks/gallery-shake-1.jpg` |
| Fries | `assets/images/food/sides/gallery-fries-1.jpg` |

> Photos load automatically once the filename matches. Missing photos show a branded placeholder — the site won't break.

---

## 📋 To-Do

- [ ] Add real address to Contact section in `index.html`
- [ ] Add real phone number
- [ ] Add Google Maps link
- [ ] Connect contact form to Formspree / EmailJS
- [ ] Upload food photos
- [ ] Upload logo icon
- [ ] Connect custom domain `grubmonkeys.in` on Vercel
- [ ] Update live URL in this README

---

## 👥 Team Notes

| Role | Name | Contact |
|------|------|---------|
| Owner | ` ` | ` ` |
| Developer | ` ` | ` ` |
| Designer | ` ` | ` ` |

### For the developer
- Single file site — all HTML, CSS, and JS lives in `index.html`
- No framework, no build tools, no npm — edit and commit directly
- Fonts loaded from Google Fonts CDN (Jaro + Lexend)
- Brand colors defined as CSS variables at the top of the `<style>` block
- Menu tabs use a simple `switchTab()` JS function at the bottom of the file
- All image slots have `onerror` fallbacks — safe to deploy before photos are ready

---

## 📞 Support

| Service | Support Link |
|---------|-------------|
| Vercel | https://vercel.com/support |
| GitHub | https://support.github.com |
| Google Fonts | https://fonts.google.com |
