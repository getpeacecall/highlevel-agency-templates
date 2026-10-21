# HVAC & Plumbing AI Receptionist: Intake Fields and Triage Map

A copy-ready field list and triage table for an HVAC or plumbing company's AI phone agent (or a human answering service). Paste the triage table into the agent's prompt word for word after your team agrees on it, and create the fields as custom contact fields in your CRM.

> Prepared with AI assistance from Peace Call's public guide. Peace Call is an independent HighLevel affiliate and may earn a commission through links in the guide. Not affiliated with or endorsed by HighLevel. The safety lines are placeholders: replace them with your own company policy and local utility instructions.

## 1. Required fields (every call)

| Field | Type | Example values | Notes |
|---|---|---|---|
| full_name | text | | |
| callback_number | phone | | Read back to the caller to confirm |
| email | email | | Only if offered |
| service_address | text | | |
| service_zip | text | | Check against your service-area list |
| occupant_type | dropdown | homeowner / renter / property manager | Renters may need landlord approval |
| service_type | dropdown | HVAC heating / HVAC cooling / plumbing / water heater / drain / other | |
| problem_description | long text | | Caller's own words, no diagnosis |
| urgency_level | dropdown | 1-hazard / 2-urgent / 3-next-available / 4-standard | From the table below |
| system_details | text | age, brand, gas or electric, tank or tankless | If known |
| preferred_windows | text | | |
| lead_source | dropdown | | Optional |
| disposition | dropdown | transferred / paged / booked / message only / out of area | |

## 2. Triage table (paste into the prompt)

| Level | Caller describes | Agent does |
|---|---|---|
| 1-hazard | Gas smell | "[approved line: leave now, no switches, call the gas utility or 911 from outside]". Alert on-call. Stop intake. |
| 1-hazard | CO alarm sounding | "[approved line: everyone outside, call 911]". Alert on-call. Stop intake. |
| 1-hazard | Water spreading near electrical | "[approved line: stay away, call 911 if unsafe]". Escalate to on-call. |
| 2-urgent | Active leak, water spreading | Ask if they can safely shut off the main valve. Escalate to on-call. |
| 2-urgent | No heat in freezing weather or no AC in dangerous heat, vulnerable occupants | Live transfer or immediate page, per policy. |
| 3-next-available | No heat/AC, mild weather, no vulnerable occupants | Book next repair slot. Offer priority if you sell it. |
| 4-standard | Clog, dripping faucet, tune-up, quote | Book a standard appointment. |

## 3. HighLevel Voice AI action map

| Need | Action |
|---|---|
| Save fields above | Update Contact Field |
| Level 1 and 2 | Call Transfer to on-call (add a backup number) |
| Level 3 and 4 | Appointment Booking (route repair vs estimate calendars by intent) |
| Confirmation | Send SMS |
| Dispatch alert or opportunity | Trigger a Workflow |
| Push to field-service software | Custom Action (webhook) |

## 4. Test before launch (real phone call for transfers)

- [ ] Gas-smell call stops intake and escalates
- [ ] Upset caller, no AC in a heat wave
- [ ] Caller outside the service area
- [ ] "How much to replace my water heater?" gets no invented price
- [ ] Address given in pieces or changed mid-call
- [ ] Background noise, long silence, talking over the agent
- [ ] Spam or robocall

Full guide: https://getpeacecall.com/ai-receptionist-hvac-plumbing/?utm_source=github&utm_medium=social
