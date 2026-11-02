# NoJam

**Skip the line, not the steps.**

NoJam lets event organisers set up every entry step once: registration, consent, partner sign-ups, swag and forms. Guests finish them before the event, on arrival or after, and door staff scan once to check it all.

Built from a real experience at a Claude Community × Supabase meetup, where guests had to scan three QR codes and create an account in the queue before they could sit down.

## What's in the prototype

- **Build:** a step library and an entry checklist, with settings that open inside each step (questions, photo options, timing, required/optional, verification).
- **Attendee preview:** fill in the checklist as a test guest and watch the pass turn green.
- **Check-in preview:** what door staff see after one scan: green, green with checks, or amber.

This is a clickable front-end prototype. Nothing is saved and no real accounts are checked.

## Run it

It's a single static file. Open `index.html` in a browser, or deploy the repo to Vercel or Netlify with no build step.
