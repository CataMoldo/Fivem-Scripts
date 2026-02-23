# Fivem-Scripts

This repository is dedicated exclusively to FiveM scripts:
- standalone (no framework)
- Qbox (compatible with the Qbox framework)

## Recommended Structure

```text
standalone/
qbox/
```

You can organize each resource in the appropriate folder, for example:

```text
standalone/my_resource/
qbox/qbx_my_resource/
```

## Repository Rules

- Do not add scripts for other frameworks here (ESX, classic QBCore, etc.).
- Keep each script as a separate resource (with its own `fxmanifest.lua`).
- Use clear, function-oriented naming.

## Commit Convention (Simple)

- `feat:` new functionality
- `fix:` bug fix
- `chore:` maintenance/configuration

Example:

```text
feat(qbox): add banking helper export
fix(standalone): prevent nil callback on player drop
```
