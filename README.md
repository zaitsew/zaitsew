<!-- Generated file. Do not edit by hand. -->

# Ivan

I build AI-native tools and apps. The company's products live at
[Fabrique Futur](https://github.com/Fabrique-Futur).

## Open source

| | Status | Platforms | What it is |
|---|---|---|---|
| [Teyla](https://github.com/zaitsew/teyla) | live | macOS | Operating layer for one person running many AI-built products on one Mac: questions, policy, cost, builds. |
| [CasaVPN](https://github.com/zaitsew/casavpn) | building | Linux (Raspberry Pi) | Installer and tooling for a home VLESS + Reality VPN on a Raspberry Pi, with backups and monitoring. |

### [Teyla](https://github.com/zaitsew/teyla)

Operating layer for one person running many AI-built products on one Mac: questions, policy, cost, builds.

- Lists agent questions still waiting on you, with links back
- Keeps long prompts in per-product intent files outside repos
- Syncs one policy file into Claude Code, Codex, Grok, Hermes, Cursor
- Reports agent cost by subagent type and model
- Machine guard refuses builds and simulators while overloaded
- Checks whether newest TestFlight and Play builds reached testers
- Reports whether scheduled routines ran, from teyla.toml
- Reports reply length and filler phrases per project

### [CasaVPN](https://github.com/zaitsew/casavpn)

Installer and tooling for a home VLESS + Reality VPN on a Raspberry Pi, with backups and monitoring.

- install.sh with --dry-run; installs VLESS + Reality behind nftables
- casavpn-ddns reconciles the Cloudflare DNS record every minute
- Nightly age-encrypted backup and a restore drill script
- casavpn-upgrade backs up, pins 3x-ui, and rolls back
- casavpn-healthcheck verifies every layer on the host
- Cloudflare Worker monitor sends ntfy alerts
- Offline tests and a personal-data scanner in check.sh
