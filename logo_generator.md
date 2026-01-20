# Logo Generator Agent - Cost & Credit Documentation

**Agent ID:** logo_generator
**Version:** 2.1.0
**Last Updated:** 2026-01-19

## Cost Breakdown

| Component | Model/Service | Est. Cost (USD) |
|-----------|---------------|-----------------|
| Brand Strategist Agent | GPT-4.1 Mini | $0.007 |
| Logo Designer Agent | GPT-4.1 Mini | $0.0054 |
| Brand Analyst Agent | GPT-4.1 Mini | $0.0096 |
| Prompt Refinement | Claude Sonnet 4.5 | $0.0159 |
| Image Generation | fal-ai/nano-banana | $0.039 |
| **Total Internal Cost** | | **~$0.08** |

## Credit Configuration

| Parameter | Value |
|-----------|-------|
| Internal Cost | $0.08 |
| External Credits | **2** |
| User Cost | $0.20 |
| Margin | ~2.5x |

## Notes
- Sequential CrewAI process with 3 agents
- Single 1024x1024 PNG logo output (cloud URL)
- Includes Claude-powered prompt refinement for quality