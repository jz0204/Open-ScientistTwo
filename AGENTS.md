# Running research in this fork

Read HANDOFF.MD for verified runs and known pitfalls. For new Codex research
campaigns use `examples/live-options.codex-paper.json` unless the user selects
other models. Use the checkout's own environment (`uv run scientisttwo`).
Give each direction its own task, frozen manifest and output directory. Use
the user's budget when preparing the manifest; creating or checking it makes
zero model calls.
