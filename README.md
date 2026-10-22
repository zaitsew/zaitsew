<!-- Generated file. Do not edit by hand. -->

# Ivan Zaitsev

**One builder, a fleet of AI agents, apps people install.**

I design and ship AI-native products for iPhone, Mac, Android and the web from Valencia, Spain, through [Fabrique Futur](https://www.fafutur.com), the studio I co-founded. Agents write most of the code. I decide what gets built and what ships.

[X](https://x.com/ceozaitsev) · [LinkedIn](https://www.linkedin.com/in/zaitsew) · [Fabrique Futur](https://www.fafutur.com) · [Studio on GitHub](https://github.com/Fabrique-Futur)

> **3** you can use today · **3** open source · **8** in the workshop

## Use them today

<table>
  <tr>
    <td width="80"><a href="https://apps.apple.com/app/id6809226188?ct=github-profile&mt=8"><img src="https://raw.githubusercontent.com/zaitsew/zaitsew/main/assets/loco.png" width="64" height="64" alt="Loco icon"></a></td>
    <td><a href="https://apps.apple.com/app/id6809226188?ct=github-profile&mt=8"><b>Loco</b></a> — Shared trip plan: flights, stays, bookings and who is where, for the whole group.<br><a href="https://apps.apple.com/app/id6809226188?ct=github-profile&mt=8">App Store</a> (iPhone, iPad, Mac) · <a href="https://play.google.com/store/apps/details?id=com.fabriquefutur.loco&referrer=utm_source%3Dgithub%26utm_medium%3Dprofile">Google Play</a> (Android) · <a href="https://loco.fabriquefutur.com">Web</a> (any browser)</td>
  </tr>
  <tr>
    <td width="80"><a href="https://apps.apple.com/app/id6808361269?ct=github-profile&mt=8"><img src="https://raw.githubusercontent.com/zaitsew/zaitsew/main/assets/wine-cave.png" width="64" height="64" alt="Wine Cave icon"></a></td>
    <td><a href="https://apps.apple.com/app/id6808361269?ct=github-profile&mt=8"><b>Wine Cave</b></a> — A sommelier for your own cellar: tracks bottles, learns taste from verdicts, picks tonight's wine.<br><a href="https://apps.apple.com/app/id6808361269?ct=github-profile&mt=8">App Store</a> (iPhone, iPad, Mac) · <a href="https://play.google.com/store/apps/details?id=com.fabriquefutur.winecave&referrer=utm_source%3Dgithub%26utm_medium%3Dprofile">Google Play</a> (Android)</td>
  </tr>
  <tr>
    <td width="80"><a href="https://guiri.fabriquefutur.com"><img src="https://raw.githubusercontent.com/zaitsew/zaitsew/main/assets/guiri.png" width="64" height="64" alt="Guiri icon"></a></td>
    <td><a href="https://guiri.fabriquefutur.com"><b>Guiri</b></a> — Turns Spanish you meet into phrases you can say tomorrow, then drills them until they stick.<br><a href="https://guiri.fabriquefutur.com">Web</a> (any browser)</td>
  </tr>
</table>

## Open source

### [Teyla](https://github.com/zaitsew/teyla)

Operating layer for one person running many AI-built products on one Mac: questions, policy, cost, builds.

<sub>macOS · live</sub>

<details><summary>What it does today</summary>

- Lists agent questions still waiting on you, with links back
- Keeps long prompts in per-product intent files outside repos
- Syncs one policy file into Claude Code, Codex, Grok, Hermes, Cursor
- Reports agent cost by subagent type and model
- Machine guard refuses builds and simulators while overloaded
- Checks whether newest TestFlight and Play builds reached testers
- Reports whether scheduled routines ran, from teyla.toml
- Reports reply length and filler phrases per project

</details>

### [BankJar](https://github.com/zaitsew/bankjar)

Compares Spanish bank offers by goal, with AI search, open data and an MCP server.

<sub>web · building</sub>

<details><summary>What it does today</summary>

- Plain-words search returns a ranked offer comparison table
- One scale: first-year net value and value per commitment month
- Goal leaderboards, offer pages and side-by-side compare
- Open dataset: one dated, sourced YAML file per offer
- JSON API, OpenAPI, llms.txt and a remote MCP server
- Bank app ranking from store ratings, freshness and payment features

</details>

### [CasaVPN](https://github.com/zaitsew/casavpn)

Installer and tooling for a home VLESS + Reality VPN on a Raspberry Pi, with backups, monitoring and an iPhone app.

<sub>Linux (Raspberry Pi), iOS · building</sub>

<details><summary>What it does today</summary>

- install.sh with --dry-run; installs VLESS + Reality behind nftables
- casavpn-ddns reconciles the Cloudflare DNS record every minute
- Nightly age-encrypted backup and a restore drill script
- casavpn-upgrade backs up, pins 3x-ui, and rolls back
- casavpn-healthcheck verifies every layer on the host
- Cloudflare Worker monitor and alert relay with APNs push
- casavpn-alerts: certificate, client quota, Xray, backup, disk and reboot alerts
- iPhone app signs in like the panel and keeps only its own token
- App manages inbounds (Reality), clients, Xray restart and logs
- App shares client links and subscriptions as text or QR
- App alert history, push, and an offline demo mode
- casavpn-pair prints a QR code that pairs the app
- Offline tests and a personal-data scanner in check.sh

</details>

## In the workshop

In TestFlight or still being built. Want early access? Message me on [X](https://x.com/ceozaitsev).

| | | On | What it is |
|---|---|---|---|
|  | **Afterglow** | iOS | Long-exposure camera for iPhone with Silk, Trails and Freeze effects. |
| <img src="https://raw.githubusercontent.com/zaitsew/zaitsew/main/assets/finca.png" width="32" height="32" alt="Finca icon"> | **Finca** | iOS | A barista for your own coffee: tracks bean bags, freshness, brews and taste. |
| <img src="https://raw.githubusercontent.com/zaitsew/zaitsew/main/assets/iron-u.png" width="32" height="32" alt="Iron U icon"> | **Iron U** | iOS, macOS, Android, web, Garmin | Closed-loop Ironman 70.3 coach: writes the plan, pushes it to the watch, reads results, adapts. |
| <img src="https://raw.githubusercontent.com/zaitsew/zaitsew/main/assets/lumi.png" width="32" height="32" alt="Lumi icon"> | **Lumi** | iOS, macOS | AI shot director for iPhone: plans the outing, checks each take, cuts the film from footage. |
| <img src="https://raw.githubusercontent.com/zaitsew/zaitsew/main/assets/orbita.png" width="32" height="32" alt="Orbita icon"> | **Orbita** | iOS, macOS | Your network as four rings: who is going cold, birthdays, promises, and what you owe each person. |
| <img src="https://raw.githubusercontent.com/zaitsew/zaitsew/main/assets/petit-chef.png" width="32" height="32" alt="Petit Chef icon"> | **Petit Chef** | iOS | Runs a recipe like a workout: an overview, then one timed step per screen with voice cues. |
|  | **Beyond Intelligence** | web | Weekly, monthly and yearly brief and dashboard on AI and startups. |
|  | **Elecarm** | web | Compare European electric cars and A2/A motorcycles, with transparent rankings and sourced Spanish offer snapshots. |

## How I build

- **Agents do the volume.** Claude plans and reviews; cheaper models write tests, docs and boilerplate. On a good day that is 100–500 commits.
- **A second provider reviews.** Code one model wrote is reviewed by a model from another provider before it merges.
- **The laptop is the CI.** One `check.sh` gate per repo runs before every push.
- **One policy for every agent.** [Teyla](https://github.com/zaitsew/teyla) keeps the rules, open questions and costs for all of it in one place. It is open source.

<sub>Generated from my tools catalog, so it lists what ships today, not what is planned.</sub>
