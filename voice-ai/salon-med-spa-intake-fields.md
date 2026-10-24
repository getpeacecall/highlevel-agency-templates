# Salon & med spa AI receptionist: intake fields (collect vs leave out)

Use this when scoping a Voice AI agent that books for a salon or med spa. The agent is a scheduling and routing assistant, not a stylist, injector or clinician.

## Collect on the call
| Field | Notes |
| --- | --- |
| Name | |
| Confirmed callback number | Read it back |
| New or existing guest | |
| Service category | Use your own menu names (haircut, color, facial, consult, injectables consult, laser consult) |
| Preferred stylist / provider / location | |
| Preferred days and times | |
| Deposit / policy acknowledgment | Yes / no only, using wording you approved |

## Leave for staff or secure forms
- Full medical history, medications, allergy narratives
- Insurance IDs
- Detailed symptom stories beyond a yes/no urgency screen
- Payment card numbers (unless your approved payment flow supports the phone channel)
- Marketing authorizations that need a signed form

## One urgent-triage question (med spa)
"Are you having a possible allergic reaction or trouble breathing right now?" Yes → the emergency line your medical director approved. The agent gives no medical advice.

## Never
- Recommend treatments or promise results
- Quote prices that are not in the knowledge base
- Pretend to be human or guess when information is missing

## Launch tests (call by phone)
1. New guest books a haircut with a named stylist
2. Existing client reschedules
3. Caller asks for a price not on the menu (agent must not invent one)
4. Caller says yes to the allergic-reaction question (must route to emergency line)
5. Caller tries to read a card number (agent must stop and offer the secure option)

Source guide: https://getpeacecall.com/ai-receptionist-salon-med-spa/

Prepared with AI assistance. Maintained by Peace Call, an independent HighLevel affiliate.
