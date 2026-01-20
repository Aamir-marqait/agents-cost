# Google Ads Copy Generator - Cost & Credit Documentation

**Agent ID:** google_ads_generator  
**Version:** 1.1.0  
**Last Updated:** 2026-01-20

## Cost Breakdown

| Component | Model/Service | Est. Cost (USD) |
|-----------|---------------|-----------------|
| Research Agent | Claude Sonnet 4.5 | $0.0735 |
| Research Tool | Perplexity Sonar | $0.0033 |
| Copywriter Agent | Claude Sonnet 4.5 | $0.1080 |
| **Total Internal Cost** | | **~$0.21** |

## Credit Configuration

| Parameter | Value |
|-----------|-------|
| Internal Cost | $0.21 |
| External Credits | **6** |
| User Cost | $0.60 |
| Margin | ~2.86x |

## Notes
- 2-agent sequential CrewAI workflow (45-90 seconds)
- Perplexity research for dynamic industry insights
- Outputs: 15 short headlines, 5 long headlines, 5 descriptions, extensions
- Multi-language support (15 languages)
- Strict character limit enforcement