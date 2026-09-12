# Contributing

Thanks for helping keep this list useful. Suggestions and pull requests are welcome.

## What belongs here

A tool, service, dataset, bot, or resource that a prediction market trader, quant, or
developer would actually use. It must be publicly reachable and working today.

## What does not belong here

- Dead links, parked domains, and abandoned projects.
- Prediction market venues themselves. This list covers tooling built around them.
- Paid placements. Position on this list is not for sale.
- Referral or affiliate links in the entry URL.
- Projects that exist only as an announcement, a waitlist, or a landing page.

## Entry format

One line, in the right category, kept alphabetically loose but grouped sensibly:

```
- [Name](https://example.com) - Short factual description of what it does.
```

Rules the linter enforces:

- Separate the link and the description with a hyphen surrounded by spaces, not a dash.
- Start the description with a capital letter and end it with a single period.
- Keep it to one sentence, roughly 12 to 28 words.
- Do not repeat the tool's name inside the description.

Rules the linter cannot enforce, but reviewers will:

- Write plainly. No marketing language, no superlatives, no "revolutionary".
- Say what it does and which venues it covers, not how great it is.
- Drop accuracy percentages, user counts, and volume figures that nobody can verify.
- Note open-source status and the license when it applies.

## Submitting

1. Open a pull request against `main`, or file an issue using the "Add a tool" template.
2. One tool per pull request.
3. Run the linter locally first:

```bash
npx awesome-lint
```

4. If you are the tool's author, say so in the pull request. That is fine, it just helps
   reviewers weigh the description.

## Removing an entry

Open an issue if a listed tool has gone offline, changed materially, or turned out to be
a scam. Removals are as valuable as additions.
