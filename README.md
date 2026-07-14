# Kseniia Kalashnikova — Personal Site

Single-page personal website for Kseniia Kalashnikova, marketing strategist.
Visual identity matches the Celar Marketing Lab design system (Cosmic Navy /
Aurora Cyan / Stellar Purple palette, Space Grotesk + Poppins, orbital motifs).

## Structure

- `index.html` — the entire site (HTML + CSS + JS in one self-contained file, no build step)
- `vercel.json` — static hosting config for Vercel

## Deploy

1. Push this repo to GitHub.
2. Import the repo in Vercel → it will auto-detect the static site and deploy `index.html` at the root.
3. Point your domain (if any) to the Vercel project.

No build command or install step is needed — it's a static file.

## Sections

Hero → About → Why Work With Me → Services & Pricing → Digital Products
(links out to celarmarketinglab.com/celar_products.html) → Free Interactive
Tools (3 lead-gen quizzes) → Process → Ecosystems (Celar Marketing Lab /
Equesolution) → Contact.

## To finish setup

- **Lead capture on the free quizzes**: open `index.html`, find
  `WEB3FORMS_ACCESS_KEY = "REPLACE_WITH_YOUR_WEB3FORMS_ACCESS_KEY"` near the
  bottom `<script>` block, and paste the real Web3Forms access key (same one
  used on celarmarketinglab.com contact forms). Without it, quizzes still work
  fully in-browser — results just aren't emailed to you yet.
- **Equesolution link**: currently points to the Contact section as a
  placeholder. Update the two `href="#contact"` instances labeled
  "Equesolution" once the site exists.
