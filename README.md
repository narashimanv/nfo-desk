# NFO Desk

AssetPlus landing page listing new fund offers that are open now or upcoming, for MFD partners.
Static site: `index.html` (layout and logic), `data.js` (the NFO list), `assetplus-logo.png`.

The daily NFO tracker run updates only `data.js`. Every field comes from each scheme's own scheme document
(SID / KIM / ISID, or the SEBI draft for "Coming soon"). An NFO is shown only when its scheme document,
fund manager, minimum investment, dates and riskometer are all available.

Netlify: publish directory is the repository root; no build command.
