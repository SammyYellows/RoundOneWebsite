# Open list

Everything in progress and what each item is waiting on. Sammy picks from
this; Claude keeps it current. Started 18/10/2026.

## Open

Order (Sammy, 18/10): the jobs that came from the CRM (2–4) come first,
then the audit (5).

**The connector can't edit pages** (checked 18/10): this is a Wix Editor
site, and the connector reaches its data (shop, forms, page titles for
Google, redirects, site settings, visitor numbers, accessibility scans),
not its pages, text, buttons, menu or footer. So 2–4 are done by Sammy in
the Wix Editor, a few minutes each, with the steps in
`docs/editor-steps.md`.

2. **Privacy policy** (from the CRM's open list, item 5). The site has
   none (checked 18/10). Recommended (`docs/privacy-paragraphs.md`): a
   "Privacy policy" link in the footer to the CRM's privacy page, which
   gets a short "This website" section, so there's one policy to keep up
   to date. Then, in the CRM: set `PRIVACY_URL` so the consent line shows
   on the form. Waiting on Sammy: yes to that approach (or a copy on Wix
   instead), and the wording checked; then the footer link (steps, job 1).
3. **WhatsApp number on the site** (from the CRM's open list: "new number
   on website/Instagram/Google"). The site shows only the landline
   (checked 18/10). Add `WhatsApp 07536 138295` beside the landline,
   linked to a WhatsApp chat (`wa.me/447536138295`), and on Contact us a
   "Save our number" link to `crm.round1boxfit.co.uk/contact`. Instagram
   and Google stay on the CRM's list. Waiting on Sammy (steps, job 2).
4. **Button to the 28 Day Program form** (`crm.round1boxfit.co.uk/f/free-trial`)
   on Home and Memberships. Not in the page source on 18/10. Where it sits
   on the improved site comes with the plan. A plain link is recorded as
   a Website lead in the CRM. Waiting on Sammy: the button's wording
   (suggestion: "Start your 28 days"), then the button (steps, job 3).
5. **Audit the site** (`docs/plan.md`, step 2). Claude, once 2–4 are done:
   the connector for what it can read (page titles and descriptions,
   visitor numbers, an accessibility scan, forms, shop), the live pages
   for the rest.

## Noticed

- **The shop is empty** (18/10): Wix Stores is installed with no
  products, and its page (`/category/all-products`) is in the sitemap.
  For the audit: hide it, or decide what to sell.

## Done

1. **Connect Wix.** Done 18/10: the connector reaches the Round One site
   (Premium, custom domain, Wix Editor, Velo on).
