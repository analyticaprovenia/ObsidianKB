---
tags: [business, tech, open-cloud, deidentification, data, ai]
date: 2026-05-24
---

# Open Cloud — De-identification Pipeline

## Goal
Download Open Cloud and integrate a de-identification layer so data can be processed/shared safely. Claude one-shots the integration.

## Tasks
- [ ] Download Open Cloud
- [ ] Map where de-identification needs to slot in (input pipeline)
- [ ] Claude: one-shot the de-identification integration
- [ ] Test end-to-end: data in → de-identified → processed → out
- [ ] Make it locally hosted (ties into home server build)

## Business Plan

### Problem
Businesses and individuals want to use AI and cloud services but can't safely send sensitive/personal data to external providers. There's no easy plug-in layer that strips PII before data leaves.

### Solution
Open Cloud with a de-identification pipeline baked in — data goes in, PII is stripped, then it's processed or shared safely. Self-hosted, private, nothing leaves the local network.

### Target Customers
- Small businesses needing GDPR/Privacy Act compliance
- The business network (see [[Business Concepts]]) — shared data, pooled insights, without privacy risk
- Healthcare, legal, finance sectors — high sensitivity, high willingness to pay

### Revenue Model
- SaaS tier for the de-identification layer (charge per GB processed or per seat)
- Consulting: set it up for businesses who can't do it themselves
- Data brokering with privacy layer — sell anonymised insights, not raw data

### Competitive Advantage
- Self-hosted = no third-party risk
- One-shot Claude integration = fast setup for non-technical users
- Ties into the broader business network / anti-monopoly platform

### Milestones
1. [ ] Working local prototype (Open Cloud + de-ID pipeline)
2. [ ] Claude one-shots the integration for a test dataset
3. [ ] Document it well enough for a non-technical business owner to use
4. [ ] Package as a product / offer to first business network members
5. [ ] Build SaaS wrapper around it

---

## Notes
- De-identification = strip PII before data hits any model or external service
- Aim: self-hosted, private, no data leaving the local network
- Could become a product/service for the business network (data brokering with privacy layer)

## Links
- [[Master Todo]]
- [[Business Concepts]] — data brokering / MCP data platform SaaS
