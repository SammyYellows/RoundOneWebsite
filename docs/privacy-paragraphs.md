# Privacy page: wording for the site

Claude isn't a lawyer: check the wording, or have someone look over it.

## Agreed: one policy, linked from the footer (Sammy, 18/10/2026)

The CRM already has a full privacy policy at
`crm.round1boxfit.co.uk/privacy` (last updated 14 October 2026;
`src/app/privacy/page.tsx` in the CRM repo). It covers enquiries, intro
meetings, WhatsApp, Facebook, Instagram and email messages, memberships,
door entries, safety, the AI, who handles data, how long it's kept, your
rights and how to have data deleted. The Meta app already uses it.

So rather than a second copy on Wix that has to be kept in step, the
site's footer links to that page (`docs/editor-steps.md`, job 1), and the
CRM's page gets one short section about the website (below). One policy,
one place to keep up to date. The section went into the CRM on 18/10
(pull request #261; live once merged).

## What the site collects (checked in Wix, 18/10)

- **Shop:** Wix Stores is installed but has **no products**, so no orders
  are taken. If the shop starts selling, the policy needs a line about
  orders and payments.
- **Forms:** a contact form on Contact us and at the bottom of
  Memberships (first name, last name, email, message). It isn't in Wix
  Forms, so it's the older Wix Forms & Payments app.
- **Cookies and tracking:** no Google or Meta tracking in the page source,
  and no cookie banner showed (18/10). Wix's own cookies and visitor
  counts apply.

## What went into the CRM's policy (18/10)

"This policy covers how we handle your information when you **visit our
website**, enquire about the gym, …", and a new section:

> **Our website**
>
> Our website, roundonefitness.co.uk, is built and hosted by Wix. When you
> visit it, Wix uses cookies to make the site work and to count visits. If
> you send us a message through the contact form on the website, we keep
> your name, email address and message, and use them to reply to you.

And under **Who we share it with**: "Wix: hosts our website."
