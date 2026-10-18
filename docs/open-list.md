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

2. **Privacy policy** (from the CRM's open list, item 5). One policy for
   the CRM and the site (Sammy, 18/10): a "Privacy policy" link in the
   footer to `crm.round1boxfit.co.uk/privacy`, which now has an "Our
   website" section (CRM pull request #261). Waiting on Sammy: the footer
   link (steps, job 1), and merging #261 so the section goes live.
3. **WhatsApp number on the site** (from the CRM's open list: "new number
   on website/Instagram/Google"). The site shows only the landline
   (checked 18/10). Add `WhatsApp: 07536 138295` under the landline in the
   footer, linked to a WhatsApp chat (`wa.me/447536138295`), and on
   Contact us "Or WhatsApp us on 07536 138295 · Save our number"
   (`crm.round1boxfit.co.uk/contact`). Previewed 18/10. Instagram
   and Google stay on the CRM's list. Waiting on Sammy (steps, job 2).
4. **Button to the 28 Day Program form** (`crm.round1boxfit.co.uk/f/free-trial`)
   on Home and Memberships. Not in the page source on 18/10. Where it sits
   on the improved site comes with the plan. A plain link is recorded as
   a Website lead in the CRM. Wording suggested by Claude (18/10): "Start
   your 28 days", with "Answer a few quick questions, then book your intro
   meeting." under it; previewed on the live pages. Waiting on Sammy: OK
   the wording, then the button (steps, job 3).
5. **Audit the site** (`docs/plan.md`, step 2). Claude, once 2–4 are done:
   the connector for what it can read (page titles and descriptions,
   visitor numbers, an accessibility scan, forms, shop), the live pages
   for the rest.

## Noticed

- **The site's contact form** (Contact us, and the bottom of
  Memberships; first name, last name, email, message) is a Wix form, so
  those messages stay in Wix and don't reach the CRM as enquiries. For
  the audit: where its notifications go, and whether it should send
  people to the CRM instead. The footer's Enquire button goes to Contact
  us.
- **No cookie banner** showed on the live site (18/10), and no Google or
  Meta tracking is on it. For the audit: check Wix's cookie banner
  setting (Claude isn't a lawyer).
- **The shop is empty** (18/10): Wix Stores is installed with no
  products, and its page (`/category/all-products`) is in the sitemap.
  For the audit: hide it, or decide what to sell.

## Done

1. **Connect Wix.** Done 18/10: the connector reaches the Round One site
   (Premium, custom domain, Wix Editor, Velo on).
