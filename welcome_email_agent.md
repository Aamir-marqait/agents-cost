# Welcome Email Sequence Generator - Cost & Credit Documentation

**Agent ID:** welcome_email_generator  
**Version:** 1.0.0  
**Last Updated:** 2026-01-20

## Cost Breakdown

| Component | Model/Service | Est. Cost (USD) |
|-----------|---------------|-----------------|
| Email Research Agent | Claude Sonnet 4.5 | $0.155 |
| Research Tool (5 queries) | Perplexity Sonar Pro | $0.130 |
| Email Sequence Architect | Claude Sonnet 4.5 | $0.183 |
| Email Copywriter | Claude Sonnet 4.5 | $0.312 |
| Email Optimizer | GPT-5.2 | $0.175 |
| **Total Internal Cost** | | **~$1.10** |

## Credit Configuration

| Parameter | Value |
|-----------|-------|
| Internal Cost | $1.10 |
| External Credits | **25** |
| User Cost | $2.50 |
| Margin | ~2.3x |

## Notes
- 4-agent sequential CrewAI workflow (research → architect → copywriter → optimizer)
- Perplexity performs 5 comprehensive research queries (industry benchmarks, tactics, subject lines, psychology, trends)
- Writes 3-7 complete emails in 3 formats each (HTML, Markdown, Plain Text)
- Includes A/B test variants, deliverability analysis, ESP automation guides
- Execution time: ~3 minutes (180 seconds)
- Highest-cost agent due to extensive research and multi-format email generation