<div align="center">

<img src="https://raw.githubusercontent.com/kontext-security/kontext-cli/main/assets/banner-cli.svg" alt="Kontext" width="100%" style="margin-bottom: 20px;" />

### Store Credentials. Inject At Runtime. Agents Never Store The Keys.

[Website](https://kontext.security) &middot; [Documentation](https://kontext.security/docs) &middot; [Discord](https://discord.gg/gw9UpFUhyY)

[![GitHub Stars](https://img.shields.io/github/stars/kontext-dev/kontext-cli?style=social)](https://github.com/kontext-dev/kontext-cli/stargazers)
[![Twitter](https://img.shields.io/twitter/follow/kontext_dev?style=social)](https://twitter.com/kontext_dev)

</div>

## What is Kontext?

Kontext is the identity and credential layer for AI coding agents. It replaces long-lived API keys in `.env` files with short-lived, scoped credentials that are injected at session start and expire when the session ends. Every tool call is logged, every secret is accounted for.

```bash
brew install kontext-dev/tap/kontext
kontext start --agent claude
```

That's it. The CLI authenticates you, resolves credentials, launches your agent, and streams governance telemetry to the Kontext dashboard.

## Open Source

| Repository | Description |
|---|---|
| [kontext-cli](https://github.com/kontext-dev/kontext-cli) | CLI for AI coding agents — credential management, governance, and audit trails |
| [proto](https://github.com/kontext-dev/proto) | Protocol buffer definitions — shared contract between CLI and API |
| [skills](https://github.com/kontext-dev/skills) | Claude Code skills for the Kontext ecosystem |

## Get Involved

- Read the [docs](https://kontext.security/docs)
- Join the [Discord](https://discord.gg/gw9UpFUhyY)
- Follow us on [Twitter/X](https://twitter.com/kontext_dev)
- Open an issue on any repo above
