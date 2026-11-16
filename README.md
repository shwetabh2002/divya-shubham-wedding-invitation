# Divya & Shubham wedding invitation

Personalized static invitation for 11 December 2026 in Jaipur.

## Run locally

Python 3 is the only local requirement. From this repository:

```sh
python3 -m http.server 8765 --bind 127.0.0.1 --directory dist
```

Open http://127.0.0.1:8765. Stop the server with Ctrl+C.

## Edit

- `dist/index.html`: names, family details, schedule, venue, RSVP and page markup.
- `dist/assets/`: styles, scripts, images, fonts and opening video.
- `.openai/hosting.json`: existing Sites deployment configuration.

No build or npm install is required. Maps, WhatsApp RSVP and external calendar links require internet access. RSVP opens a WhatsApp draft; guests must send it themselves.

Design and media follow the supplied MyInvitations Shubh Aarambh reference; this repository does not grant rights to redistribute third-party assets. The template gallery images remain from the reference.
