<div align="center">

<img src="https://raw.githubusercontent.com/kontext-security/.github/main/profile/Kontext_Banner.png" alt="Kontext Security" width="100%" />

### Agent security. Enforced before execution.

Kontext applies identity-aware policy to AI agent actions.  
Sandy contains AI coding agents with native macOS and Linux sandboxing.

[Get started with Kontext](https://github.com/kontext-security/kontext) &middot;
[Documentation](https://kontext.security/docs) &middot;
[Website](https://kontext.security)

[![GitHub Stars](https://img.shields.io/github/stars/kontext-security/kontext?style=social)](https://github.com/kontext-security/kontext/stargazers)
[![Follow on X](https://img.shields.io/twitter/follow/kontextsecurity?style=social)](https://twitter.com/kontextsecurity)

</div>

## Control what AI agents can do

AI agents can chain individually permitted operations into outcomes nobody intended.

**Kontext** gives agents a runtime identity, evaluates supported tool calls against policy, and blocks disallowed actions before they reach protected systems. Every decision produces evidence showing what the agent attempted, which policy applied, and why the action was allowed or denied.

```bash
brew install kontext-security/tap/kontext
```

[View the Kontext repository →](https://github.com/kontext-security/kontext)

## Add process containment with Sandy

**Sandy** confines AI coding agents to explicitly permitted files, network destinations, and processes using native operating-system sandboxing on macOS and Linux.

```bash
brew install kontext-security/tap/sandy
```

[View the Sandy repository →](https://github.com/kontext-security/sandy)

## Two complementary security layers

| Layer | Question it answers | Project |
|---|---|---|
| Runtime authorization | Should this supported agent action proceed under policy? | [Kontext](https://github.com/kontext-security/kontext) |
| Process containment | What can this agent process access on the machine? | [Sandy](https://github.com/kontext-security/sandy) for macOS and Linux |

Use them independently or together for defense in depth.

## Open-source projects

| Repository | Description |
|---|---|
| [kontext](https://github.com/kontext-security/kontext) | Identity-aware runtime policy enforcement for AI agents |
| [sandy](https://github.com/kontext-security/sandy) | Native process containment for AI coding agents on macOS and Linux |
| [agent-skills](https://github.com/kontext-security/agent-skills) | Skills and integrations for using Kontext with AI agents |

## Join the community

- Explore the [documentation](https://kontext.security/docs)
- Join the [Discord community](https://discord.gg/gw9UpFUhyY)
- Follow [Kontext Security on X](https://twitter.com/kontextsecurity)
