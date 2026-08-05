# Wago installer bootstraps

This repository publishes the small bootstrap scripts served from
[`install.wago.sh`](https://install.wago.sh). The canonical copies live in
[`wago-org/wago`](https://github.com/wago-org/wago) and are synchronized by its
`Publish installers` workflow.

```sh
curl -fsSL https://install.wago.sh/install.sh | sh
```

```cmd
curl.exe -fsSL https://install.wago.sh/install.cmd -o install.cmd && install.cmd
```

Do not edit `install.sh` or `install.cmd` here; the next Wago `main` sync will
replace them.
