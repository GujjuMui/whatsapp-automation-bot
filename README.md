# WhatsApp Automation

A WhatsApp automation bot for businesses that want every customer message answered quickly, without a team sitting on WhatsApp all day.

> **This repository is a public overview only.** It does not contain the bot's source code, configuration, credentials, or customer data. The implementation is private.

## Visuals

Artwork taken from the real interface — the background doodle pattern and the chat mark used in the landing page and dashboard. The pattern is faint by design: it sits behind the glass cards on the near-black interface background.

![Background doodle pattern](assets/doodle-pattern.svg)

![Chat mark](assets/whatsapp-mark.svg)

Full-page screenshots of the landing page and dashboard are not included yet — they need to be captured from a running copy of the interface. The artwork above is the exact pattern and mark from that interface, not a redraw.

## What it does

- **Instant replies, 24/7** — a customer sends any message and gets a helpful response straight away.
- **Service menu** — customers see the business's services, tap one, and get the details for it.
- **Support handover** — when a customer needs a person, they can share a subject and their query. It becomes a support ticket for the team to reply to and close.
- **Broadcasts** — send an announcement or follow-up to customers from one place.
- **Auto-replies** — keyword-based replies for common questions, so repeat questions don't need a manual answer every time.
- **Dashboard** — one quiet place to see connection status, send messages, manage auto-reply rules, and handle support tickets.

## How a conversation works

1. A customer messages the business on WhatsApp.
2. They see a list of services and choose one — or ask for support.
3. They get the details for the service they chose.
4. If they choose support, they share a short subject and their query. The bot pauses for that customer while the team handles the ticket, and resumes once the ticket is closed.

No customer data, phone numbers, or message contents are stored in this repository.

## Who it's for

Businesses that get repeat questions on WhatsApp and want faster, more consistent replies — without giving customers a clunky form or a long wait.

## Services

The exact services shown in the menu depend on the business using it.

<!-- Replace the list below with the business's real services when ready. -->
<!-- Keep each service to: name, one short line, and the details a customer sees after tapping it. -->

- Service 1 — _to be added_
- Service 2 — _to be added_
- Service 3 — _to be added_

## Get started

This service is set up for each business individually. To enquire:

<!-- Add your preferred contact here before sharing the repo publicly. -->
- Contact: _to be added_

## Privacy and security

- No credentials, tokens, phone numbers, or customer data are published here.
- The live system keeps its credentials in local environment configuration only — never in a public repository.
- The dashboard is password-protected in the live system.

See [`docs/how-it-works.md`](docs/how-it-works.md) for a plain-language overview of the flow.
