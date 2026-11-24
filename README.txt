BRAINLESS MINDS — CLOUDFLARE PAGES STATIC WEBSITE

Files
- index.html       Main homepage
- styles.css       Responsive styling
- script.js        Mobile navigation and footer year
- assets/favicon.svg

DEPLOY WITH CLOUDFLARE PAGES (DIRECT UPLOAD)
1. Sign in to https://dash.cloudflare.com/
2. Open Workers & Pages.
3. Choose Create application > Pages > Direct Upload (the exact dashboard wording may vary).
4. Create a project named brainlessminds.
5. Upload the contents of this folder (or the ZIP archive) and deploy.
6. Test the generated *.pages.dev address.

CONNECT brainlessminds.com
1. In the Pages project, open Custom domains > Set up a domain.
2. Enter brainlessminds.com and follow Cloudflare's instructions.
3. For an apex domain, Cloudflare requires the domain to be added as a Cloudflare zone and its nameservers pointed to Cloudflare.
4. IMPORTANT: Before changing nameservers, inspect the existing DNS zone and preserve all email-related records (MX, SPF, DKIM, DMARC) and any other records you need. Do not delete records blindly.

NOTES
- This is a static website and does not require a build command or framework.
- The contact link currently points to hello@brainlessminds.com. Confirm that this mailbox exists or change the address in index.html.
- The guide cards are launch placeholders marked Coming soon; publish real articles before promoting them.
- Google Fonts are loaded externally. If you prefer no third-party font requests, remove the Google Fonts links from index.html; the site will fall back to sans-serif fonts.
- This package does not configure your Cloudflare account or change DNS automatically.
