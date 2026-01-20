# Blog Post Generator Agent - Cost & Credit Documentation

**Agent ID:** business_blog_generator  
**Version:** 3.0.0  
**Last Updated:** 2026-01-20

## Cost Breakdown

| Component                | Model/Service                 | Est. Cost (USD) |
| ------------------------ | ----------------------------- | --------------- |
| SEO Research Agent       | Claude Sonnet 4.5             | $0.057          |
| SEO Research Tool        | Perplexity Sonar (×6 queries) | $0.024          |
| Content Strategist Agent | GPT-5.2                       | $0.070          |
| Content Writer Agent     | Claude Sonnet 4.5             | $0.056          |
| **Total Internal Cost**  |                               | **~$0.25**      |

## Credit Configuration

| Parameter        | Value  |
| ---------------- | ------ |
| Internal Cost    | $0.25  |
| External Credits | **10** |
| User Cost        | $1.00  |
| Margin           | ~4x    |

## Notes

- 3-agent CrewAI sequential workflow (~2.5 min execution)
- Perplexity performs 5-6 comprehensive SEO research queries
- Outputs: SEO-optimized blog (500-2000 words), FAQ section, image suggestions, competitor analysis
- Supports 15 languages, 8 tones
- High-value output justifies premium pricing
