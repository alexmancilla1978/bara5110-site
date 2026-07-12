# BARA5110

Website for **BARA5110**, a creative technology studio in San Diego.
Single-file static site (`index.html`) with no build step, so it hosts anywhere.

## Structure

```
.
├── index.html   ← the entire website (HTML, CSS, JS, logo, and photo embedded)
├── README.md
└── .gitignore
```

## The two settings you edit

Open `index.html`, scroll to the bottom `<script>` section, and set these two lines:

```js
const CAL_LINK = "";      // your Cal.com booking link, e.g. "bara5110/discovery-call"
const FORM_ENDPOINT = ""; // the webhook/URL the contact form posts to (goes to Airtable)
```

- **CAL_LINK** powers the branded "Book a discovery call" calendar. Get it from Cal.com after connecting your Google Calendar.
- **FORM_ENDPOINT** powers the "Tell us about your project" form. Point it at a Make.com (or Zapier) webhook that creates a record in Airtable.

Leave either blank to keep the friendly placeholder until you're ready.

## Editing / updating

Change `index.html`, commit, and push. If the repo is connected to a host
(Netlify / Cloudflare Pages / Vercel), the live site redeploys automatically.

## Contact

info@bara5110.com · (619) 340-8944 · San Diego, California
BARA5110 is a creative technology studio under Bara Holdings, LLC.
