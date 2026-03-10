# Ukah Daniel Chukwuemeka — Portfolio Website

A professional portfolio website built with **HTML5, CSS3, and Vanilla JavaScript**.

---

## 📁 Folder Structure

```
portfolio/
├── index.html                        ← Main page (entry point)
├── README.md                         ← This file
├── assets/
│   ├── Ukah_Daniel_Resume.pdf        ← Downloadable resume
│   ├── css/
│   │   └── styles.css                ← All styles
│   ├── js/
│   │   └── main.js                   ← All scripts
│   └── images/
│       ├── daniel.jpg                ← Profile photo
│       └── certificates/
│           ├── data_analysis_diploma.jpg
│           ├── virtual_assistant.png
│           ├── research_ethics.jpg
│           ├── step.jpg
│           ├── hackathon.jpg
│           ├── bgs_department.jpg
│           ├── bgs_faculty.jpg
│           └── chief_nnamdi_prize.jpg
```

---

## 🚀 How to Run Locally

1. Simply **open `index.html`** in any modern browser (Chrome, Firefox, Edge).
2. No build tools or server required — it runs entirely in the browser.

---

## 🌐 How to Deploy (Free Hosting Options)

### Option A — GitHub Pages (Recommended, Free)
1. Create a free account at [github.com](https://github.com)
2. Create a new repository named `portfolio` (or `your-name.github.io`)
3. Upload all files maintaining the folder structure
4. Go to **Settings → Pages → Source: main branch → root folder**
5. Your site will be live at: `https://yourusername.github.io/portfolio`

### Option B — Netlify (Free, Drag & Drop)
1. Go to [netlify.com](https://netlify.com) and sign up free
2. Drag the entire `portfolio` folder into the Netlify dashboard
3. Your site is live instantly with a custom URL like `https://daniel-ukah.netlify.app`
4. You can set a custom domain name too

### Option C — Vercel (Free)
1. Go to [vercel.com](https://vercel.com) and sign up with GitHub
2. Import your GitHub repository
3. Vercel deploys it automatically

---

## ✏️ How to Update Content

- **Personal info / text**: Edit `index.html` — each section is clearly labelled with HTML comments
- **Styles / colors**: Edit `assets/css/styles.css` — CSS variables at the top control the color palette
- **Add new certificates**: Drop the image into `assets/images/certificates/` and add a new `.cert-card` block in `index.html`
- **Replace resume**: Replace `assets/Ukah_Daniel_Resume.pdf` with your updated PDF (keep the same filename)

---

## 📬 Making the Contact Form Work

The form currently simulates a submission. To make it actually send emails, integrate one of:

- **[Formspree](https://formspree.io)** — Add `action="https://formspree.io/f/YOUR_ID"` to the `<form>` tag
- **[EmailJS](https://emailjs.com)** — Free plan, JavaScript-based, no backend needed
- **[Web3Forms](https://web3forms.com)** — Very easy setup, free tier available

---

## 🎨 Customisation

| Variable | Location | Purpose |
|---|---|---|
| `--teal` | `styles.css :root` | Accent colour |
| `--gold` | `styles.css :root` | Achievement badges |
| `--font-display` | `styles.css :root` | Heading font |
| `--font-body` | `styles.css :root` | Body font |

---

Built with ❤️ for Ukah Daniel Chukwuemeka
