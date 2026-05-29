# CampaignIQ — AI Decision Engine for Marketing Campaigns

CampaignIQ is a portfolio case study for an AI decision-support dashboard that helps marketing teams compare campaign channels, generate explainable recommendations, stress-test assumptions, and close the loop with actual performance data.

This repository is a **public showcase** version. The full implementation and private working files are not included.

## Live Case Study

https://7tjbt66zwg-sys.github.io/campaigniq-showcase/

## What It Does

CampaignIQ turns a campaign brief into a defensible channel decision.

The flow:

1. Enter campaign objective, audience and budget.
2. Compare channel options such as Instagram Reels, TikTok, YouTube Shorts or LinkedIn Video.
3. Score each option using weighted business criteria.
4. Generate an explainable recommendation.
5. Run what-if scenarios without overwriting the baseline decision.
6. Record actual campaign results.
7. Export a decision packet with recommendation, audit trail and learning insight.

## Demo Narrative

```text
Brief -> Decision packet -> What-if scenario -> Actuals -> Learning insight
```

The goal was not to build another generic dashboard. The product story is focused on a real business question:

> Which campaign channel deserves budget, and why?

## Key Features

- Explainable recommendation engine
- Weighted scoring across conversion volume, cost efficiency, engagement, brand fit and risk
- Ranked channel alternatives
- PostgreSQL-backed decision records
- Audit trail for campaign creation, recommendation generation, what-if analysis and performance recording
- Printable report
- JSON decision packet export
- Performance learning loop with predicted vs actual comparison

## Example Output

```text
Recommended channel: Instagram Reels
Confidence: 89%
Expected conversions: 182.4
Expected CPA: EUR 18.64
Loop status: measured
Learning insight: Scale candidate
```

## Stack

- Python
- PostgreSQL
- Docker
- REST API
- HTML / CSS / JavaScript
- Decision scoring
- Audit-event model

## Publishing Strategy

The full codebase is kept private because this can become a freelance service, SaaS prototype or deeper DSS project.

This public repository is meant to show:

- product thinking
- system architecture
- AI/decision-support workflow
- business value
- UI narrative

## Status

Portfolio MVP. Demo available on request.
