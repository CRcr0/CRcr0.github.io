# crcr0.github.io

Personal academic homepage of Richard Rui Chu, served at <https://crcr0.github.io/>.

- Nine pages, one per application version: the site root and `cs/`, `business/`, `ise/`, `stats/`, `hcai/`, `robotics/`, `health/`, `ai4s/`. Each page has its own `cv/Richard_Rui_Chu_CV.pdf` (public copy of that version's CV, phone number removed).
- The pages are generated from the private application-materials repository (`tools/homepage/build_homepages.py`): research interests, selected publications and manuscripts come from that version's CV, the tagline from its research statement. Edit the CV there and re-run the script; do not edit the `index.html` files by hand.
- `img/fig1/`: Figure 1 of each published paper. `img/avatar.webp`: cartoon-style portrait.
- Pages carry `noindex`; `robots.txt` keeps `/cv/` out of search indexes.

To update, re-run the generator and push to `main`; GitHub Pages redeploys automatically.
