# Evaluation Guide

Use this page to evaluate whether Gemini Omni Rights Receipt fits a real workflow.

## What To Test

- Gemini Omni commercial rights receipt MCP
- Gemini Omni Rights Receipt
- Gemini Omni Rights Receipt documentation
- Gemini Omni Rights Receipt remote MCP
- geminiomnirights server card

## Expected Evidence

- Open Gemini Omni Rights Receipt and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://geminiomnirights.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call check_video_rights with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.
- Confirm region-specific disclosure and rights decisions with the accountable policy owner.

## Buyer Path

Default plan: team.

- https://geminiomnirights.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=geminiomnirights_public_docs&utm_content=evaluation_checkout
