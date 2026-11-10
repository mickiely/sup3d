# SUP3D — Commercial Model & Advertising Network v1
Date: 10 November 2026
Owner: ESO ES
Status: Working commercial decisions / assumptions. Not a production launch or verified forecast.

## Positioning
SUP3D is a reusable spatial guest-experience and park-operations platform, not just a 3D map. Sell outcomes (guest engagement, navigation, time saved, potential park revenue) rather than cheap hosting. Existing demos use real park maps and sample operational data; do not represent sample bookings, prices, owners or jobs as live data.

## Packaging and pricing hypotheses (AUD ex GST)
| Package | One-off implementation | Monthly licence | Status |
|---|---:|---:|---|
| Experience | $2,995 | $599 | Demo foundation exists; verify guest content and delivery |
| Operations | $5,995 | $1,199 | Demonstration only; production backend and acceptance pending |
| Complete | $8,995 | $1,799 | Requires operational readiness |

Standard implementation includes agreed map setup, basic verification, branding, website integration, testing and handover. Quote unusual remapping, additional training, integrations and custom work separately. No double-charging for included scope.

## Cost model — assumptions, not measured expenditure
Per Experience park: approximately $50 cash setup + 10 hours labour at $65/h = $700 economic setup cost. Monthly direct cost previously modelled at $42–49 including allowances for support, maintenance and payments. Operations and Complete need additional labour, persistent data, auth, backup and support; actual costs unverified. Platform development, acquisition, central overhead, insurance, taxes, GST, refunds and churn must be modelled separately. Measure actual onboarding hours before quoting at scale.

## Revenue engines
1. Per-property platform licence and recurring support.
2. One-off implementation and scoped professional services.
3. Opt-in local advertising network with park revenue share.
4. Potential future premium integrations/customisation.

## Advertising network — proposed hybrid
ESO ES operates the technology, advertiser management, billing, reporting and multi-park inventory. Each participating park controls/approves advertisers and categories presented to its guests. Proposed starting split: **70% ESO ES / 30% park of eligible advertising receipts**, subject to written terms. Define whether split is calculated before or after refunds, GST, processor charges and agency commissions; do not imply 70% is net profit. Alternative split for park-sourced advertisers can be negotiated.

### Proposed ad inventory / test prices (AUD ex GST)
| Placement | Monthly price hypothesis |
|---|---:|
| Featured local business | $99 |
| Sponsored map pin | $149 |
| Sponsored itinerary placement | $199 |
| Category sponsorship (where permitted) | $299 |
| Multi-park campaign | Quote |

Sponsored content must be labelled. Never imply a recommendation is independent when paid. Protect the guest experience; no accommodation competitors without explicit park consent. Park may decline categories, placements or advertisers. Do not guarantee impressions, guest traffic or sales.

### Example economics — illustrative, not forecast
20 participating parks × 5 sold placements per park × $199/month = $19,900 gross advertising billings per month, assuming 100 distinct paid placements. At proposed 70/30: ESO ES $13,930; parks collectively $5,970, **before** taxes, refunds, sales costs, payment processing and support. Avoid double-counting one multi-park advertiser as multiple customers without separately priced placements.

## Measurement and proof
Instrument per-park and per-campaign: eligible impressions (actually rendered in view), unique/repeat reach where privacy-respecting, clicks, directions taps, itinerary saves, referral links and **verified** voucher redemptions/bookings when available. Keep these distinct: clicks and itinerary saves are not sales. Baseline adoption and engagement must be measured before promising any exposure. Offer aggregate reports; minimise personal data, obtain necessary consent, document retention, and comply with Australian privacy and advertising obligations.

## MVP: one park, three to five advertisers
- Build an approved sponsor catalogue and clearly labelled placements in the **existing guest planner**, without breaking the working 3D controls or nine-park navigation.
- Admin initially manual: park approves each sponsor and content; ESO ES configures campaigns and dates.
- Record campaign impressions/clicks without unnecessary identifying data; basic campaign/park reporting; optional unique redemption code.
- Use real data only when instrumented; never populate customer-facing metrics with invented results.
- Test actual guest engagement, park satisfaction, advertiser renewal and support workload before building self-service billing or multi-park buying.
- Revenue share can initially be reconciled manually with auditable receipts and payouts.

## Product delivery gates
Guest demo: confirm links, responsiveness, content rights, accuracy and browser performance.
Operations: verify identity/roles, persistence, backups/recovery, permissions, reliable task state, imports and acceptance tests before offering as production.
Advertising: sponsor approval, disclosures, consent/privacy review, tracking accuracy, refund and payout terms, reporting QA and opt-out controls.
Do not deploy or alter live production until tested and explicitly approved.

## Decision register
**Agreed direction:** packages at the front end, reusable modules underneath; hybrid ad model; park control; proposed revenue sharing; measurable advertising; pilot first; retain ESO ES software IP subject to licences.
**Still to validate:** pricing and willingness to pay, ad take-up, exact revenue-share contract, support economics, park approval process, advertising compliance, technical instrumentation, live operations readiness, existing map rights.
**Next:** build a customer-facing package comparison and ROI estimator; prototype labelled sponsored placements and measurement in a non-production branch; interview one operator and 3–5 local advertisers.
