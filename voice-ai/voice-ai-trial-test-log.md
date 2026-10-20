# Voice AI trial test log

A test log for evaluating one HighLevel Voice AI agent during a trial, before it takes real calls. It follows the evaluation steps in Peace Call's HighLevel Voice AI review: start with one narrow job, test hard, and check the real per-call cost before scaling.

Rates and features change. Confirm everything in your own account.

## 1. Scope (fill in before testing)

- Business / sub-account: [name]
- The one job this agent does: [for example, after-hours intake for one company]
- Deployment mode: [Answer Calls Directly / Use as Backup]
- Working Hours: [all hours / custom schedule]
- Actions enabled (keep it to these three at first): Appointment Booking, Call Transfer, one notification workflow
- Voice selected: [name] (the voice is one of the biggest cost levers)

## 2. Test calls (aim for 15 to 20)

Transfers only run in a real phone-call test, not in the browser Web Call test, so mark which type you used.

| # | Scenario | Web Call or Phone Call | Expected result | What happened | Pass? |
| --- | --- | --- | --- | --- | --- |
| 1 | Routine booking, calm caller | | Books on the right calendar | | |
| 2 | Question the knowledge base answers | | Answers from the KB only | | |
| 3 | Question the KB does not answer | | Takes a message, does not guess | | |
| 4 | Request that needs a person | Phone Call | Transfers to the right number | | |
| 5 | Transfer target does not pick up | Phone Call | Falls back as configured | | |
| 6 | Unclear or rambling request | | Asks one question at a time | | |
| 7 | Caller interrupts the agent | | Recovers without repeating itself | | |
| 8 | Long silence | | Prompts, then ends politely | | |
| 9 | Caller asks for a price not in the KB | | Does not quote | | |
| 10 | Caller asks "Are you a person?" | | Says it is a virtual assistant | | |
| 11 | Spam or robocall | | Ends without creating a lead | | |
| 12 | Outside service area | | Says so and does not book | | |
| 13 | Safety or emergency wording for this trade | Phone Call | Reads the approved line, escalates | | |
| 14 | Call outside Working Hours | Phone Call | Behaves as the schedule says | | |
| 15 | Booking, then check the contact record | | Fields and tags are filled in | | |

## 3. After testing

- [ ] Read every transcript and AI summary in the call logs.
- [ ] Check AI usage and wallet charges, and divide by the number of test calls to get a real per-call cost.
- [ ] Note phone charges separately (they apply on every plan).
- [ ] Turn on missed call text back as a safety net.
- [ ] Decide: pay-per-use, AI Employee Growth, or AI Employee Unlimited, based on expected minutes.

Source review: https://getpeacecall.com/gohighlevel-voice-ai-review/?utm_source=github&utm_medium=social

Prepared with AI assistance. Peace Call is an independent HighLevel affiliate and may earn a commission from links in the review. Not affiliated with or endorsed by HighLevel.
