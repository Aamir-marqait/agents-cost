# Content Calendar Agent - Cost & Credit Documentation

**Agent ID:** calendar_generator
**Version:** 5.0.1
**Last Updated:** 2026-01-19

## Cost Breakdown (30-day calendar, ~57 items)

| Phase | Model/Service | Est. Cost (USD) |
|-------|---------------|-----------------|
| 1 - Calendar Architect | GPT-5.2 | $0.15 |
| 2 - Brief Writer | Claude Sonnet 4.5 (×10 batches) | $1.35 |
| **Total Internal Cost** | | **~$1.50** |

## Credit Configuration

| Parameter | Value |
|-----------|-------|
| Internal Cost (30-day) | $1.50 |
| External Credits | **20** |
| User Cost | $2.00 |
| Margin | ~1.3x |

## Scaling Notes
| Duration | Items | Batches | Internal Cost |
|----------|-------|---------|---------------|
| 30 days | ~57 | 10 | $1.50 |
| 60 days | ~114 | 19 | $2.72 |
| 90 days | ~171 | 29 | $4.07 |

## Notes
- Phase 1: GPT-5.2 creates calendar skeleton with reel workflow decisions
- Phase 2: Claude Sonnet 4.5 writes briefs in parallel batches (6 items/batch)
- Output: visual_description, visual_brief, reel_agent_params (with workflow + avatar)
- Execution time: 5-7 minutes for 30-day calendar
- Fixed pricing covers typical 30-day use; longer calendars may exceed cost