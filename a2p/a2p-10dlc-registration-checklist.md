# A2P 10DLC registration checklist (US business texting)

> Disclosure: Peace Call is an independent HighLevel affiliate. Some guides on getpeacecall.com contain labeled affiliate links; Peace Call may earn a commission at no extra cost to you. This repository contains no affiliate links. Not affiliated with or endorsed by HighLevel. Not legal advice.

Based on HighLevel help-center documentation as read in October 2026. Fees and steps change; re-check before submitting. Draft and check your wording with the free [A2P 10DLC checker](https://getpeacecall.com/a2p-10dlc-checker/?utm_source=github&utm_medium=repo&utm_campaign=agency-templates). Full guide: [A2P 10DLC registration](https://getpeacecall.com/gohighlevel-a2p-10dlc-registration/?utm_source=github&utm_medium=repo&utm_campaign=agency-templates).

## 1. Pick the brand type
- [ ] Business has an EIN / Tax ID → **Standard Brand** (required even if small).
- [ ] No Tax ID, one person → **Sole Proprietor** (1 number per campaign, ~3,000 segments/day, public email such as Gmail, US/CA mobile for OTP, no VoIP).
- [ ] EIN is older than ~15 days (newer ones may be rejected). DUNS is not accepted.

## 2. Prepare before opening Trust Center
- [ ] Exact legal business name, EIN, business type, industry, registered address (no P.O. box in street field). IRS CP-575 / 147C at hand.
- [ ] Authorized contact: name, reachable phone, monitored email, job title.
- [ ] Live public website showing the same business name (and DBA) and contact details.
- [ ] Privacy Policy: no lead selling/sharing language; includes "mobile information will not be shared with third parties for marketing".
- [ ] Terms: business name, message types, STOP/HELP, carrier-liability line, message frequency, "Message and data rates may apply", link to Privacy Policy.
- [ ] Every phone-collecting form: SMS consent checkbox optional, unchecked, separate for marketing vs non-marketing; form works without consenting.

## 3. Campaign content
- [ ] Description says who sends, who receives, what is sent, how people opt in.
- [ ] 2+ realistic sample messages with the business name and "Reply STOP to opt out"; no merge fields, no link shorteners, https only.
- [ ] Opt-in method matches reality (web form, verbal, paper, QR, chat widget). Public opt-in page or screenshot with full consent wording.
- [ ] Marketing texts not hidden in a customer-care campaign.
- [ ] STOP and HELP auto-replies written.

### Example description (missed-call text-back, customer care only)
> [Business] sends customer-care text messages to people who call our business line or request service on [website]. When a call is missed, we text the caller once to ask how we can help, then reply to questions about service requests, scheduling and appointment confirmations. We don't send promotional offers in this campaign. Contacts can reply STOP to opt out or HELP for help.

Sample: `[Business]: Sorry we missed your call. How can we help? Reply here. Reply STOP to opt out.`

## 4. Submit (HighLevel: Settings → Phone System → Trust Center)
- [ ] Start Registration → Get Started questions → brand details → verification (Persona or email OTP).
- [ ] Volume: Low or High (Standard) / single number (Sole Prop).
- [ ] Chat Widget Setup or Manual Setup (manual if opt-in happens elsewhere).
- [ ] Review Application → fix every AI-review flag → submit. Don't open a second campaign while one is Pending.
- [ ] Budget: fees start at submission regardless of outcome (Oct 2026: about $22.50 one-time + $1.50–$10.50/month per Low Volume campaign). Verify current pricing.

## 5. Common rejection causes
| Area | Cause | Fix |
|---|---|---|
| Brand | Name/EIN mismatch with IRS, wrong address, Sole Prop despite Tax ID | Match records exactly |
| Opt-in | Can't be verified, pre-checked/required box | Public opt-in page with full wording |
| Website | Down, different name, no Privacy/Terms | Publish pages, align names |
| Use case | Description, samples and real messages disagree | Rewrite all three together |
| Samples | No sender name, no opt-out, merge fields | Realistic samples with name + STOP |
| DBA | Site name ≠ legal name | Show DBA on site and in description |

Open the rejected campaign → *View required fixes* and fix every item before resubmitting.

## 6. After approval
- [ ] Link every sending number to the campaign; check the "A2P Verified" label in Phone Numbers.
- [ ] Repeat for every newly bought number (unlinked numbers cause error 30034).
- [ ] Real test: call from an unsaved phone, let it ring out, confirm the text-back arrives.
- [ ] Check state quiet hours and consent rules: [texting laws by state](https://getpeacecall.com/missed-call-text-back-laws-by-state/?utm_source=github&utm_medium=repo&utm_campaign=agency-templates).
- [ ] Agencies: each client registers under its own legal business.
