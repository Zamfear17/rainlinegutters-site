# Rainline Gutters — website

Static, mobile-responsive site for Rainline Gutters, a Tampa Bay seamless-gutter company and a sister brand to Rainier Roofing.

## Pages

- `index.html` — homepage
- `services.html` — seamless K-style, half-round, downspouts, guards, repairs, cleaning, fascia/soffit, hangers
- `about.html` — brand story and Rainier Roofing tie-in
- `areas.html` — Hillsborough, Pinellas, and Pasco service areas
- `contact.html` — free-quote form
- `faq.html` — common questions
- `css/styles.css` — shared stylesheet
- `favicon.svg` — brand mark

The site works when opened as local files and when hosted at the domain root. Planned production URL: https://www.rainlinegutters.com/

## Placeholders to replace before launch

Search the HTML files for these strings and replace them with real values. Do not publish the site until they are filled in.

| Placeholder | What to put there |
| --- | --- |
| `[PHONE]` | Business phone, including `tel:` links |
| `[EMAIL]` | Business email, including `mailto:` links |
| `[ADDRESS]` | Street address |
| `[CITY_STATE_ZIP]` | City, state, ZIP |
| `[LICENSE]` | The contractor license number that must appear in ads (and on marked vehicles) |
| `[HOURS]` | Business hours |
| `[WARRANTY]` | Only if a named warranty is offered; otherwise keep the “terms in writing with each proposal” language |
| `[FORM_ENDPOINT]` | Your Formspree form ID (or switch the form action to FormSubmit.co) |

The contact form posts to `https://formspree.io/f/[FORM_ENDPOINT]`. Create a free Formspree form, paste the ID in, and remove or update the on-page note that delivery is not active. Until that is done, the page will not email quote requests.

Also replace the same placeholders inside each page’s JSON-LD script.

## Publish for free

Any of these will host the folder at no charge:

1. **Netlify Drop** — go to https://app.netlify.com/drop and drag this folder. You get a `*.netlify.app` URL immediately. Then add `rainlinegutters.com` as a custom domain after the domain is purchased.
2. **Cloudflare Pages** — https://pages.cloudflare.com — upload or connect a Git repo, then attach the custom domain (Cloudflare can also host the DNS for free).
3. **GitHub Pages** — put these files in a public repository, enable Pages from the main branch, and point GoDaddy DNS at GitHub as described in `Rainline_Setup_Plan.docx`.

Do not buy the domain or change live DNS until the owner approves the purchase. After the domain is at GoDaddy, create only the DNS records the chosen host asks for. Enable HTTPS on the host, and do not point the same name at GoDaddy Website Builder at the same time.

## Alternative

GoDaddy Airo / Website Builder can build a site on the domain, but it is not required. This folder is already a complete free site.
