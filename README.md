# chkm8-wiki

chkm8's research knowledge base (LLM-wiki style): interlinked markdown pages on tokens, chains,
narratives and topics, plus the daily digests. Conventions are in `SCHEMA.md`; `index.md` is the
entry point and `log.md` the change log.

- `tokens/`, `chains/`, `narratives/`, `topics/`: knowledge pages
- `digests/`: daily market digests (markdown)
- `signals.json`: watchlist signals scored by the digest collector

Rendered HTML/PNG copies, raw collector JSON (`raw/`) and household budget emails (`budget/`) are
gitignored.

New pages and digests are committed and pushed daily at 07:45 PT by the Hermes cron job
"git autopush" (`~/.hermes/scripts/chkm8_git_autopush.sh`), through the same leak checks as manual commits.
