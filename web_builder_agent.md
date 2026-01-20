# Web Builder Agent - Cost & Credit Documentation

**Agent ID:** web_builder  
**Version:** 1.0.0  
**Last Updated:** 2026-01-20

## Cost Breakdown

| Component               | Model/Service     | Est. Cost (USD) |
| ----------------------- | ----------------- | --------------- |
| Brand Analyst           | Claude Haiku 3.5  | $0.002          |
| Web Designer            | Claude Sonnet 4.5 | $0.029          |
| HTML Developer          | Claude Sonnet 4.5 | $0.234          |
| **Total Internal Cost** |                   | **~$0.31**      |

## Credit Configuration

| Parameter        | Value |
| ---------------- | ----- |
| Internal Cost    | $0.31 |
| External Credits | **8** |
| User Cost        | $0.80 |
| Margin           | ~2.6x |

## Notes

- 3-agent sequential CrewAI workflow (brand analysis → design spec → HTML generation)
- Generates complete, production-ready HTML websites with Tailwind CSS
- Includes modern animations, responsive design, and form integration
- Output is typically 15,000+ tokens (complete HTML files with all sections)
- Supports third-party form integration (Web3Forms, Zoho, etc.)
- Execution time: ~60 seconds (1 minute)
- HTML Developer agent is the most expensive component due to large HTML file generation
