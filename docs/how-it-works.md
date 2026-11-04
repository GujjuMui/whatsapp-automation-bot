# How it works

A plain-language overview. No code, no credentials, no customer data.

## The pieces

- **WhatsApp** — where the customer messages the business.
- **The bot** — reads the incoming message, shows the service menu, answers from the business's rules, and creates support tickets when needed. The bot itself is private and is not in this repository.
- **The dashboard** — where the business sends broadcasts, manages auto-reply rules, and replies to support tickets. The dashboard is password-protected in the live system.

## A customer journey

```text
Customer: "Hi"
Bot:      Shows the service menu

Customer: Taps a service
Bot:      Shows the details for that service,
          with options to talk to support or go back to the menu

Customer: Chooses support
Bot:      Asks for a short subject, then the details
          Creates a support ticket and pauses automated replies
          for that customer until the ticket is closed

Team:     Replies from the dashboard and closes the ticket
Bot:      Resumes the normal menu for that customer
```

## Auto-replies

The business sets keyword triggers and the reply for each one. When a customer's message matches a trigger, they get that reply automatically. Matching is done on whole words, so a keyword does not fire inside an unrelated word.

## Broadcasts

A broadcast is a single message sent to chosen customers from the dashboard. It is for announcements and follow-ups to people the business already serves — not for cold bulk messaging.

## Limits worth knowing

- Replies outside WhatsApp's 24-hour customer-service window need an approved template message instead of free text. This is a WhatsApp rule, not a choice in the bot.
- Messaging limits and business verification are handled through WhatsApp / Meta, per the business's account.
