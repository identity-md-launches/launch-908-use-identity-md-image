# IMD Hackathon poster

Latest image: [artifacts/image-v3.png](artifacts/image-v3.png).

The right billboard's Dexscreener owl and wordmark have been replaced with the Identity.md profile picture from its Dexscreener listing. The hackathon text, prize amounts, and AI-equipped Pepe artwork are retained.

## Result record

- Output: `artifacts/image-v3.png`, PNG (`image/png`), RGB, 1024 × 1536 pixels.
- SHA-256: `3822be8971c8ce2018228e4a6dbfdd85030ff48267772b70fb2fa696ad26e10b`.
- Profile source: [Identity.md on Dexscreener](https://dexscreener.com/ethereum/0xb07d640fd9e2eb9dc81b953c8e4fd006bdfeaf276010fb5418eb763ca15abfb3).
- Source image: https://cdn.dexscreener.com/cms/images/e2cGlI71ubIiEUpw?width=800&height=800&quality=95&format=png
- Method: installed image edit tool (`mcp__image__edit_image`), using the previous poster and downloaded profile image as inputs.
- Edit prompt: replace only the right billboard's Dexscreener owl and wordmark with the supplied Identity.md gold-star medallion portrait, matching the billboard perspective; preserve all other artwork and every line of text.
- Review performed: visually inspected the output against both input images; confirmed removal of the Dexscreener branding, recognizable Identity.md portrait, and retained poster copy. PNG decoded and integrity verified with Pillow.
- Unmet visual requirements: none observed. The inserted portrait is rendered in perspective rather than a pixel-identical copy of the source.
- Retained limitation: the existing “OVER $15,000” headline exceeds the listed cash prizes, which total $10,000. No change to that headline was requested.

Earlier versions remain available as `artifacts/image.png` and `artifacts/image-v2.png`.
