# Contributing to HNS Pool Accountability Tracker

Thank you for helping keep this record accurate and useful for the HNS community.

---

## Ground Rules

1. **Facts only.** Every claim must have a verifiable source — a dated announcement, a hashrate chart, a forum post, or an on-chain reference.
2. **No personal attacks.** This is about pool behavior, not individuals.
3. **No speculation.** "I heard that..." is not acceptable. Link to evidence.
4. **Be fair.** If a pool exited and later returned with explanation, record both facts.

---

## How to Add or Update a Pool Record

### Option A — Open an Issue (easiest)

1. Go to **Issues → New Issue**
2. Select the **Pool Event Report** template
3. Fill in all fields with as much evidence as possible
4. A maintainer will review and create/update the pool file

### Option B — Submit a Pull Request

1. Fork this repository
2. Copy the pool template below into `data/pools/POOLNAME.md`
3. Fill in all known information
4. Open a PR with a clear description and your evidence links

---

## Pool File Template

```markdown
# [Pool Name] — Pool Accountability Record

**Pool Website:** https://...  
**Loyalty Score:** ⭐ (X/5)  
**Current Status:** ✅ Active | ❌ Exited | ⚠️ Unknown

---

## Summary

[1-2 sentences describing the pool's overall HNS behavior]

---

## Timeline of Events

| Date | Event | HNS Price (approx.) | Source |
|------|-------|---------------------|--------|
| YYYY-MM | [Event description] | $X.XX | [Link] |

---

## Evidence & Sources

- [Link to announcement or source]
- [Link to hashrate chart]
- [Link to community discussion]

---

*Last updated: YYYY-MM | To update this record, open a Pull Request with evidence.*
```

---

## Scoring Guide

| Score | Criteria |
|-------|----------|
| ⭐⭐⭐⭐⭐ | Never exited, maintained hashrate through all downturns, communicated proactively |
| ⭐⭐⭐⭐ | Minor disruptions only, always communicated with miners |
| ⭐⭐⭐ | Reduced operations temporarily, returned and explained |
| ⭐⭐ | Exited without notice, returned later |
| ⭐ | Exited during downturn, never returned |

Scores are determined by community consensus and maintainer review, not by individuals.

---

## What Counts as Evidence

✅ Accepted:
- Official pool announcements (with date + URL)
- Screenshots of pool pages going offline (with date)
- Network hashrate charts from reputable sources (hns.tools, poolwatch, etc.)
- Forum/Discord posts from pool operators (with date + link)
- On-chain data showing pool hashrate drop

❌ Not accepted:
- Rumors or hearsay
- Anonymous claims without corroboration
- Price speculation or predictions

---

## Maintainers

This repository is maintained by volunteer community members. If you'd like to become a maintainer, open an issue.
