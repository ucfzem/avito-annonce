# Avito Annonce — Conversation Log

## What was built
Professional Avito landing page for web services in Morocco with 3 pricing packs.

## Features
- 3 packs: Standard (2 900 DHS/درهم), Pro (5 900 DHS/درهم), Premium (9 900 DHS/درهم)
- 4 languages: FR (default), EN, ES, AR (Moroccan flag 🇲🇦)
- RTL support for Arabic with Cairo font
- Sticky language switcher bar with flags + initials (🇫🇷 FR, 🇬🇧 EN, 🇪🇸 ES, 🇲🇦 AR)
- WhatsApp floating button with language-aware message
- Email CTAs (per-pack subjects)
- "Pour qui" section (3 profiles: Starter, Conqueror, Leader)
- Testimonials section (social proof)
- FAQ section (accordion, 3 questions)
- KPI indicators on Pro and Premium packs
- Trust section + scarcity element (5 clients/month)
- Fade-in scroll animations (IntersectionObserver)
- Dark theme with gold accents (default)
- Light mode toggle (beige/brown/gold) with sun/moon icon, persists in localStorage
- Mobile responsive

## Price format
- Numbers in `<bdi>` tags for LTR isolation in RTL mode
- Currency in separate `<span>`: `DHS` for FR/EN/ES, `درهم` for AR
- Dynamic via `translations.currency` key

## Files
- `index.html` — Single-page landing page with i18n

## Deploy
- GitHub: https://github.com/ucfzem/avito-annonce
- GitHub Pages: https://ucfzem.github.io/avito-annonce/
- Vercel: https://avito-annonce.vercel.app/
