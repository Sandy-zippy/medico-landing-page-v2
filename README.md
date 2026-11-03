# Medico landing page, version 2 (book a call)

Copy of medico-clinic-lp (live at build.medicoconstruction.com) for the appointment-setting rebuild.
No CNAME: it can't take the live address. Off the live address it sends no leads and fires no Google, Meta or Clarity tags.
To go live: merge into medico-clinic-lp after sign-off, with the cal.com event swapped in (thank-you.html BOOKING_URL).

## Original notes

Static page for Google Search traffic (medical clinic construction, BC + Alberta).
Spec: `BRIEF.md` (Sandy's locked brief, 24 Sep 2026). Keyword map: `../ads/KEYWORD-PLAN-MEDICO-v3-2026-09-23.md`.

- `index.html`, `styles.css`, `app.js`: the whole page. No build step, no framework.
- `assets/img/`: real Medico project photos, resized from their portfolio originals.
- Form lead destination is connected LAST (after design sign-off). Until then `app.js` refuses to send.

Hosting: GitHub Pages only.
