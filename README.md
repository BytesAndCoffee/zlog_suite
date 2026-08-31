# zlog_suite

Meta-repository for the zlog stack.

## Architecture

![ZLog ecosystem architecture](docs/architecture/01-zlog-system-overview.png)

The complete architecture set documents the [live notification](docs/architecture/02-live-notification-flow.png), [context lookup](docs/architecture/03-context-flow.png), [reply](docs/architecture/04-reply-flow.png), and [database recovery](docs/architecture/05-recovery-flow.png) paths. See [the architecture guide](docs/architecture/README.md) for the notation and editable SVG sources.

## Included projects

- `components/zlog-sql`
- `components/zlog_parsing`
- `components/zlog_store`
- `components/zlog_telegram` (renamed/refactored from Telepush)

## Clone with submodules

```bash
git clone --recurse-submodules git@github.com:BytesAndCoffee/zlog_suite.git
```

## Pull latest for all components

```bash
git submodule update --remote --recursive
```
