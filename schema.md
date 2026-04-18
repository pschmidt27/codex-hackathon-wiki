# Vault Maintenance Contract

The vault contains raw captures in `raw/` and curated notes in `notes/`.

## Rules

- Keep notes concise, accurate, and reader-friendly.
- Preserve useful wiki-style links between related notes.
- Keep `index.md`, `log.md`, and `overview.md` useful after every ingest.
- Prefer updating existing notes when new input fits an existing topic.
- Use `log.md` for chronological ingest history.
- Treat `raw/*.txt` files as the canonical fact sources for submissions.
- When adding or updating wiki content, prefer linking concrete claims back to supporting raw files, using explicit vault links like `[[raw/...txt]]` when practical.
- Keep curated notes free of pipeline language like "submission URL", "share sheet", "shared text", or "ingest" unless `log.md` specifically needs that operational detail.
- If external URLs were fetched for context, incorporate the resulting facts naturally instead of mentioning the retrieval process in curated prose.
- Avoid heavy-handed provenance labels like `Source:` in curated notes when a lighter citation pattern or no visible citation would read better.
- Prefer provenance only when it genuinely helps readers, using light patterns like a short `References` section or inline raw links.
- Reference raw sources when they support a claim.
- Every submission must result in curated note work in `notes/`.
- For image ingests, update an existing note only when the match is clear; otherwise create a new note.
