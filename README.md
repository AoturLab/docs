# HiLinkup developer documentation

Chinese developer documentation for the HiLinkup OpenAI-compatible API.

## Local preview

Install the Mintlify CLI:

```bash
npm install -g mint
```

Start the local documentation server:

```bash
mint dev
```

The preview is available at `http://localhost:3000`.

## Quality checks

```bash
mint broken-links
mint a11y
mint validate
```

## Publishing

Mintlify deploys changes after they are merged into the repository's default branch.
