# Bitsense Marketplace

The self-hosted Claude Code marketplace for [Bitsense](https://bitsense.dev) plugins.

## Install

Add this marketplace to Claude Code:

```
/plugin marketplace add bitsense/bitsense-marketplace
```

Then install the plugin:

```
/plugin install bitsense@bitsense
```

You'll need a Bitsense API key — get one at [bitsense.dev](https://bitsense.dev) and set it in your shell:

```sh
export BITSENSE_API_KEY=<your-key>
```

## What's here

- [`bitsense`](https://github.com/bitsense/bitsense-plugin) — personalizes Claude Code to your team's codebase. Auto-injects team conventions; runs orchestrated reviews and team-aware code generation. V1 supports Java + Spring Boot deeply.

## License

MIT.
