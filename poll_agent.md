# Poll Agent - Cost & Credit Documentation

**Agent ID:** poll_generator  
**Version:** 1.0.0  
**Last Updated:** 2026-01-20

## Cost Breakdown

| Component | Model/Service | Est. Cost (USD) |
|-----------|---------------|-----------------|
| Poll Strategist | Claude Haiku 3.5 | $0.0040 |
| Question Crafter | Claude Sonnet 4 | $0.0120 |
| **Total Internal Cost** | | **~$0.018** |

## Credit Configuration

| Parameter | Value |
|-----------|-------|
| Internal Cost | $0.018 |
| External Credits | **5** |
| User Cost | $0.50 |
| Margin | ~27.8x |

## Notes
- 2-agent sequential CrewAI workflow (~20-40 seconds)
- No external tools (pure content creation)
- Generates 1-5 poll variants with strategic analysis
- Supports 6 platforms (Instagram, Twitter, LinkedIn, Facebook, YouTube, TikTok)
- Platform-optimized output with character limit compliance
- Multiple poll types (multiple_choice, yes_no, rating_scale, this_or_that, ranking)