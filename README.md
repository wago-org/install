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

```cmd
curl -fsSL https://install.wago.sh/cmd | cmd
```

The site root remains a shell/Command Prompt polyglot loader. The dedicated
`/unix`, `/ps`, and `/cmd` entry points provide cleaner native shell output.
The explicit `/install.sh`, `/install.cmd`, and `/install.ps1` URLs remain
available for scripts that need them, and `/win` remains the cross-shell
Windows fallback.

Do not edit the installer scripts here; the next Wago `main` sync will replace
them.
