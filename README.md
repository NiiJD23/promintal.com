# promintal.com

Official website of Promintal Consulting Limited (registered in London, United Kingdom).

A single self-contained page (`index.html`) with hash-routed pages: Home, Services, Products, About and Contact. Fonts load from Google Fonts; the logo and photography are embedded in the file.

## Deploy (Cloudflare Pages)

1. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git → select this repository.
2. Framework preset: None. Build command: leave empty. Output directory: `/`.
3. Add the custom domain `promintal.com` (and `www.promintal.com`).

## Before going live

- The contact form prepares an enquiry for the visitor to copy; connect it to a form service (for example Formspree or a Cloudflare Worker) to receive submissions directly.
- Add live URLs for CRM, Synesis, Asset Watch and Library in the `PRODUCTS` list inside `index.html` when they are available.
- Confirm licences for all photography.

© Promintal Consulting Limited. All rights reserved.
