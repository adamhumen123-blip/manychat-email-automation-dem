# FlowPilot — ManyChat Email Automation Demo

A client-ready working model that demonstrates how a ManyChat automation can trigger flows from keywords, capture names and email addresses, tag contacts, export leads, and simulate synchronization with an email marketing platform.

## Live demo

After GitHub Pages is enabled for the `main` branch, the project will be available at:

`https://adamhumen123-blip.github.io/manychat-email-automation-dem/`

## Features

- Keyword-triggered chatbot flows
- Create, edit, pause, activate, and delete flows
- Preconfigured `GUIDE`, `PRICE`, and `DEMO` keywords
- Live Instagram DM-style conversation simulator
- Name and email capture with email validation
- Contact tagging and lead-source tracking
- Searchable and filterable contact database
- CSV contact export
- Mailchimp, Klaviyo, ActiveCampaign, Brevo, HubSpot, GoHighLevel, and custom webhook settings
- Manual and automatic synchronization simulation
- Dashboard metrics and activity history
- Browser-based local data persistence
- Responsive desktop and mobile interface

## Test the model

1. Open the live simulator.
2. Enter `DEMO`, `PRICE`, or `GUIDE`.
3. Provide a name and valid email address.
4. Review the captured contact in the Contacts section.
5. Test CSV export and email-platform synchronization.

## Run locally

No installation is required. Download the repository and open `index.html` in a modern browser.

## Production implementation

This proof of concept stores demo data in the browser and simulates external synchronization so it can be reviewed without private credentials. A production version would replace the simulation with authenticated ManyChat, Make, Zapier, webhook, or direct email-platform API integrations.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage
