nomica-site

Temporary Nomica landing page, live until the final version of the website is ready.

Structure
index.html   # single self-contained page (CSS, logo and icons embedded)
README.md

The only external resources are the fonts (Google Fonts: Quicksand, Literata, Barlow Condensed).

Run locally

Open index.html in a browser or serve the folder:

bash
python3 -m http.server 8000
# http://localhost:8000
Edit contacts

Search for TROCAR in index.html:

WhatsApp: https://wa.me/55AREANUMBER (digits only, with 55 and area code)
Phone: tel:+55AREANUMBER and the displayed text
Email: mailto: and the displayed text
Deploy

It's a static file. It works on any static hosting (GitHub Pages, Netlify, Vercel, Cloudflare Pages or your own server). Just publish index.html at the root.

Visual identity

Follows the Nomica Brand Book and the Trama design system:

Colors: ivory #F5F1E6, beige #D7C6B1, graphite #2E2E2E, orange #F47A3C, terracotta #A0573C, sage #7F9173
Typography: Quicksand (headings), Literata (body), Barlow Condensed (labels)
