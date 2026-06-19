# Methodology — How We Verify & Score Pool Behavior

This document explains how the HNS Pool Accountability Tracker collects, verifies, and scores pool behavior reports.

---

## Principles

**Transparency over opinion.** We record what happened, when it happened, and what the evidence shows. We do not speculate about motives.

**Fairness to all pools.** A pool that exited but communicated clearly and returned is treated differently from one that vanished without a word. The record reflects the full picture.

**Community-driven, maintainer-reviewed.** Anyone can submit a report. Maintainers verify evidence before adding it to the official record.

---

## What Counts as a "Bear Market Exit"

A pool is recorded as having exited HNS mining during a downturn when:

- The pool's HNS mining page goes offline or hashrate drops to zero
- This coincides with a period of sustained low HNS price (subjective, but generally below the pool's operational break-even)
- The pool does not announce a return timeline

A pool that temporarily pauses for maintenance and returns within 2 weeks is **not** counted as a bear market exit.

---

## Evidence Standards

### Tier 1 — Strong Evidence
- Official pool announcement with date and URL
- On-chain hashrate data from a reputable source (hns.tools, etc.) showing pool hashrate going to zero
- Pool mining page confirmed offline by multiple community members

### Tier 2 — Supporting Evidence
- Forum or Discord posts from pool operators
- Community reports corroborated by at least 2 independent sources
- Screenshots with verifiable metadata

### Tier 3 — Weak (not sufficient alone)
- Single community report without corroboration
- Secondhand accounts

**A Tier 3 source alone is not enough to add a negative entry to a pool record.** It may be noted as "unverified" pending further evidence.

---

## Scoring Rubric Detail

### ⭐⭐⭐⭐⭐ (5 stars)
- Has never exited HNS mining
- Maintained or increased hashrate during at least one documented bear market
- Has public communication channels and responds to miners

### ⭐⭐⭐⭐ (4 stars)
- No exits, but minor disruptions (brief downtime, delayed payouts) with communication
- OR: One brief exit (<2 weeks) with clear advance notice and explanation

### ⭐⭐⭐ (3 stars)
- Reduced support or partial exit during a downturn
- Returned to full operation afterward
- Communicated with miners during the disruption

### ⭐⭐ (2 stars)
- Exited HNS mining during a bear market without advance notice
- Returned after conditions improved
- No formal explanation given to miners

### ⭐ (1 star)
- Exited HNS mining during a bear market
- Has not returned
- Did not communicate with miners about the exit

---

## Dispute Process

If a pool believes their record is inaccurate:

1. Open an issue titled `[DISPUTE] Pool Name — Specific Claim`
2. Provide counter-evidence (Tier 1 or Tier 2 only)
3. Maintainers will review and update the record if the evidence supports it

Pool operators are welcome and encouraged to participate. A pool that actively engages with this repository and provides clear explanations will have that noted positively in their record.

---

## Update Frequency

Pool records should be reviewed and updated:
- When a major price movement occurs (significant up or down)
- When a pool makes a public announcement about HNS support
- When community members submit verified reports

---

*This methodology is itself open to community feedback. Open an issue if you believe it should be changed.*
