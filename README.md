# Ek kadam Organization — NGO Engagement Workflow

A no-code engagement webpage and workflow for an NGO, covering volunteer
recruitment, donations, and event participation in a single connected page.

## Live Demo
https://kanav-codes.github.io/Ek kadam-ngo/

## Features

- **Landing page** with live impact stats: volunteers onboard, funds raised,
  and event RSVPs — updates in real time as forms are used.
- **Three interactive forms**: Volunteer Signup, Donation Pledge, and Event RSVP.
- **Community Ledger**: a visual record where every demo submission appears
  as an entry, showing how individual actions add up to collective impact.
- **Automations panel**: toggles showing how each submission connects to a
  spreadsheet log, calendar scheduling, and email confirmations.
- **Real data capture**: each form section links to a live Google Form,
  connected to a Google Sheet, so real submissions are automatically logged.
- **CSV export**: download a record of all demo ledger entries.

## How it works

1. A visitor fills in a form on the website (demo) or clicks through to the
   linked Google Form (real data capture).
2. The Google Form response is automatically logged to a Google Sheet.
3. The website's ledger and stats update live to reflect new activity
   (demo mode).

## Future Work

- Connect the Google Sheets to Zapier/Make to automatically send confirmation
  emails and create calendar invites for event RSVPs.
- Replace demo/simulated automation indicators with live status pulled from
  the connected automation tool.
- Add a payment gateway integration for real donation processing.
- Add an admin view to see live counts pulled directly from the Google Sheets.
- Embed the Google Forms directly into the page (instead of linking out) for
  a fully seamless experience.

## Disclaimer

This project was built with the assistance of AI tools as part of a no-code
development task. The webpage (HTML/CSS/JS) was AI-generated and customized
for Ek kadam Organization's branding and content. Google Forms and Sheets
were set up manually to handle real data capture.
