# HiLinkup Mintlify documentation

## Project context

- This is the Chinese developer documentation for HiLinkup.
- The production origin is `https://hilinkup.com`.
- The OpenAI-compatible API base URL is `https://hilinkup.com/v1`.
- Navigation and site settings are defined in `docs.json`.
- Documentation pages use MDX with YAML frontmatter.

## Writing standards

- Write concise Simplified Chinese in second person.
- Use active voice and sentence-case headings.
- Explain what a feature does before showing how to use it.
- Put prerequisites before procedural steps.
- Use current model IDs only when verified; otherwise instruct readers to call `GET /v1/models`.
- Do not invent prices, limits, supported models, or account permissions.
- Mark unverified operational values with a TODO comment.

## API examples

- Use `https://hilinkup.com/v1` as the base URL.
- Use `HILINKUP_API_KEY` for environment variable examples.
- Never include a real API Key.
- Include language tags on every code block.
- Treat response IDs, timestamps, usage, URLs, and model output as illustrative.
- Note when capability depends on the selected model or upstream channel.

## Mintlify conventions

- Add every new user-facing page to `docs.json`.
- Use root-relative internal links without file extensions.
- Prefer built-in Mintlify components.
- Use `<Steps>` for sequential procedures.
- Use `<CodeGroup>` for equivalent language examples.
- Use `<ParamField>` and `<ResponseField>` on API pages.
- Use `<Warning>` for security, billing, or destructive-operation risks.

## Verification

- Run `mint broken-links`.
- Run `mint validate`.
- Check that every page has `title`, `description`, and `keywords`.
- Check that examples never contain secrets.
