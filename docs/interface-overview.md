# Interface overview

This describes, at a high level, how the private system is organised. It is documentation only — there is no runnable code here, and the names below are illustrative.

## Illustrative structure

```text
webhook        Receives incoming WhatsApp messages and delivery updates
menu           Builds the service list and service-detail replies
support        Creates tickets, pauses the bot for a customer, resumes on close
rules          Keyword triggers and automated replies
dashboard      Broadcasts, rules, tickets, and connection status (password-protected)
```

## Illustrative message flow

```text
WhatsApp -> webhook -> menu / rules / support -> WhatsApp reply
Dashboard -> broadcasts / ticket replies -> WhatsApp
```

## Example exchange (illustrative, not real customer data)

```text
Customer: Hi
Bot:      Here are our services: [Service A] [Service B] [Talk to support]

Customer: [Service A]
Bot:      <details for Service A>
          [Talk to support] [Main menu]

Customer: [Talk to support]
Bot:      What is this about, in one line?
Customer: <subject>
Bot:      Thanks — please share the details.
Customer: <details>
Bot:      Done. Your ticket is T-1001. Our team will reply here.
```

## What is deliberately not in this repository

- Source code (server, webhook handlers, dashboard pages)
- Environment files, tokens, secrets, IDs, or phone numbers
- Customer data, tickets, or message history
- Deployment configuration for the live system
