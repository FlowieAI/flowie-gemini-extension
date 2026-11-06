# Flowie for Gemini CLI

AI procure-to-pay for SMEs to multi-entity groups, from your terminal: build, send and receive compliant e-invoices in **150 countries through Sovos**, and run everything from intake to pay, plus supplier relationship management (SRM).

```bash
gemini extensions install https://github.com/FlowieAI/flowie-gemini-extension
```

The first time Gemini calls a Flowie tool, your browser opens to sign in to Flowie (OAuth 2.1, PKCE). Nothing to configure.

## What you can ask

- "Invoice Acme for 12 hours of consulting at 150 euros."
- "What is waiting for my approval?"
- "Order 20 laptops from our catalog."
- "Which suppliers were onboarded this month?"
- "How much of the marketing budget is left?"
- "Show my top suppliers and spend without a purchase order."
- "Send this UBL invoice and tell me when it is delivered."

## Servers

| Server | URL | For |
|---|---|---|
| `flowie` | `https://back.p2p-flowie.com/agent-hub/mcp` | Working in the Flowie app as yourself: approvals, purchasing, invoices, budgets, suppliers, workflows, reports |
| `flowie-exchange` | `https://back.p2p-flowie.com/exchange/mcp` | High-volume e-invoicing and ERP integrations: send, receive, validate and track e-invoices |

Both are listed on the official MCP Registry as `com.get-flowie/app` and `com.get-flowie/exchange`.

## Links

- Docs: https://docs.get-flowie.com/mcp.md
- Security: https://get-flowie.com/trust (GDPR, EU hosting)
- Website: https://get-flowie.com
