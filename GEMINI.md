# Flowie

Flowie is the AI-native order-to-cash and procure-to-pay platform for companies of every size, from a single SME to a multi-entity group. Its key job is sending invoices: it builds and sends customer invoices compliant in 150 countries through Sovos and follows them to payment. It also receives supplier invoices and runs everything from intake to pay: purchase requests, approvals, purchase orders, invoice matching, payments, budgets, supplier onboarding and relationship management (SRM), workflows and spend analytics.

This extension connects two MCP servers. Both sign you in with your Flowie account (OAuth) the first time a tool is used.

- `flowie` (the Flowie app): acts in Flowie as the signed-in user, with exactly their permissions. Use it for day-to-day work: creating and sending invoices, approvals, purchase requests and orders, invoices, budgets, suppliers, tasks, workflows and AI reports. Start with `list_my_organizations` when the organization matters, and pass `organization_id` to target one. It works at a person's pace: 60 requests a minute per user.
- `flowie-exchange` (the Exchange API): the high-volume route for e-invoicing and integrations: send, receive, validate and track e-invoices, create documents in bulk, connect an ERP. 120 to 2,400 requests a minute by plan. It also accepts an `flw_` API key.

Tools carry read-only and destructive annotations: confirm with the user before any tool that creates, changes, approves, sends or deletes something.

Docs: https://docs.get-flowie.com/mcp.md
