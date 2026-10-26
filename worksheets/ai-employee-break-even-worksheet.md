# AI Employee: Growth vs Unlimited break-even worksheet

Fill this in per location (sub-account) once a month. It uses HighLevel's published rates as of October 2026, as summarized in Peace Call's break-even guide. Check HighLevel's AI Product Pricing page before relying on any number.

## Plan facts

| Plan | Price per location | Voice AI minutes |
| --- | --- | --- |
| Growth | $50/month | 100 included, then pay-per-use |
| Unlimited | $97/month | Unlimited, subject to fair use |

The gap is **$47/month**. That's how much Growth overage you can absorb before Unlimited is cheaper.

## Your numbers

```
Location name:                       ____
Month:                               ____
Total Voice AI minutes this month:   ____   (inbound + outbound + website widget, shared)
Voice chosen:                        ____
Pay-per-use rate per minute:         $____  (voice engine $0.045 + your voice's TTS rate; LLM tokens extra)
```

## Formula

```
Overage minutes    = max(0, total minutes - 100)
Growth cost        = $50 + overage minutes x per-minute rate
Unlimited cost     = $97
Break-even minutes = 100 + 47 / per-minute rate
```

## Reference points from the guide

| Per-minute rate | Example voice | Break-even (total minutes/month) |
| --- | --- | --- |
| about $0.06 | OpenAI or Cartesia | about 883 |
| about $0.215 | ElevenLabs V3 | about 319 |

Token costs and Conversation AI overages push the break-even lower. Phone System charges (numbers, call minutes) apply on both plans and don't change the comparison.

Guide: https://getpeacecall.com/gohighlevel-ai-employee-growth-vs-unlimited/?utm_source=github&utm_medium=social

Made with AI assistance. Peace Call is an independent HighLevel affiliate and may earn a commission through links in the guide.
