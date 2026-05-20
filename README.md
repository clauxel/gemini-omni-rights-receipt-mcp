# Gemini Omni Rights Receipt

Gemini Omni Rights Receipt is a hosted remote MCP for Gemini Omni commercial rights receipt MCP.

This repository is a public documentation project for Gemini Omni Rights Receipt. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://geminiomnirights.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=geminiomnirights_public_docs&utm_content=readme_home
- Pricing: https://geminiomnirights.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=geminiomnirights_public_docs&utm_content=readme_pricing
- Checkout: https://geminiomnirights.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=geminiomnirights_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://geminiomnirights.clauxel.com/mcp
- Server card: https://geminiomnirights.clauxel.com/server-card.json
- Registry name: `com.clauxel.geminiomnirights/geminiomnirights-mcp`
- Tools: `check_video_rights`, `issue_rights_receipt`, `flag_missing_disclosure`, `summarize_asset_sources`, `export_client_receipts`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI governance teams, policy reviewers, trust and safety leads, and compliance operators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: check_video_rights
- MCP tool: issue_rights_receipt
- MCP tool: flag_missing_disclosure
- MCP tool: summarize_asset_sources
- MCP tool: export_client_receipts

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
