# Evaluation Guide

Use this page to evaluate whether Agentic HTML Export QA fits a real workflow.

## What To Test

- agentic HTML export QA MCP
- Agentic HTML Export QA
- Agentic HTML Export QA documentation
- Agentic HTML Export QA remote MCP
- agentichtmlexportqa server card

## Expected Evidence

- Open Agentic HTML Export QA and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://agentichtmlexportqa.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call check_html_export_qa with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://agentichtmlexportqa.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=agentichtmlexportqa_public_docs&utm_content=evaluation_checkout
