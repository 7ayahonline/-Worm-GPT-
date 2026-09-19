# WORM GPT

A complete static, fictional AI interface with a cyberpunk/underground aesthetic.

## Run
Open `index.html` directly in a modern browser. No build step, backend, API key, or external AI service is required.

## Files
- `index.html` — structure and sections
- `style.css` — responsive visual system and animations
- `app.js` — local demo response engine, chat state, terminal simulation, settings and particles

## Real AI integration
The UI intentionally has no external AI integration. To connect a legitimate provider later, replace/extend `localResponse()` in `app.js` with a server-side request to your own backend. Keep secret API keys off the client.

## Safety
The terminal is a visual simulation only. It does not access networks, devices, accounts, credentials, or targets.
