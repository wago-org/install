# Wago installer bootstraps

This repository publishes the small bootstrap scripts served from
[`install.wago.sh`](https://install.wago.sh). The canonical copies live in
[`wago-org/wago`](https://github.com/wago-org/wago) and are synchronized by its
`Publish installers` workflow.

```sh
curl -fsSL https://install.wago.sh/unix | sh
```

```powershell
irm https://install.wago.sh/ps | iex
```

The site root is a shell loader. The dedicated `/unix` and `/ps` entry points
provide native shell output. The explicit `/install.sh` and `/install.ps1`
URLs remain available for scripts that need them, and `/win` remains an alias
for the PowerShell loader.

Do not edit the installer scripts here; the next Wago `main` sync will replace
them.
