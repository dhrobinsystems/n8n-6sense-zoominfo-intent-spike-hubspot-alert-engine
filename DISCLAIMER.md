# ⚠️ Disclaimer & Liability Limitation

**Repository:** `n8n-6sense-zoominfo-intent-spike-hubspot-alert-engine`
**Author:** DH Robin (dhRobin Systems)
**Last updated:** November 2026

Use at your own risk. The code, workflows, and scripts in this repository (`n8n-6sense-zoominfo-intent-spike-hubspot-alert-engine`) are provided for educational and architectural demonstration purposes.

* **No Liability:** The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. That includes, without limitation, intent surges that are missed, delayed, duplicated or misclassified, accounts matched to the wrong HubSpot company or tier, tasks assigned to the wrong person or not created, unwanted or mistimed outreach, lost revenue, API or data-licence charges, and any record created or changed in a connected system.

* **No Warranty:** All software, n8n JSON blueprints and JavaScript modules are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement. Intent data is probabilistic. The surge thresholds, stage ordering, tier rules, domain matching and redaction patterns are illustrative defaults and are not guaranteed to be correct for your data.

* **Production Testing Required:** Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox and a test Slack channel, with `SANDBOX_MODE=true` and `DRY_RUN=true` enabled, before you connect live HubSpot, 6sense, ZoomInfo or Slack credentials. Treat every intent surge as a research signal that a person must judge before acting on it, not as a confirmed buying decision.

* **Not Consent to Contact:** Intent signals describe aggregated, account-level research activity. They don't show that any individual is interested in your product or has agreed to be contacted. Don't use them to profile, target or make decisions about individual people.

* **Third-Party APIs & Compliance:** You alone are responsible for complying with the terms of service, rate limits, data-licensing terms, data privacy regulations (GDPR/CCPA and others), e-mail, telephone and anti-spam rules, and security policies of 6sense, ZoomInfo, HubSpot, Slack and any connected services. That includes confirming your intent-data licence permits this use, keeping personal data out of alerts, tasks and logs, honouring opt-outs, restricting access to n8n executions and alert channels, and reviewing every automatically created or updated record.

* **No Affiliation:** This project is independent. It is not affiliated with, endorsed by, or sponsored by 6sense Insights, Inc., ZoomInfo Technologies Inc., HubSpot, Inc., Slack Technologies, LLC, Salesforce, Inc., or n8n GmbH. All product names and trademarks belong to their respective owners and are used only to describe compatibility.

* **Fictional Sample Data:** All company names, domains (under the reserved `.example` suffix), account and record IDs, owner IDs, intent topics, scores, stages and secrets in the pinned sample data and documentation are fictional and exist only for testing. Any resemblance to real organisations is coincidental. Placeholder values such as `YOUR_WEBHOOK_SECRET`, `YOUR_ZOOMINFO_WEBHOOK_TOKEN`, `YOUR_HUBSPOT_PRIVATE_APP_TOKEN`, `YOUR_HUBSPOT_PORTAL_ID`, `YOUR_FALLBACK_OWNER_ID` and `YOUR_SLACK_WEBHOOK_URL` must be replaced with your own values, which you keep in environment variables or n8n credentials.

* **Not Professional Advice:** Nothing in this repository is legal, privacy, compliance or sales-strategy advice. Consult qualified professionals for decisions in those areas.

## Open-Source License Notice

This project is released under the MIT License. You may use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the conditions in [LICENSE](./LICENSE). The MIT License's own warranty disclaimer and limitation of liability apply in addition to this document. If the two conflict, the terms more protective of the author apply to the extent permitted by law.

---

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 DH Robin (dhRobin Systems) · Provided as-is, see the disclaimer.
