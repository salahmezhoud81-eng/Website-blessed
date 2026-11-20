# Blessed — flagship website
React + Vite + Framer Motion + Lucide. Plain CSS. Deploys to Vercel as-is.

## Run
npm install && npm run dev      # develop
npm run build                   # production build → dist/

## Configure (everything lives in src/config.js)
Replace every value marked PLACEHOLDER: WhatsApp number, price, colours, sizes,
description, fit, fabric, delivery info, Instagram, logo, and all photos.
Put images in /public/images and reference them as "/images/name.jpg" (use WebP/AVIF, ≤ 250 KB for gallery frames).

## Deploy (Vercel)
Push to GitHub → import the repo in Vercel. vercel.json is already set (Vite, dist/).

## Note on /public/brand/blessed-film.mp4
Supplied brand animation; it carries a "Qwen" generator watermark. Replace with a clean export,
or set brand.brandFilm.enabled=false in config to use a photo instead.
