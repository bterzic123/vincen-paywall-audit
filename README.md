# Paywall Audit — Vincen

**Live:** https://bterzic123.github.io/vincen-paywall-audit/

Prepared for the Apptribe team by Adapty, October 2026. Four ideas for Vincen's paywall, each tied to a finding in [State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=vincen), plus a clickable rebuild of the paywall and of what happens when it is closed, in Vincen's own design. Flip **Today / Proposed** above the phone to compare.

## The four ideas

| # | Idea | Report anchor | Potential outcome |
| :-- | :-- | :-- | :-- |
| 1 | Put a 7-day trial on Yearly, and say when it bills | 5.3 annual-forward layout; 3.4 trial timeline (24% of trial paywalls); table K (7-day trials convert better on annual) | ARPU +25–40% · observed in winning A/B tests |
| 2 | Give the close button a second chance | 4.5: only 4% of apps do it; converts at 0.88× the main paywall | ARPU +10–15% · based on Adapty data |
| 3 | Show your 4.7 stars on the paywall | 3.1: 27% of top paywalls show social proof; 5.3 social proof | CR +10–30% · observed in winning A/B tests |
| 4 | Let the X wait three seconds | 3.7: 22% of apps delay it, half by 3–5 s; 5.3 close-button delay | CR +8–15% · observed in winning A/B tests |

**Benchmarks:** App Store data, Oct 2025–Sep 2026. Productivity apps in the US where the report cuts that finely; the A/B test results cover all apps.

## Grounding

Prices (179,99 €/year, 22,99 €/month, 15.00€/month, "Save 35% + 10.000 Credits Bonus"), the feature list and the close behaviour come from Vincen's live paywall. The 4.7 rating from 1.8K ratings comes from the US App Store listing. The 7-day trial and the offer sheet are proposals to test, not products Vincen sells today; the offer uses only the existing monthly price.

Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for Vincen.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Add `?open=proto` to land on the prototype.
