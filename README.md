# AQUASENSE — Smart Water Management Website

A premium React + TypeScript website prototype for AQUASENSE, developed by THE THINKERS.

## Run locally
1. Install Node.js (LTS).
2. Open this project folder in a terminal.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL shown in the terminal.

## Build
Run `npm run build`. The production output is created in `dist/`.

## Demo features
- Responsive startup-style website.
- Technology, workflow, applications and product sections.
- Inquiry form saved to this browser's localStorage.
- Feedback form with admin approval before public display.
- Demo admin dashboard.
- Demo admin password: `aqua-demo-2026`.

## Important limitations
This is a frontend demo. Inquiries and feedback are stored only in the browser that submits them. They are NOT automatically sent to the project owner or shared between visitors. The demo admin password is not secure production authentication.

Before accepting real orders or collecting customer data online, connect a backend such as Supabase, configure authentication, database tables and Row Level Security, and add a proper privacy policy. Add a payment provider only after configuring a real merchant account.

The prototype does not claim to treat all industrial pollutants or produce drinking water. Real industrial deployment requires pollutant-specific testing, engineering validation and regulatory compliance.

## Deploy
Recommended: import the repository into Vercel and deploy the Vite project. Build command: `npm run build`; output directory: `dist`.
