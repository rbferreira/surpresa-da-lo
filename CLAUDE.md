# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Context

Single-page website for **Surpresa da Lo** — a personalized dessert brand specializing in layered jar desserts for events (children's parties, weddings, corporate). The site's primary goal is converting visitors into WhatsApp orders.

## Brand Identity

- **Palette:** Nude `#F7EDE2`, Rosa `#FADADD`, Marrom chocolate `#6B4F4F`, Branco `#FFFFFF`
- **Style:** Dreamy, delicate, feminine, sparkle effects — inspired by the reference images in the project root
- **Typography:** Script/cursive for the brand name, clean sans-serif for body text
- **Tone:** Afetuoso, encantador, proximo. Phrases like "Feito com carinho", "Encante seus convidados"
- **Visual elements:** Strawberries, hearts, flowers, sparkles, soft textures

## Architecture

Single `index.html` file with all CSS and JS inline. No build step, no dependencies — just open in a browser.

- **Fonts:** Google Fonts CDN (Great Vibes for brand script, Poppins for body)
- **Images:** Local files in project root (product photos and brand seal)
- **WhatsApp:** All CTAs link to `wa.me` with pre-filled message template

## Sections

Hero | Visual showcase | Sobre | Cardapio (3 lines: Assinatura, Classicos, Premium) | Kits (20/30/50 units) | Diferenciais | Galeria | Contato

## Key Data

- **WhatsApp:** `5521998201151` (+55 21 99820-1151)
- **Instagram placeholder:** `@seudocontato` (replace with real handle)
- **Prices:** Delicia de Morango P R$15 / M R$21 | Premium a partir de R$18 | Kits: 20un R$300, 30un R$450, 50un R$750

## Development

```bash
# Just open in browser — no build required
start index.html          # Windows
open index.html           # macOS
```

To serve locally with live reload:
```bash
npx serve .
```
