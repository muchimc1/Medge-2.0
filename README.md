# Medge Marketing Website

**Marketing With An Edge** — official website for Medge Marketing, Lusaka, Zambia.

## 📁 File Structure

```
/
├── index.html        ← Home page
├── about.html        ← About page
├── services.html     ← Services page
├── team.html         ← Team page
├── contact.html      ← Contact page
├── .nojekyll         ← Tells GitHub Pages not to use Jekyll
└── README.md         ← This file
```

## 🚀 Deploying to GitHub Pages

### Step 1 — Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in.
2. Click **New repository**.
3. Name it `medge-website` (or any name you like).
4. Set it to **Public** (required for free GitHub Pages).
5. Click **Create repository**.

### Step 2 — Upload the Files

**Option A — via the GitHub website (easiest):**

1. On your new repository page, click **Add file → Upload files**.
2. Drag and drop all files: `index.html`, `about.html`, `services.html`, `team.html`, `contact.html`, `.nojekyll`
3. Click **Commit changes**.

**Option B — via Git (for developers):**

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. In your repository, go to **Settings → Pages**.
2. Under **Source**, select **Deploy from a branch**.
3. Choose branch: `main`, folder: `/ (root)`.
4. Click **Save**.

Your site will be live at:
```
https://YOUR_USERNAME.github.io/YOUR_REPO/
```

*(It may take 1–2 minutes for the first deployment.)*

### Step 4 — (Optional) Custom Domain

If you have a custom domain (e.g. `medge.co.zm`):

1. Go to **Settings → Pages → Custom domain**.
2. Enter your domain and click **Save**.
3. In your domain registrar's DNS settings, add a `CNAME` record pointing to `YOUR_USERNAME.github.io`.

---

## ✉️ Contact Form

The contact form currently uses a simulated submit. To make it functional, integrate a free form service:

- **[Formspree](https://formspree.io)** — change the form `action` to your Formspree endpoint
- **[EmailJS](https://emailjs.com)** — add their SDK and call their API on submit

## 📞 Contact

- **Phone:** +260 777 444 104
- **Email:** hello@medge.co.zm
- **LinkedIn:** [linkedin.com/company/medgezm](https://www.linkedin.com/company/medgezm/)
- **Location:** Chalala, Lusaka, Zambia
