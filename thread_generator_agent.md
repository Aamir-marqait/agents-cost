# Thread/Tweet Storm Generator - Cost & Credit Documentation

**Agent ID:** thread_generator  
**Version:** 1.0.0  
**Last Updated:** 2026-01-20

## Cost Breakdown

| Component | Model/Service | Est. Cost (USD) |
|-----------|---------------|-----------------|
| Trend Research Agent | Claude Sonnet 4.5 | $0.138 |
| Research Tool (4 queries) | Perplexity Sonar Pro | $0.104 |
| Thread Writer Agent | Claude Sonnet 4.5 | $0.210 |
| Viral Optimizer Agent | GPT-5.2 | $0.138 |
| **Total Internal Cost** | | **~$0.68** |

## Credit Configuration

| Parameter | Value |
|-----------|-------|
| Internal Cost | $0.68 |
| External Credits | **14** |
| User Cost | $1.40 |
| Margin | ~2x |

## Notes
- 3-agent sequential CrewAI workflow (research → writing → optimization)
- Perplexity performs 4 comprehensive research queries per execution
- Supports guided mode (user topic) and autonomous mode (AI finds trending topics)
- Outputs complete viral-ready threads with hook variants, posting times, engagement tips
- Execution time: ~90 seconds (1.5 minutes)