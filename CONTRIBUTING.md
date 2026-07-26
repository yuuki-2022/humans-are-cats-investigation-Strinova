# Contributing

Thanks for helping improve Humans are Cats: Investigation.

## Development

```bash
npm install
npm run dev
```

Before opening a pull request, run:

```bash
npm run build
```

There is no dedicated test suite yet. For gameplay changes, also verify the game in a browser and mention what you tested in the PR.

## Guidelines

- Keep the game playable without a DeepSeek API key; NPC chat can fail gracefully.
- Do not add compatibility shims for old versions of the game. Remove obsolete code when replacing behavior.
- Keep runtime VOCALOID data offline under `public/data/`.
- Never commit real `.env`, API keys, local database files, logs, or generated `dist/` output.

## Contribution license

By submitting a contribution, you confirm that you have the right to provide it and agree to license your contribution under the repository's [PolyForm Noncommercial License 1.0.0](LICENSE). Do not submit third-party code, data, artwork, audio, characters, trademarks, or other material unless its license permits the intended use and all required notices are included.
