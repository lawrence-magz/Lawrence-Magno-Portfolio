# Lawrence B. Magno | Portfolio

Static portfolio website (HTML/CSS) with a printable QR business card.

## Files
- `index.html`: the portfolio site (self-contained, photo included)
- `style.css`, `photo.jpg`: optional copies of the styles and photo
- `card.html`: QR card generator (front + back, print-ready)

## Before publishing
All personal details, LinkedIn and GitHub links are already filled in.
The only thing left is the QR code, which needs your live Vercel URL (see below).

## Push to GitHub
```bash
git init
git add .
git commit -m "Add portfolio website"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Deploy on Vercel
1. Go to vercel.com and sign in with GitHub.
2. Click **Add New > Project** and import the repository.
3. Framework Preset: **Other**. Leave build settings empty. Click **Deploy**.
4. Copy the live URL (e.g. `https://your-portfolio.vercel.app`).

## Make the QR card
1. Open `card.html`, paste the Vercel URL, click **Update QR**.
2. Click **Print / Save PDF** and print on card stock (3.5 x 2 in).
3. Test the scan with your phone before printing a batch.
4. Optionally, hard-code the URL in `card.html` and push again.
