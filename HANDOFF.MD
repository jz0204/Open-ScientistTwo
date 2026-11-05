# Codex research handoff

- At `0fe2572`, the real single-model GPT-6.1 Terra pilot on generated quadratic
  regression completed 30 calls (979,124 observed tokens), six development and
  ablation experiments, two final scores, internal meta-review and container
  audit. Earlier 400,000-token pilots stopped during drafting. The controller
  checks the token threshold between calls.
- The canonical writer renders numeric claims from bound evidence. Writing and
  review feedback must preserve those bindings. Keep a failed campaign intact
  and freeze a new manifest if the implementation, task or budget changes.
- For a new Codex research project use the [paper role profile](docs/model-providers.md#codex-paper-profile).
  This preset now uses GPT-6-Astra for every role. The previous Terra/Astra routing was checked with a local test CLI and a zero-call
  preflight. The real all-Terra pilot is separate evidence. Campaign ledgers,
  task manifests and datasets from another checkout are local artifacts.
