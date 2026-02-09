# Impact Bonus Guide

A static web page that explains FirstLine Schools' Impact Bonus program, including bonus tiers, eligibility requirements, and payout amounts by role.

**Live URL:** https://impact-bonus-965913991496.us-central1.run.app

---

## Overview

This guide helps staff understand:
- Bonus tiers (Exceptional vs Full Impact)
- Eligibility requirements
- Bonus amounts by role/position
- Payout timeline

---

## Tech Stack

- Static HTML with Tailwind CSS
- No backend required
- Deployed on Google Cloud Run

---

## Deployment

```bash
gcloud run deploy impact-bonus \
  --source . \
  --region us-central1 \
  --project talent-demo-482004 \
  --allow-unauthenticated
```

---

## Contact

For questions about the Impact Bonus program:
- talent@firstlineschools.org
- hr@firstlineschools.org
