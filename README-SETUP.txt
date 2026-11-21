CHEVYPARTS101 — CUSTOM WEBSITE STARTER
======================================

WHAT'S INCLUDED
- index.html (Home)
- carburetor-services.html
- free-downloads.html
- about.html
- contact.html
- assets/ (logo/header artwork, carburetor images, CSS and JavaScript)
- downloads/ (two Edelbrock 1406 PDF reference documents)

IMPORTANT BEFORE PUBLISHING
1. Open assets/site.js and replace REPLACE_WITH_YOUR_EMAIL with the email address that should receive contact messages.
2. The contact form currently opens the visitor's default email app. It does not store or send form data to a server.
3. The downloads page currently provides direct PDF downloads. No visitor email addresses are collected by this version.
4. To enable Brevo signup and automatic email delivery:
   - In Brevo, create a contact list for ChevyParts101 subscribers.
   - Create a signup form and configure the required consent/privacy text.
   - Create an automation triggered when a contact is added to that list.
   - Send an email containing links to the PDF files hosted on your published website.
   - Copy Brevo's official embedded form HTML and replace the signup instructions area in free-downloads.html with that embed code.
   - Test with an email address you control before promoting the site.
   - Do not put a Brevo API key or other secret in browser-side HTML/JavaScript.
5. Add a privacy policy and accurate business/contact details before collecting visitor information or running ads.
6. Confirm you have the rights to distribute every image and PDF before publishing them publicly.

PUBLISH WITH GITHUB + CLOUDFLARE PAGES (STATIC SITE)
1. Extract this ZIP on your computer.
2. Open your GitHub repository named ChevyParts101.
3. Upload the CONTENTS of this folder to the repository root (not the outer folder itself).
   The repository root should contain index.html, the other .html pages, assets/, downloads/, and this README.
4. Commit the upload to your main branch.
5. In Cloudflare, open Workers & Pages and create a Pages project connected to Git.
6. Select the ChevyParts101 GitHub repository.
7. For a plain static HTML site, use no framework/build command; set the output directory to the repository root (often shown as / or . in the setup UI).
8. Deploy, then open the pages.dev address Cloudflare provides and test every page and both PDF downloads.
9. Add the custom domain later after registering it. A .com domain normally has a registration cost; this package and hosting workflow do not purchase a domain.

CONTENT / SAFETY NOTES
- The site is an independent informational project and is not affiliated with Edelbrock.
- Carburetor/fuel-system work can be hazardous. Follow manufacturer instructions and use a qualified professional when unsure.
- Do not advertise parts, repair services, pricing, or appointments until those offerings are confirmed and ready.
