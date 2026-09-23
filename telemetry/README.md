# API telemetry

Each `api-calls.jsonl` file is the original per-game OpenRouter telemetry log, arranged as
`telemetry/<condition>/exp_<nnn>/api-calls.jsonl`. The `exp_<nnn>` directory matches the
corresponding clean-dataset game directory and its condition-level `id_mapping.json`.

Coverage is complete: 411 of 411 games. The 25 Claude Opus 4.6 human-crewmate telemetry logs
were recovered from `AmongUs-ShivensShare.zip`; the remaining logs came from the original game
directories.
