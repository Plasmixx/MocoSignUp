# MoCo Sign up

Free community events for Montgomery County, Maryland.

MoCo Sign up is a simple, independent prototype that helps residents find free local events — and helps organizers list them — without needing an account to browse, post, or sign up.

**Live site:** https://www.mocosignup.com/

> This is an independent community prototype. It is not an official Montgomery County or Montgomery County Public Libraries site.

## For residents

- Browse free events across Montgomery County by neighborhood, category, and date
- See what's upcoming, what's popular, and what's happening near you
- Reserve a spot in a few taps — no account required
- Cancel a reservation if your plans change

## For organizers

- Post a free event in a few minutes — no account required to post
- Events are checked automatically before they go live
- Events that need a closer look are sent to an admin review queue instead of going straight to the public feed
- See who signed up for your events, and message attendees through the site

## How it works

- **No account needed to post or sign up.** Posting and reserving are open to everyone, to keep it simple — especially for seniors and first-time users.
- **Automatic checks.** New events pass a built-in checker and automated moderation before they are published. Low-quality or flagged posts are held for admin review.
- **Admin review.** Admins can approve events from the review queue so they appear in the public feed, or reject them.
- **Spam protections.** The site limits how often one poster can submit, and blocks exact duplicate events sent within a day.
- **Languages.** The interface is available in English, Spanish, Chinese, French, and Korean. Event creators can also tag the language of their event description.

## Accessibility

MoCo Sign up aims to meet WCAG 2.2 AA, based on a vendor self-assessment.

- An accessibility statement is available at https://www.mocosignup.com/accessibility
- A VPAT (Voluntary Product Accessibility Template) self-assessment for WCAG 2.2 Level A and AA is available from that page

This is a self-assessment, not a formal third-party audit or certification.

## Tech notes

- Single-page site, deployed with Vercel
- Data and sign-ups are stored in Supabase
- Event text is checked with automated moderation before publishing

This repository contains the site's front-end code. No passwords, private keys, or admin credentials are stored in this repository — sign-in is handled through Supabase Auth.

## Contact

Questions, or found a barrier? Email help@mocosignup.com.
