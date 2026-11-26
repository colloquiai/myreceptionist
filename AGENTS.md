# Documentation project instructions

## About this project

- The help site for My Receptionist, built on [Mintlify](https://mintlify.com).
- Pages are MDX files with YAML frontmatter. The menu and site settings are in `docs.json`.
- Preview with `mint dev`. Check with `mint validate` and `mint broken-links` before every commit.
- Commits to `main` publish the site.

## Who reads it

Ordinary, non-technical people: business owners and their staff, and partners who run My Receptionist for
their customers. Not developers. Every page must make sense to someone who has never seen the product.

## Terminology

- "receptionist", never "agent" or "bot".
- "workspace" for the account a business's receptionists live in.
- "caller" for a person who rings.
- "People and teams" are who callers can be put through to. "People" (a tab of Settings) are who can sign in. Keep them apart.

## Style

- Australian English. Plain, short sentences. Second person. Active voice.
- Start with what the thing is for, in terms of a phone call. Then numbered steps.
- No technical words. If the screen uses one, explain it in a few plain words.
- Sentence case for headings.
- Bold for anything on screen: click **Go live**.
- Quote on-screen words exactly as the application shows them.
- Screenshots wherever the reader needs to see the screen.
- No em dashes, no exclamation marks, no marketing language.

## Content boundaries

- No prices or plan names: the Billing page shows them.
- Do not name the companies or technology behind the product.
- Do not document administrator-only pages.
- Do not describe anything that is not built.
