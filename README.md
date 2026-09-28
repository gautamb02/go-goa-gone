# Goa, the lazy version (1–4 Oct 2026)

A one-page trip guide for Gautam, Piyush and Kankshit, plus a printable PDF.

## Put it online with GitHub Pages

1. Create a new public repository on GitHub, for example `goa-trip`.
2. Upload everything in this folder (keep the `assets` folder and the `.nojekyll` file).
   - In the browser: **Add file > Upload files**, drag the contents in, then **Commit changes**.
   - Or from a terminal:
     ```
     git init
     git add .
     git commit -m "Goa trip guide"
     git branch -M main
     git remote add origin https://github.com/<your-username>/goa-trip.git
     git push -u origin main
     ```
3. In the repository, open **Settings > Pages**. Under **Build and deployment**, set **Source** to
   **Deploy from a branch**, pick **main** and **/ (root)**, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io/goa-trip/`.

## What's inside

- `index.html`: the guide. Works offline too; just open it in a browser.
- `Goa_Lazy_Itinerary_1-4_Oct_2026.pdf`: the same guide as a printable PDF.
- `assets/maps`: day maps. Lines show the order of stops, not exact roads.
- `assets/fonts`: Rozha One and Hind (SIL Open Font License), served locally so the page has no outside requests.

Place names and route buttons open Google Maps.
