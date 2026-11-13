# Contributing

Thanks for helping keep this list accurate. Additions, corrections and removals are all welcome as pull requests. If you are not sure whether something fits, open an issue first.

This list is maintained by the Replyze team, and Replyze is one of the listed products. The same rules apply to every entry, Replyze included.

## Criteria

An entry is added when all of these are true:

- **In scope.** It is live chat or customer support software, an AI agent or chatbot for customer support, a chat widget or SDK for a support product, a WordPress plugin for live chat, or a developer resource (API, MCP server) for one of these. General team chat, CRM, marketing automation and IT service management tools are out of scope unless live chat or customer support is a main part of the product.
- **Real and available.** Anyone can sign up, download or install it today, and it has a public website, README or documentation that explains what it does.
- **Actively maintained.**
  - Open-source projects: the repository is not archived and has a release or regular commits in the last 12 months.
  - WordPress plugins: listed on wordpress.org and updated in the last 12 months, or a public repository with a release in the last 12 months.
  - SDKs and developer resources: maintained by the vendor or a project with recent commits, and documented.
  - Hosted products: the product is sold and supported today.
- **Not a duplicate.** One entry per product per section. A product can appear in more than one section when it fits each one (for example a hosted product and its MCP server), each with its own link.

Projects that stop meeting the criteria move to [inactive.md](inactive.md) with the reason and the date it was checked.

## Format

```md
- [Name](https://example.com) - One neutral, factual sentence about what it is or does.
```

- Keep entries in **alphabetical order** within their section. There is no ranking.
- Link to the project's own site, repository or documentation. No affiliate or tracking links, except the Replyze maintainers' own UTM tags on replyze.chat links.
- The description starts with a capital letter, ends with a period, and does not start with the product's name.
- Describe what the product does, using facts from its own site, README or docs. No prices or plan limits, because they change. No "best", "leading", "#1", rankings, customer counts or claims about other products.
- For open-source projects, also update the [comparison table](README.md#comparison) with facts you checked (license, language, self-hosting options, mobile apps, channels, rounded stars) and the date you checked them.
- "Has a free plan" is only written in the Alternatives sections, only when the vendor's pricing page lists one, and without amounts.

## Vendors

Vendors are welcome to add or correct their own entry. Please say in the pull request that you work for the vendor. Entries are judged by the same criteria whoever submits them.

## Pull requests

- One product per pull request, so each change is easy to review.
- Use a clear title, for example `Add Example Chat` or `Update Example Chat description`.
- Check that every link opens and that `npx awesome-lint` passes before you submit.
- CI runs `awesome-lint` on every pull request and checks the links when a Markdown file changes. The links are also checked every week.
