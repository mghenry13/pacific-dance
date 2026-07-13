# Conversion tracking wiring (for Curtis) — zero code
Existing: GA4, GTM, Meta Pixel & Google Ads tags already installed on the account (per May strategy call).

1. **Pixel on the new site**: Squarespace → Settings → Developer/Marketing → Facebook Pixel field → paste pixel ID (native, sitewide).
2. **Lead event**: every completed form redirects to **/thank-you**. In Meta Events Manager → Custom Conversions → new conversion, rule: URL contains `/thank-you`, event = Lead. Same rule in GA4/Google Ads (page_view of /thank-you = conversion).
3. **Ad destination**: point all Meta traffic at **/free-class** (message-matched, form-first). Never the homepage.
4. **UTMs**: Meta auto-params on; keep `utm_campaign` naming = audience (littles / teens-kpop / adults) so form attribution + platform data line up.
5. **Attribution field**: the optional "How did you hear about us?" on both forms gives human-readable attribution in Lori's inbox — cross-check monthly against platform numbers.
6. **Post-launch (needs Business plan)**: Microsoft Clarity via code injection for session recordings; quiz-format form v2 for audience segmentation.
