# MuAPI skills

Vendored from [SamurAIGPT/muapi-skills](https://github.com/SamurAIGPT/muapi-skills)
at commit `1dd7527a9d5e0477e18af8baf8c6915053585680` (MIT, see `LICENSE`).
Referenced by [anil-matcha/open-generative-ai](https://github.com/anil-matcha/open-generative-ai).

The directory layout is kept as upstream because the scripts call each other via
relative paths (e.g. `library/*/scripts/*.sh` -> `core/media/*.sh`).
Demo images from `media_outputs/` were left out; generated files land there and are git-ignored.

## Requirements

- A MuAPI key: `export MUAPI_API_KEY=...` (https://muapi.ai/dashboard). Never commit it.
- The `muapi` CLI: `pip install muapi-cli` or `npm i -g muapi-cli`.
- Some scripts also use `curl`, `jq` and `python3`.

Generations consume paid MuAPI credits.
