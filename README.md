# Court Navigator (prototype)

A court help site for self-represented tenants in Indiana eviction cases. Built for the AI for Impact course (Team 11).

**Live prototype:** https://court-nav.netlify.app/

## The idea

Tenants can lose eviction cases by default before a judge hears their side, often because they do not realize that showing up is what the court requires. Court Navigator is designed so that one QR code, printed on court papers and posted at the courthouse, opens a public information page. When a tenant tells the assistant about their case, the help becomes personal.

## What the prototype includes

- **Learn:** a public page of plain-English court basics (the 10-day notice, court papers, the first hearing, the diversion program, missing a hearing, free help, a glossary), with search.
- **My case:** a short step-by-step intake (what you received, hearing date, what might get in the way, documents you have) that produces a personal plan with a hearing countdown, simulated reminders, tips, and a document checklist.
- **Ask the assistant:** answers drawn only from a small set of sample court sources, with source tags. It declines to give legal advice, points to emergency resources if safety or distress comes up, and says so when something is outside its sources.
- **Court staff view:** an opt-in queue of upcoming hearings with document readiness, flags, and suggested next steps.
- **Accessibility:** text size controls, high contrast, dark mode, read-aloud, large tap targets, keyboard navigation, and a skip link.

## Important notes

- This is a **prototype with sample data**. Nothing is saved or sent anywhere. Sign-in, texts, and reminders are simulated.
- The assistant is **rule-based**, not a live AI model. It demonstrates the guardrails and the source-grounded answer design.
- The content is **information, not legal advice**, and a court would need to review and approve all wording before real use.
- Court contact details are placeholders.

## Sample sources used in the prototype

1. Allen Superior Court, New Eviction Protocol memo (October 10, 2022)
2. Public Allen County eviction dockets (sample cases)
3. Class scenario facts: Indiana 10-day notice, possession decided first, Allen County settlement conference
4. Indiana Small Claims Rule 10(B): default judgment when a defendant does not appear

## Run it locally

It is a single self-contained file. Open `index.html` in a browser. No build step or install is needed.

## Deploy

Drag the folder containing `index.html` onto Netlify Drop, or connect this repository to Netlify.

## Project structure

```
index.html   the whole app (HTML, CSS, and JavaScript)
README.md    this file
```

## Team

Team 11, AI for Impact, Northeastern University.
