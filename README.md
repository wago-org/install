# Wago installer bootstraps

This repository publishes the small bootstrap scripts served from
[`install.wago.sh`](https://install.wago.sh). The canonical copies live in
[`wago-org/wago`](https://github.com/wago-org/wago) and are synchronized by its
`Publish installers` workflow.

```sh
curl -fsSL https://install.wago.sh | sh
```

```cmd
curl -fsSL https://install.wago.sh | cmd
```

The site root is a small shell/Command Prompt polyglot loader. The explicit
`/install.sh` and `/install.cmd` URLs remain available for scripts that need
them.

Do not edit `install.sh` or `install.cmd` here; the next Wago `main` sync will
replace them.
