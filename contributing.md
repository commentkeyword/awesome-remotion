# Contributing

Thanks for helping make Awesome Remotion better. This list is curated, not exhaustive: every entry should be something you would personally recommend to someone building with Remotion.

## What belongs here

- Official Remotion documentation, packages, and services.
- Community packages, components, and templates that are actively maintained.
- Complete projects and examples that show a useful technique or product.
- Tutorials, talks, and articles that teach something concrete.
- Community spaces where Remotion users help each other.

Please do not add:

- Abandoned projects, link farms, or SEO blog posts that repeat the official docs.
- Products that only mention Remotion in passing.
- Anything paid or promotional without a clear, honest description.
- Duplicate entries or the same resource under a different name.

## Adding an entry

1. Fork the repository and create a branch.
2. Add your entry to the most relevant section of `readme.md`.
3. If you add a new section, update the `Contents` list to match.
4. Run the linter locally:

   ```sh
   npx awesome-lint
   ```

5. Open a pull request that explains what you added and why it is worth including.

## Formatting

Use one line per entry:

```md
- [Name](https://example.com) - A short description of what it does and why it is useful.
```

The linter enforces these rules:

- Use a `-` list marker followed by a single space.
- Separate the link and the description with ` - ` (spaces around an ASCII hyphen).
- Start the description with a capital letter and end it with a period.
- Do not start the description with the item name.
- Do not use a trailing slash in URLs.
- Do not link the same URL twice.
- Keep descriptions short: one sentence is usually enough.

Write descriptions for a reader who has never heard of the project. Prefer concrete details ("Renders videos on AWS Lambda") over vague praise ("An amazing tool").

## Review process

A maintainer will review your pull request. We may ask you to:

- Move an entry to a different section.
- Shorten or rewrite a description.
- Remove an entry that does not meet the quality bar.
- Split a large pull request into smaller ones.

Decisions are made in the interest of the list as a whole. If you disagree, explain your reasoning in the pull request; we are happy to reconsider.

## Code of Conduct

By participating, you agree to follow the [Code of Conduct](code-of-conduct.md). Please report unacceptable behavior by opening an issue in this repository.
