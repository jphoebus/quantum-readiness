# Portfolio project conventions

These pages are neutral, sourced policy comparisons published at jphoebus.github.io. Every change follows these rules.

## Voice and sourcing

- Strictly neutral. Describe what each state does, not which approach is better. No "win," "pushback" or similar framing.
- Use only the facts given in the request. Don't add facts.
- Mark any detail that rests on news coverage rather than a statute, rule, order, court record or official release with "(as reported)." Put the marker on the sentence that holds the reported facts, not on a sentence that needs no source (for example, "The allegations have not been decided.").
- An official primary source, such as an agency release, a statute or an order, can replace "(as reported)." If you can't open a source to confirm it, say so and stop. Don't add a link you haven't confirmed unless the request says it was checked elsewhere.
- Attribute contested claims to whoever makes them (for example, "which the sponsor says...").
- Don't list the same source twice. Check the existing sources before adding one.

## Dates

- Page-level dates move together whenever a page changes: "Current as of" in the header and the meta description, the footer's "Last updated," and the README.
- Per-state "Last updated" cells change only when that state's entry changes. Never move every state's date to today.
- Keep content dates (event dates inside cells) as written.

## Data files

- Keep each CSV's existing quoting convention: all cells quoted where the file already does that, and quote-only-when-needed elsewhere. Keep its line endings (some files use CRLF).
- The CSV must match the page. Where a CSV has one row per action, add a new row for a new action rather than appending to another row.
- Update source and step counts in the download list and README when rows change.
- data-center-siting: index.html was built from the three CSVs, but the build script isn't in the repo. Edit the CSVs and the matching page markup together, and keep them identical.

## Page structure

- Match the existing design, link style and separator on each page ( · or &middot;).
- "What to watch" lists run in date order; undated items ("Ongoing," "Pending") go at the end.
- Footer "Related:" lines list sibling projects. medicaid-transportation uses a shorter list; don't change it unless asked.

## Workflow

- One PR per repo, squash-merged unless the request says to hold it for review. Don't delete branches.
- Describe each change in the PR body, including anything left unchanged on purpose and why.
- After a merge, check the GitHub Pages deployment. If it's stuck or failed, report it before re-running.
