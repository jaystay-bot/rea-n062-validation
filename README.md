# rea-n062-validation

One-time, manually triggered check of whether `rea-agents@6.7.0` (https://github.com/morluto/rea, MIT) can statically inspect a small public sample app.

- Target: `electron/electron-quick-start-typescript` at commit `eb58abdbd1dd8cb0d2df9608fccf12ad989a189b` (CC0-1.0, archived).
- The workflow pins the package integrity and lockfile hashes, installs with lifecycle scripts and optional dependencies disabled, never runs `rea setup`, and never installs or launches the sample.
- No secrets, tokens or private data are used. Workflow permissions are empty, and results are written only to the job log.

This repository contains test inputs only and will not be maintained.
