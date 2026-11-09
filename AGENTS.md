# AGENTS.md — Rules for working on this site

Personal site for Takuma Murakami (GitHub Pages: tmurakami27.github.io).
Source material: `private/cv.pdf` (kept in the git-ignored `private/` folder; the site uses `images/photo-web.jpg`). LinkedIn: https://www.linkedin.com/in/takuma-murakami — GitHub: https://github.com/TMurakami27

## What never to publish
- Phone number, home address, personal email, or any other private contact details (the CV's phone number stays off the site).
- Email addresses, unless Takuma has explicitly approved a specific address for the site.
- Grades, salary, visa status, date of birth.
- Anything in `private/`: add it to `.gitignore` first, before doing anything else with it.
- Confidential or non-public information about current or former employers or clients: no client names, deal terms, or internal figures beyond what already appears on the CV.
- Anything about other people (colleagues, classmates, clients) that identifies them without their consent.
- Credentials, tokens, API keys, or `.env`-style files.
- `private/cv.pdf` and the original `private/photo.JPG` are source files. Do not link to or publish the PDF unless Takuma says so.
- Do not invent facts. Every claim on the site must trace back to the CV or to something Takuma has told us.

## When to ask me first
- Before any `git push`, any change on GitHub, publishing, or deploy. Local commits and local preview are fine only when asked for.
- Before deleting or overwriting a file. Look at the target first.
- Before adding or changing any factual content (titles, dates, numbers, achievements), or rewording that changes meaning.
- Before adding personal contact details, analytics, tracking, forms, or any third-party scripts or services.
- Before adding, removing, or replacing photos or other media.
- Before deleting files, or renaming/restructuring the site.
- Before adding new pages or sections beyond the CV's sections.

## Style
- Vibe: professional and casual. Warm and approachable, never stiff, never flashy.
- Colors: Columbia blue (`#B9D9EB` light, `#6CACE4` mid) with navy (`#0B2545`) for text and contrast. White/off-white backgrounds. Keep text contrast accessible.
- Navigation: streamlined — a single sticky top bar with a few anchor links. No dropdowns, no hamburger on desktop.
- Content order follows the CV: header/contact, Education, Experience, Additional Information.
- Plain HTML + CSS, clean and minimal. No frameworks or build step. Must work on phone widths.
- Keep the CV's wording and numbers exactly; only reformat.
- Portfolio: a gallery page that links to each project (when projects are added, with approval per the rules above).

## When you finish
- Tell Takuma what you changed and what you skipped. List every file created or modified.
