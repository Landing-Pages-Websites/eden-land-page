# Eden Land Company — Landing Pages

Multi-route landing page serving https://book.edenlandcompany.com.

## Routes

- `/` — Rancho Chula Vista (10-acre tracts near Cuero, TX)
- `/camp-swift` — Camp Swift (half-acre lots in Bastrop County) — English
- `/camp-swift-es` — Camp Swift — Spanish translation. Reuses
  `/camp-swift/images/` assets and the same HubSpot form, MegaTag,
  GTM, Meta Pixel, and CTM config as the English page.

## Stack

Static HTML deployed to Vercel. Vercel project `eden-land-page`
(prj_TbFIvzdsB0SK3CSjYqWPOu6sR81J) auto-deploys this `main` branch.

## History

Repo adopted into `Landing-Pages-Websites` org on 2026-05-18 from a CLI-only
Vercel deployment (previous source at `zleague/eden-land-page`,
inaccessible). Initial commit reconstructs the production deployment files
from Vercel's deployment-files API (dpl_5LHhwuwBFb8CfJguuqH8nTMFKzHY).
See Buena Health 2026-05-15 playbook (`memory/lp-mistakes.md`) for the
adoption procedure.

## Tracking

- MegaTag (cdn.gomega.ai/scripts/optimizer.min.js)
- Camp Swift siteKey: `sk_mm9mpdqg_cvto430u2ev`
- GTM: GTM-N79FSNMF (head config), GTM-M8CKNQMC (body container)
- Meta Pixel: 1502927760991301
- Google Ads: AW-17529529320
- CallTrackingMetrics: 572388.tctm.co/t.js
