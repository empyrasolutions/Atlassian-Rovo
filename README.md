# Atlassian AI Feature Audit

A checklist for auditing how well your already-active Atlassian AI features
are actually performing — for teams past the activation stage, checking
whether the features are working as intended six months in.

## Why this matters

AI features that were accurate at rollout can quietly drift as ticket
patterns, team structure, or documentation change. This isn't a
readiness checklist — it's a post-activation health check.

## 1. AI ticket triage
- [ ] Pull a sample of recent auto-triaged tickets and spot-check accuracy
- [ ] Check whether request-type categories have changed since triage was configured
- [ ] Review the "Emailed request" bucket — is it shrinking or growing?

## 2. Virtual agent / deflection
- [ ] Calculate actual deflection rate: resolved-by-agent vs. escalated-to-human
- [ ] Sample a handful of deflected conversations for genuine resolution vs. false completion
- [ ] Confirm which channels are covered (Slack, Teams, email) vs. which teams assume are covered

## 3. Sentiment insights
- [ ] Check whether sentiment scoring is actually being used to reprioritize anything, or just displayed and ignored
- [ ] Spot-check a few high-negative-sentiment tickets — did they get escalated appropriately?

## 4. Knowledge base / AI suggestions
- [ ] Audit the top 10 most-suggested articles for accuracy and last-updated date
- [ ] Check for suggestion loops pointing to outdated or superseded content

## 5. Rovo agents (if active)
- [ ] Confirm which agents are custom-built vs. still using defaults
- [ ] Review usage data — are agents actually being invoked, or configured and ignored?

---

Built by [Empyra](https://www.empyra.com/atlassian-ai-consulting?utm_source=github&utm_medium=referral&utm_content=N),
an Atlassian Platinum & Enterprise Solution Partner.
