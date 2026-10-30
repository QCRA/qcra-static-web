# Queensfield Court Residents’ Association website

Source for the QCRA website at https://qcra.org.uk/

## Design & Philosophy

- **Mobile-First:** Optimized for mobile viewing as most residents will access the site via phones.
- **QR Code Integration:** Every page features a dedicated SVG QR code to enable easy sharing and physical-to-digital linkage for notices and documents displayed around the development.

## Deployment

The `public/` directory is the web root.
The production site is deployed through Cloudflare Pages from the `main` branch[cite: 5].

## Local Development & Preview

To preview the site locally, you can run a lightweight static server from the `public/` directory:

```bash
cd public
python3 -m http.server 8000
python3 -m http.server 8000 --directory public
