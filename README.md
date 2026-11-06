# Maisha Safety Foundation website

A responsive React + Vite website for Maisha Safety Foundation (MSF), with a text-based identity, programme information, 2026–2027 priorities and contact details.

## Run locally
1. Install Node.js LTS.
2. Extract this folder and open it in Visual Studio Code.
3. In Terminal run `npm install` and then `npm run dev`.
4. Open the local address printed by Vite (usually http://localhost:5173).

## Build
Run `npm run build`. The production site is generated in `dist/`.

## Hosting on Render
The included `render.yaml` describes a static-site deployment. Push this folder to a GitHub repository, connect that repository to Render, and create the service from the Blueprint. Render will run `npm install && npm run build` and publish `dist/`. Add `www.maishasafetyfoundation.org` as a custom domain in Render, then apply the DNS records Render displays at the domain registrar. DNS values must be copied from the live Render dashboard; do not guess them.

## Contact form limitation
The enquiry form prepares an email in the visitor's default email application addressed to `maishasafetyfoundation@gmail.com`. It does not send messages directly or store submissions. A server-side form service or backend must be connected if MSF needs reliable web-based submissions without requiring the visitor's email application.

## Photography and permissions
No AI-generated photographs are included. Photo areas are placeholders. Add Nation Africa / Nation Media Group photographs only after MSF obtains written permission or a valid licence. Alternatively, use photographs supplied by MSF with documented usage rights. Do not download or reuse copyrighted images without permission.

Suggested licensed image filenames:
- `public/images/road-safety.jpg`
- `public/images/community-safety.jpg`
- `public/images/workplace-safety.jpg`

## Before public launch
- Confirm the content against the approved Foundation Profile.
- Obtain and add approved photographs and captions/credits.
- Confirm official Facebook, Instagram and LinkedIn URLs.
- Confirm the enquiry inbox and decide whether a backend form is required.
- Test the production build, mobile layout, links and accessibility.
- Connect the domain and verify HTTPS after DNS propagates.
