# lovelydata.org

Public site of LovelyData, a trade name of Capstone Research Group VBA (Aruba). Static HTML served by GitHub Pages from `main`; **push to `main` = publish**.

- `index.html` - landing page (LovelyData palette, white background).
- `aruba-population/index.html` - interactive population pyramid, 1991-2025. **Do not edit here.** It is generated in the knowledge hub by `01-projects/aruba-demographic-pyramid/build_delta_pyramid.R` from CBS data documented in `aruba-data/datasets/cbs-population-age-sex/`; rebuild there and copy the output in.
- `assets/` - logo and preview image.
- `CNAME` - custom domain `lovelydata.org` (DNS at GoDaddy; mail stays on the GoDaddy Microsoft 365 mailbox, so never touch the MX, TXT or autodiscover records).
