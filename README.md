# Awesome Red Alerts

A curated list of open-source and community projects aiming to expand the alerting surface of Home Front Command Red Alerts (צבע אדום).

> **Disclaimer:** Never rely on community projects as your primary alerting mechanism if you are based in Israel. The official and only reliable alerts are those provided directly by the [Home Front Command](https://www.oref.org.il/en).

## Contents

- [Official Resources & Services](#official-resources--services)
- [Geo-Dashboards](#geo-dashboards)
- [API / Alert Feed Wrappers](#api--alert-feed-wrappers)
- [SDKs & Libraries](#sdks--libraries)
- [CLI](#cli)
- [Home Automation](#home-automation)
- [MagicMirror](#magicmirror)
- [Notifiers](#notifiers)
- [Bots](#bots)
- [Integrations](#integrations)
- [Hardware](#hardware)
- [Analysis & Infographics](#analysis--infographics)
- [Civilian Readiness & Preparedness](#civilian-readiness--preparedness)
- [Resource Lists](#resource-lists)
- [Other](#other)
- [FAQ](#faq)
- [Contributing](#contributing)

---

## Official Resources & Services

### Home Front Command (Pikud HaOref)

- [Alerts History](https://www.oref.org.il/eng/alerts-history) — Official alert history *(geo-restricted)*
- [Pikud HaOref Telegram](https://t.me/PikudHaOref_all) — Official Telegram channel for all alerts

### Tzofar (צופר)

- [Tzofar Website](https://www.tzevaadom.co.il/en/) — Real-time alert website
- [Tzofar Android App](https://play.google.com/store/apps/details?id=com.red.alert) — Google Play
- [Tzofar iOS App](https://apps.apple.com/il/app/tzofar-red-alert/id1480129320) — App Store
- [Tzofar Chrome Extension](https://chromewebstore.google.com/detail/%D7%A6%D7%95%D7%A4%D7%A8-%D7%A6%D7%91%D7%A2-%D7%90%D7%93%D7%95%D7%9D/hpbdhanjafnpeeobgejmdaajkiamfdpi?hl=en&pli=1) — Browser extension ![Recommended](https://img.shields.io/badge/-Recommended-brightgreen)
- [Tzofar WhatsApp Channel](https://www.whatsapp.com/channel/0029Va6c4jpIHphPAwLl4j0q) — WhatsApp alert channel

### Other Services

- [RocketAlert.live](https://rocketalert.live/) — Live rocket alert tracker
- [Tzevadom](https://tzevadom.com/en/) — Real-time alert website
- [ILRedAlert on X](https://x.com/ILRedAlert) — Alert feed on X (Twitter)

---

## Geo-Dashboards

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [oref-map](https://github.com/maorcc/oref-map) | maorcc | Oref alert map | ![Stars](https://img.shields.io/github/stars/maorcc/oref-map?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/maorcc/oref-map) |
| [Red-Alert-Geodash](https://github.com/danielrosehill/Red-Alert-Geodash) | danielrosehill | Red alert geographic dashboard | ![Stars](https://img.shields.io/github/stars/danielrosehill/Red-Alert-Geodash?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Red-Alert-Geodash) |
| [pikud-haoref-map](https://github.com/avisratmp-stack/pikud-haoref-map) | avisratmp-stack | Pikud HaOref alert map | ![Stars](https://img.shields.io/github/stars/avisratmp-stack/pikud-haoref-map?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/avisratmp-stack/pikud-haoref-map) |
| [oref](https://github.com/jilaboon/oref) | jilaboon | Oref alert map | ![Stars](https://img.shields.io/github/stars/jilaboon/oref?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/jilaboon/oref) |
| [red-alert-map](https://github.com/aviv4339/red-alert-map) | aviv4339 | Red alert map | ![Stars](https://img.shields.io/github/stars/aviv4339/red-alert-map?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/aviv4339/red-alert-map) |
| [hatraot](https://github.com/adipalko/hatraot) | adipalko | Alert map | ![Stars](https://img.shields.io/github/stars/adipalko/hatraot?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/adipalko/hatraot) |
| [tilon](https://github.com/gunr1984-jonost/tilon) | gunr1984-jonost | Alert map | ![Stars](https://img.shields.io/github/stars/gunr1984-jonost/tilon?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/gunr1984-jonost/tilon) |
| [HA-Red-Alert-News-Dash](https://github.com/danielrosehill/HA-Red-Alert-News-Dash) | danielrosehill | Home Assistant red alert news dashboard *(legacy)* | ![Stars](https://img.shields.io/github/stars/danielrosehill/HA-Red-Alert-News-Dash?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/HA-Red-Alert-News-Dash) |

## API / Alert Feed Wrappers

> **Note:** There is no official public API for Home Front Command alerts. All projects in this section are unofficial wrappers built around the Home Front Command's internal data streams.

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [pikud-haoref-api-graphql](https://github.com/TuvalSimha/pikud-haoref-api-graphql) | TuvalSimha | GraphQL wrapper for the Pikud HaOref API | ![Stars](https://img.shields.io/github/stars/TuvalSimha/pikud-haoref-api-graphql?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/TuvalSimha/pikud-haoref-api-graphql) |
| [pikud-haoref-api](https://github.com/eladnava/pikud-haoref-api) | eladnava | Node.js wrapper for the Pikud HaOref API | ![Stars](https://img.shields.io/github/stars/eladnava/pikud-haoref-api?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/eladnava/pikud-haoref-api) |
| [python-red-alert](https://github.com/Zontex/python-red-alert) | Zontex | Python red alert wrapper *(legacy)* | ![Stars](https://img.shields.io/github/stars/Zontex/python-red-alert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/Zontex/python-red-alert) |
| [python-pikudHaoref-api](https://github.com/reinerstone/python-pikudHaoref-api) | reinerstone | Python Pikud HaOref API wrapper *(legacy)* | ![Stars](https://img.shields.io/github/stars/reinerstone/python-pikudHaoref-api?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/reinerstone/python-pikudHaoref-api) |

## SDKs & Libraries

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [pikud-haoref-api-go](https://github.com/5c077m4n/pikud-haoref-api-go) | 5c077m4n | Go SDK for the Pikud HaOref API | ![Stars](https://img.shields.io/github/stars/5c077m4n/pikud-haoref-api-go?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/5c077m4n/pikud-haoref-api-go) |

## CLI

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [waralerts](https://github.com/yprez/waralerts) | yprez | Command-line alert monitor | ![Stars](https://img.shields.io/github/stars/yprez/waralerts?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/yprez/waralerts) |

## Home Automation

### Home Assistant

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [oref_alert](https://github.com/amitfin/oref_alert) | amitfin | Home Assistant integration for Oref alerts | ![Stars](https://img.shields.io/github/stars/amitfin/oref_alert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/amitfin/oref_alert) |
| [Home-Assistant-Red-Alert-Automations](https://github.com/danielrosehill/Home-Assistant-Red-Alert-Automations) | danielrosehill | Home Assistant automation configurations for red alerts | ![Stars](https://img.shields.io/github/stars/danielrosehill/Home-Assistant-Red-Alert-Automations?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Home-Assistant-Red-Alert-Automations) |

### Homebridge

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [homebridge-pikud-haoref](https://github.com/GhostOnyx/homebridge-pikud-haoref) | GhostOnyx | Homebridge plugin for Pikud HaOref alerts | ![Stars](https://img.shields.io/github/stars/GhostOnyx/homebridge-pikud-haoref?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/GhostOnyx/homebridge-pikud-haoref) |

### Philips Hue

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [oref-lights](https://github.com/sashka-ltd/oref-lights) | sashka-ltd | Philips Hue light integration for Oref alerts | ![Stars](https://img.shields.io/github/stars/sashka-ltd/oref-lights?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/sashka-ltd/oref-lights) |

### Roborock

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [roborock-missile-alert](https://github.com/DeDuckProject/roborock-missile-alert) | DeDuckProject | Roborock vacuum automation triggered by missile alerts | ![Stars](https://img.shields.io/github/stars/DeDuckProject/roborock-missile-alert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/DeDuckProject/roborock-missile-alert) |

## MagicMirror

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [MMM-RedAlert](https://github.com/Moran-k/MMM-RedAlert) | Moran-k | MagicMirror red alert module | ![Stars](https://img.shields.io/github/stars/Moran-k/MMM-RedAlert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/Moran-k/MMM-RedAlert) |
| [MMM-PikudHaoref](https://github.com/oriyaakov/MMM-PikudHaoref) | oriyaakov | MagicMirror module for Pikud HaOref alerts | ![Stars](https://img.shields.io/github/stars/oriyaakov/MMM-PikudHaoref?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/oriyaakov/MMM-PikudHaoref) |

## Notifiers

| Project | Author | Platform | Description | Stars | Last Commit |
|---------|--------|----------|-------------|-------|-------------|
| [israel-homefront-macos-notifier](https://github.com/amito/israel-homefront-macos-notifier) | amito | macOS | Desktop notifier for Israel homefront alerts | ![Stars](https://img.shields.io/github/stars/amito/israel-homefront-macos-notifier?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/amito/israel-homefront-macos-notifier) |
| [RedAlert](https://github.com/Amtrtm/RedAlert) | Amtrtm | Windows | Desktop red alert notifications | ![Stars](https://img.shields.io/github/stars/Amtrtm/RedAlert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/Amtrtm/RedAlert) |
| [Red-Alert-MQTT-Desktop-Notifier-Public](https://github.com/danielrosehill/Red-Alert-MQTT-Desktop-Notifier-Public) | danielrosehill | MQTT | MQTT-based desktop notifier for red alerts | ![Stars](https://img.shields.io/github/stars/danielrosehill/Red-Alert-MQTT-Desktop-Notifier-Public?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Red-Alert-MQTT-Desktop-Notifier-Public) |
| [pikud_haoref_mqtt](https://github.com/yeheskel2016/pikud_haoref_mqtt) | yeheskel2016 | MQTT | MQTT integration for Pikud HaOref alerts | ![Stars](https://img.shields.io/github/stars/yeheskel2016/pikud_haoref_mqtt?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/yeheskel2016/pikud_haoref_mqtt) |
| [pikud](https://github.com/erikzaadi/pikud) | erikzaadi | Raspberry Pi | Raspberry Pi red alert notifier | ![Stars](https://img.shields.io/github/stars/erikzaadi/pikud?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/erikzaadi/pikud) |
| [miklat-alert](https://github.com/t0mer/miklat-alert) | t0mer | Raspberry Pi | Raspberry Pi visual alert indicator | ![Stars](https://img.shields.io/github/stars/t0mer/miklat-alert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/t0mer/miklat-alert) |
| [alert_call](https://github.com/ophiri/alert_call) | ophiri | VoIP | Phone call alerts for red alerts | ![Stars](https://img.shields.io/github/stars/ophiri/alert_call?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/ophiri/alert_call) |

## Bots

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [pikud-haoref-memukad-bot](https://github.com/roigreenberg/pikud-haoref-memukad-bot) | roigreenberg | Pikud HaOref Memukad bot | ![Stars](https://img.shields.io/github/stars/roigreenberg/pikud-haoref-memukad-bot?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/roigreenberg/pikud-haoref-memukad-bot) |
| [pikud-haoref-bot](https://github.com/zitzman/pikud-haoref-bot) | zitzman | Pikud HaOref bot | ![Stars](https://img.shields.io/github/stars/zitzman/pikud-haoref-bot?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/zitzman/pikud-haoref-bot) |

## Integrations

### Claude / AI

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [pikud-haoref-alerts](https://github.com/yaniv-golan/pikud-haoref-alerts) | yaniv-golan | Pikud HaOref alerts integration for Claude | ![Stars](https://img.shields.io/github/stars/yaniv-golan/pikud-haoref-alerts?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/yaniv-golan/pikud-haoref-alerts) |
| [cc-redalerts-statusline](https://github.com/alonw0/cc-redalerts-statusline) | alonw0 | Claude Code statusline for red alerts | ![Stars](https://img.shields.io/github/stars/alonw0/cc-redalerts-statusline?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/alonw0/cc-redalerts-statusline) |
| [red-alert-statusline](https://github.com/lirantal/red-alert-statusline) | lirantal | Red alert statusline for Claude Code | ![Stars](https://img.shields.io/github/stars/lirantal/red-alert-statusline?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/lirantal/red-alert-statusline) |

### Slack

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [pikud-haoref-slack](https://github.com/zivhundert/pikud-haoref-slack) | zivhundert | Pikud HaOref Slack integration | ![Stars](https://img.shields.io/github/stars/zivhundert/pikud-haoref-slack?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/zivhundert/pikud-haoref-slack) |
| [oref-alerts-bot](https://github.com/anthonyangel/oref-alerts-bot) | anthonyangel | Oref alerts Slack bot | ![Stars](https://img.shields.io/github/stars/anthonyangel/oref-alerts-bot?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/anthonyangel/oref-alerts-bot) |

### Discord

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [PikudHaoref-Discord](https://github.com/Avir4m/PikudHaoref-Discord) | Avir4m | Pikud HaOref Discord notifications | ![Stars](https://img.shields.io/github/stars/Avir4m/PikudHaoref-Discord?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/Avir4m/PikudHaoref-Discord) |

### Telegram

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [multi-city-alert-monitor](https://github.com/rinad12/multi-city-alert-monitor) | rinad12 | Multi-city alert monitor for Telegram | ![Stars](https://img.shields.io/github/stars/rinad12/multi-city-alert-monitor?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/rinad12/multi-city-alert-monitor) |

### WhatsApp

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [pikued-haoref-whatsapp-bot](https://github.com/lkeness/pikued-haoref-whatsapp-bot) | lkeness | Pikud HaOref WhatsApp bot | ![Stars](https://img.shields.io/github/stars/lkeness/pikued-haoref-whatsapp-bot?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/lkeness/pikued-haoref-whatsapp-bot) |

## Hardware

| Project | Author | Platform | Description | Stars | Last Commit |
|---------|--------|----------|-------------|-------|-------------|
| [esp32c3-red-alert](https://github.com/amir684/esp32c3-red-alert) | amir684 | ESP32 | ESP32-C3 red alert notifier | ![Stars](https://img.shields.io/github/stars/amir684/esp32c3-red-alert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/amir684/esp32c3-red-alert) |

## Analysis & Infographics

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [haoref-alert-analysis](https://github.com/TomerAntman/haoref-alert-analysis) | TomerAntman | Analysis of HaOref alert data | ![Stars](https://img.shields.io/github/stars/TomerAntman/haoref-alert-analysis?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/TomerAntman/haoref-alert-analysis) |
| [Infographic-Generator-Pikud-Haoref](https://github.com/Shalev-Aviv/Infographic-Generator-Pikud-Haoref) | Shalev-Aviv | Infographic generator for Pikud HaOref data | ![Stars](https://img.shields.io/github/stars/Shalev-Aviv/Infographic-Generator-Pikud-Haoref?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/Shalev-Aviv/Infographic-Generator-Pikud-Haoref) |

## Civilian Readiness & Preparedness

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Israel-Civilian-Readiness-Guide](https://github.com/danielrosehill/Israel-Civilian-Readiness-Guide) | danielrosehill | Civilian readiness guide for Israel | ![Stars](https://img.shields.io/github/stars/danielrosehill/Israel-Civilian-Readiness-Guide?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Israel-Civilian-Readiness-Guide) |
| [Israel-Preparedness-SOPs](https://github.com/danielrosehill/Israel-Preparedness-SOPs) | danielrosehill | Standard operating procedures for preparedness in Israel | ![Stars](https://img.shields.io/github/stars/danielrosehill/Israel-Preparedness-SOPs?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Israel-Preparedness-SOPs) |
| [Pikud-Haoref-Guidelines-0326](https://github.com/danielrosehill/Pikud-Haoref-Guidelines-0326) | danielrosehill | Pikud HaOref guidelines formatted for AI context ingestion | ![Stars](https://img.shields.io/github/stars/danielrosehill/Pikud-Haoref-Guidelines-0326?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Pikud-Haoref-Guidelines-0326) |
| [Miklat-MCP](https://github.com/danielrosehill/Miklat-MCP) | danielrosehill | MCP server for shelter (miklat) information | ![Stars](https://img.shields.io/github/stars/danielrosehill/Miklat-MCP?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Miklat-MCP) |

## Resource Lists

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Magen](https://github.com/thewh1teagle/Magen) | thewh1teagle | Curated resource list for civilian protection | ![Stars](https://img.shields.io/github/stars/thewh1teagle/Magen?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/thewh1teagle/Magen) |

## Other

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [alerts](https://github.com/noam767/alerts) | noam767 | Alerts project | ![Stars](https://img.shields.io/github/stars/noam767/alerts?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/noam767/alerts) |

---

## FAQ

**How do these alerts work?**

There is no official public API for Home Front Command alerts. Consequently, all open-source projects listed here are unofficial wrappers and integrations built around the Home Front Command's internal data streams.

**Should I rely on these for my safety?**

No. These are community projects and may experience downtime, delays, or inaccuracies. Always use the official [Home Front Command app](https://www.oref.org.il/en) and your local municipal alert system as your primary source.

---

## Contributing

We welcome contributions to this list! If you have a project you would like to add, please submit a [pull request](https://github.com/danielrosehill/Awesome-Red-Alerts/pulls) or email [opensource@danielrosehill.com](mailto:opensource@danielrosehill.com).
