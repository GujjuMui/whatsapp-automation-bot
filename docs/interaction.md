# The 3D interactive chat

One part of the landing page, described on its own — the full page is not in this repository.

## What you see

A phone frame on the right of the landing page, showing a WhatsApp-style demo chat with a business assistant. The phone does not sit flat: it floats gently and tilts in 3D as the mouse moves, with the chat panel and the "Auto-reply · On" chip sitting at different depths, so the phone feels like an object rather than a flat picture.

## How it behaves

- **Float** — the phone drifts slowly on a loop (about 8 seconds), tilting a few degrees in each direction.
- **Mouse tilt** — moving the mouse rotates the whole scene a little (perspective, with the phone and chip offset forward). The movement is smooth, with a short transition, so it follows the cursor without snapping.
- **Typing pause** — while the chat input is focused, the mouse tilt pauses, so the phone stays still while someone types.
- **Demo chat** — the chat inside the phone is seeded with a short conversation: a welcome message, a "View options" list, pricing and demo questions with answers, and a closing message. Tapping "Play demo conversation" replays it. Typing and sending one message moves the visitor forward, showing a "You're ready to automate" card with the setup steps.
- **Background** — the same faint doodle pattern as the dashboard sits behind everything, on a near-black background, with glass cards blurred over it.

## What is deliberately not included

The full landing page file, its complete styling and chat logic, the dashboard, and any backend code are private and are not in this repository. This note describes only the interaction behaviour above.
