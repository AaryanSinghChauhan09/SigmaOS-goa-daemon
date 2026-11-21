# SigmaOS-goa-daemon

SigmaOS integration component for **GNOME Online Accounts**.

## Commands

```bash
sigmaos-goa-daemon install   # install package + deploy defaults
sigmaos-goa-daemon deploy    # copy config templates to $HOME
sigmaos-goa-daemon status    # binary/package/config report
sigmaos-goa-daemon reset     # remove deployed config
sigmaos-goa-daemon open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
