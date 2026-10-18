# Project context

Round One's website, **roundonefitness.co.uk**, built on Wix. Round One is
a boxing and strength gym in Bristol. Sammy is improving the site, a lot,
with Claude Code. This repo holds the plans and the to-do list; the site
itself lives in Wix.

The CRM is a separate repo (`SammyYellows/Round-One-CRM-`). Its CLAUDE.md
is the fullest description of how Round One works: read it when a website
job touches leads, bookings, messages or members.

## How changes are made

- **The site lives in Wix, not in this repo.** Nothing in this repo
  deploys anything.
- **What the Wix connector can and can't do** (checked 18/10). It's a
  Wix Editor site (site id `0220a2a1-ecdc-4b7a-8952-aac619d33eaa`). The
  connector reaches the site's data: page titles and descriptions for
  Google, redirects, the shop, forms, site settings, visitor numbers and
  accessibility scans. It **can't** change pages, text, buttons, the menu
  or the footer. Those are done in the Wix Editor (Sammy, 18/10: by
  Claude through Claude in Chrome, in a session on Sammy's computer),
  following steps written in `docs/` (see `docs/editor-steps.md`). Check
  in the Editor's Preview; Sammy presses Publish. A cloud session can't
  reach Chrome.
- **This repo holds the thinking:** `docs/plan.md` (where the site is
  going), `docs/open-list.md` (what's in progress and what each item waits
  on), page notes and copy drafts. Claude keeps both current.
- **Nothing goes live without Sammy's go-ahead.** Before changing a live
  page, say what will change and wait for a yes. If the connector can work
  on a draft or an unpublished copy, use that and publish once agreed.
- **Custom code** (Wix's Velo, or anything else) only once agreed with
  Sammy; if it happens, the code goes in this repo.
- Write down decisions with a name and date, as in the CRM: "(Sammy,
  18/10)".

## What's where

- **Wix:** the pages, menu, shop, site settings and SEO.
- **TeamUp:** memberships, billing, classes, bookings and PT. The site
  links to TeamUp's membership pages
  (`teamup.com/p/10418134-round-one/memberships/…`). Don't rebuild any of
  that on the site; link to it.
- **The CRM** (`https://crm.round1boxfit.co.uk`) owns these public pages,
  which the site can link to. Changes to them are made in the CRM repo.
  - `/f/free-trial`: the enquiry form for the 28 Day Program (the Meta ads
    point here too). A plain link from the site is recorded as source
    "Website" and the lead lands on the CRM's Pipeline. Don't add
    `utm_source=facebook` or similar to site links: that marks them as ad
    leads.
  - `/contact` and `/contact.vcf`: the "save our number" card.
  - `/privacy`: the CRM's own privacy policy, for what the CRM stores.
  - `/book/<contact id>` is someone's personal booking page. Never link to
    it from the site.

## Gym facts

From the CRM (`src/lib/gym.ts`, taken from this site on 27/09/2026, and
Sammy's decisions):

- Round One, Unit 2 Kings Business Park, Kings Park Ave, Bristol BS2 0TZ.
- WhatsApp **07536 138295** (the gym's new number since 13/10/2026; the old
  07833 399014 is gone). Landline 0117 2510 120. Email
  info@round1boxfit.co.uk.
- **The 28 Day Program** is the trial (Sammy, 07/10): £79 paid upfront;
  finish it and move onto a recurring membership and the £79 is refunded
  against that membership, so the first 28 days end up free.

**Don't invent gym facts** (prices, class times, coaches, offers). Use
what's here, on the site already, or in TeamUp, and ask Sammy for the
rest. Placeholder copy must be clearly marked as such.

## Brand

The CRM's colours and fonts were taken from this site, so the two match.
If the site's look changes, note it in the open list so the CRM can
follow.

- Colours: black `#0A0A0A`, charcoal ground `#2D2E2D`, panel `#383938`,
  brand red `#EC2024` (accents, big type), button red `#D01B20` (passes
  contrast under white text), cream `#FFF5F0`.
- Fonts: Anton for headings and big numbers, always uppercase; Poppins for
  everything else.
- Square corners. Buttons and labels uppercase and letter-spaced.

## Copy voice

British, plain, friendly, like a good front desk. Sentence case. Buttons
say what they do ("Book", "Start your 28 days"), not "Submit". No
exclamation marks.

## Rules

- **A privacy policy page** stays on the site, linked from the footer, and
  true to what the site and the CRM collect. It carries the CRM's policy
  (`crm.round1boxfit.co.uk/privacy`) word for word plus a section about
  the website; when the CRM's policy changes, update the site's too.
- **Phones too.** Check every change at phone width as well as desktop.
- **Accessible:** alt text on images, readable contrast, real headings,
  respect reduced motion.
- **Keep the CRM in step.** If a site change affects the CRM (a new form, a
  new link to a CRM page, a new number), add it to the CRM repo's
  `docs/open-list.md` too.
