# Thalassa Marine Biosciences — website

A 5-page static site (Home, Products, R&D Lab, About, Contact) ready for GitHub Pages.

## Files
- `index.html` — homepage
- `products.html` — full product/service descriptions
- `research.html` — R&D lab facility page
- `about.html` — founder & company story
- `contact.html` — enquiry form (placeholder — wire up to Formspree/Netlify Forms or a backend)
- `styles.css` — shared design system

## Publish it on GitHub Pages (no coding needed)
1. Create a new GitHub repository, e.g. `thalassa-marine` (Settings can be public or private, but Pages requires public on the free tier).
2. Upload all files in this folder to the repository root (drag-and-drop works on github.com, or `git add . && git commit -m "site" && git push`).
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
5. GitHub will publish the site at `https://<your-username>.github.io/thalassa-marine/` within a minute or two.
6. To use a custom domain later, add a `CNAME` file with your domain and configure DNS per GitHub's custom-domain instructions.

## Renaming the company
The name "Thalassa Marine Biosciences" appears in the `<title>`, `.brand` link, and footer of every page. To rename, do a find-and-replace for "Thalassa Marine Biosciences" (and "Thalassa" alone in a few headings) across all `.html` files.

## Before going live
- Replace the contact form's placeholder `alert()` with a real form handler (Formspree, Netlify Forms, or your own endpoint).
- Replace the placeholder email/address in `contact.html`.
- Confirm the chosen company name is available and not trademarked in India/EU before using it commercially.
- Legal, regulatory (FSSAI/AYUSH for the supplement; CDSCO for the biomedical sponge/matrix), and GMP certification content should be added once actually obtained — the current copy is written as a planning concept, not a certified claim.
