# Wago installer bootstraps

This repository publishes the small bootstrap scripts served from
[`install.wago.sh`](https://install.wago.sh). The canonical copies live in
[`wago-org/wago`](https://github.com/wago-org/wago) and are synchronized by its
`Publish installers` workflow.

```sh
curl -fsSL https://install.wago.sh | sh
```

```powershell
curl.exe -fsSL https://install.wago.sh/win | powershell -c -
```

The site root is a small shell/Command Prompt polyglot loader. The explicit
`/win` serves the PowerShell loader used by the cross-shell Windows command.
The explicit `/install.sh`, `/install.cmd`, and `/install.ps1` URLs remain
available for scripts that need them.

Do not edit the installer scripts here; the next Wago `main` sync will replace
them.
