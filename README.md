# Swipit — prototype
Fintech + travel + shopping super-app front-end (demo data, no real payments).
## Run
Open `index.html`, or `python3 -m http.server` and visit http://localhost:8000
## Structure
- `index.html` shell · `css/styles.css` tokens, glass/gloss, 3D cards, hero ring, scenes · `js/data.js` mock data/API layer (cards, offers, airports AP, hotels HT) · `js/app.js` components, pages, router, payments, best-card engine, hero ring, login
## Notes
Default user: Shivam Kumar (`USER` in data.js). Never store raw card numbers/CVVs; use a PCI-DSS tokenisation provider and a licensed payment aggregator.
# astravore
