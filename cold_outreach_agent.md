# Cold Outreach Email Generator - Cost & Credit Documentation

**Agent ID:** cold_outreach_generator  
**Version:** 1.0.0  
**Last Updated:** 2026-01-20

## Cost Breakdown

| Component | Model/Service | Est. Cost (USD) |
|-----------|---------------|-----------------|
| Prospect Research Agent | Claude Sonnet 4.5 | $0.069 |
| Research Tool (5-6 queries) | Perplexity Sonar Pro | $0.130 |
| Email Copywriter Agent | Claude Sonnet 4.5 | $0.138 |
| Outreach Optimizer Agent | GPT-5.2 | $0.102 |
| **Total Internal Cost** | | **~$0.50** |

## Credit Configuration

| Parameter | Value |
|-----------|-------|
| Internal Cost | $0.50 |
| External Credits | **11** |
| User Cost | $1.10 |
| Margin | ~2.2x |

## Notes
- 3-agent sequential CrewAI workflow
- 5-email B2B sequence with research, A/B tests, compliance
- Perplexity performs 5-6 comprehensive research queries
- Highest-cost agent due to extensive Perplexity research ($0.13 alone)