# Oscarman Mechanic and Engineering

Official website for **Oscarman Mechanic and Engineering**, a mechanical workshop based in Utrecht, KwaZulu-Natal, South Africa. Owned and operated by **Zama Oscar Mfusi**, the workshop has been keeping Utrecht's vehicles running since 2018, with 50+ cars repaired and counting.

🔗 **Live site:** https://<your-github-username>.github.io/oscarman-website/

## About this project

This is a simple, fast-loading static website built with plain HTML, CSS, and a touch of JavaScript — no build tools required, so it's easy to host for free on GitHub Pages.

## Project structure

```
oscarman-website/
├── index.html          # Main page (Home, About, Services, Contact)
├── styles.css           # All site styling
├── script.js             # Small interactions (nav toggle, year, counter)
├── assets/               # Images, logo, icons go here
└── README.md
```

## Running locally

No build step needed. Just open `index.html` in a browser, or serve it locally:

```bash
# Python
python3 -m http.server 8000

# Node (if you have npx)
npx serve .
```

Then visit `http://localhost:8000`.

## Deploying with GitHub Pages

1. Push this repo to GitHub (e.g. `oscarman-website`).
2. Go to your repo → **Settings** → **Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Choose the `main` branch and `/ (root)` folder, then **Save**.
5. GitHub will give you a live URL within a minute or two, usually:
   `https://<your-github-username>.github.io/oscarman-website/`

## Business details

- **Owner:** Zama Oscar Mfusi
- **Established:** 2018
- **Location:** 37 Smith Street, Utrecht, 2980, South Africa
- **Phone:** 064 607 9754
- **Email:** lindaphelele1@gmail.com

## To do

- [ ] Add real photos of the workshop and completed jobs to `assets/`
- [ ] Swap the placeholder logo for a real one
- [ ] Add a services price list if the business wants to publish rates
- [ ] Hook up the contact form to a real email service (e.g. Formspree) if a form is added later
- [ ] Add Google Maps embed for the workshop location

## License

All rights reserved — content and branding belong to Oscarman Mechanic and Engineering.
