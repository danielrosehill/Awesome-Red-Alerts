![Red Alert Open Source Projects](banner.png)

# Awesome Red Alerts

A curated list of open-source and community projects aiming to expand the alerting surface of Home Front Command Red Alerts (צבע אדום).

> **Disclaimer:** Never rely on community projects as your primary alerting mechanism if you are based in Israel. The official and only reliable alerts are those provided directly by the [Home Front Command](https://www.oref.org.il/en).

## Contents

- [Official Resources](#official-resources)
- [Third-Party Alerting Services](#third-party-alerting-services)
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
- [Full Monitoring Stacks](#full-monitoring-stacks)
- [Resource Lists](#resource-lists)
- [Other](#other)
- [FAQ](#faq)
- [Contributing](#contributing)

---

## Official Resources

The Home Front Command (פיקוד העורף / Pikud HaOref) is the only official source for red alerts in Israel.

- [Home Front Command Website](https://www.oref.org.il/en) — Official website with alert guidelines, shelter information, and safety instructions
- [Alerts History](https://www.oref.org.il/eng/alerts-history) — Official alert history *(geo-restricted to Israel)*
- [Pikud HaOref Telegram](https://t.me/PikudHaOref_all) — Official Telegram channel broadcasting all alerts in real time

---

## Third-Party Alerting Services

These are independently operated services that relay Home Front Command alerts. They are not official but are widely used.

### Tzofar (צופר)

Popular third-party alert service with apps across all major platforms.

- [Tzofar Website](https://www.tzevaadom.co.il/en/) — Real-time web-based alert dashboard
- [Tzofar Android App](https://play.google.com/store/apps/details?id=com.red.alert) — Google Play
- [Tzofar iOS App](https://apps.apple.com/il/app/tzofar-red-alert/id1480129320) — App Store
- [Tzofar Chrome Extension](https://chromewebstore.google.com/detail/%D7%A6%D7%95%D7%A4%D7%A8-%D7%A6%D7%91%D7%A2-%D7%90%D7%93%D7%95%D7%9D/hpbdhanjafnpeeobgejmdaajkiamfdpi?hl=en&pli=1) — Browser push notifications for Chrome ![Recommended](https://img.shields.io/badge/-Recommended-brightgreen)
- [Tzofar WhatsApp Channel](https://www.whatsapp.com/channel/0029Va6c4jpIHphPAwLl4j0q) — WhatsApp alert channel

### Other Services

- [Oref Map](https://oref-map.org/) — Live geographic alert map with real-time visualization
- [RocketAlert.live](https://rocketalert.live/) — Live rocket alert tracker with map and history
- [Tzevadom](https://tzevadom.com/en/) — Real-time alert website with push notifications
- [ILRedAlert on X](https://x.com/ILRedAlert) — Automated alert feed on X (Twitter)

---

## Geo-Dashboards

Interactive maps and dashboards for visualizing alert data geographically.

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Oref Map](https://github.com/maorcc/oref-map) | maorcc | Real-time interactive alert map with shelter locations | ![Stars](https://img.shields.io/github/stars/maorcc/oref-map?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/maorcc/oref-map) |
| [Red Alert Geodash](https://github.com/danielrosehill/Red-Alert-Geodash) | danielrosehill | Geographic dashboard for visualizing red alert patterns | ![Stars](https://img.shields.io/github/stars/danielrosehill/Red-Alert-Geodash?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Red-Alert-Geodash) |
| [Pikud HaOref Map](https://github.com/avisratmp-stack/pikud-haoref-map) | avisratmp-stack | Web-based Pikud HaOref alert map | ![Stars](https://img.shields.io/github/stars/avisratmp-stack/pikud-haoref-map?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/avisratmp-stack/pikud-haoref-map) |
| [Oref](https://github.com/jilaboon/oref) | jilaboon | Oref alert map visualization | ![Stars](https://img.shields.io/github/stars/jilaboon/oref?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/jilaboon/oref) |
| [Red Alert Map](https://github.com/aviv4339/red-alert-map) | aviv4339 | Red alert geographic map | ![Stars](https://img.shields.io/github/stars/aviv4339/red-alert-map?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/aviv4339/red-alert-map) |
| [Hatraot](https://github.com/adipalko/hatraot) | adipalko | Alert map dashboard | ![Stars](https://img.shields.io/github/stars/adipalko/hatraot?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/adipalko/hatraot) |
| [Tilon](https://github.com/gunr1984-jonost/tilon) | gunr1984-jonost | Alert map dashboard | ![Stars](https://img.shields.io/github/stars/gunr1984-jonost/tilon?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/gunr1984-jonost/tilon) |
| [HA Red Alert News Dash](https://github.com/danielrosehill/HA-Red-Alert-News-Dash) | danielrosehill | Home Assistant red alert news dashboard *(legacy)* | ![Stars](https://img.shields.io/github/stars/danielrosehill/HA-Red-Alert-News-Dash?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/HA-Red-Alert-News-Dash) |

## API / Alert Feed Wrappers

> **Note:** There is no official public API for Home Front Command alerts. All projects in this section are unofficial wrappers built around the Home Front Command's internal data streams. The internal alert format and endpoints have changed several times over the years, so older projects may no longer work without updates. Check the last commit date and open issues before depending on any wrapper.

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Pikud HaOref API GraphQL](https://github.com/TuvalSimha/pikud-haoref-api-graphql) | TuvalSimha | GraphQL wrapper providing typed queries over alert data | ![Stars](https://img.shields.io/github/stars/TuvalSimha/pikud-haoref-api-graphql?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/TuvalSimha/pikud-haoref-api-graphql) |
| [Pikud HaOref API](https://github.com/eladnava/pikud-haoref-api) | eladnava | Node.js wrapper with real-time polling and city mapping | ![Stars](https://img.shields.io/github/stars/eladnava/pikud-haoref-api?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/eladnava/pikud-haoref-api) |
| [Python Red Alert](https://github.com/Zontex/python-red-alert) | Zontex | Python wrapper for alert data *(legacy)* | ![Stars](https://img.shields.io/github/stars/Zontex/python-red-alert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/Zontex/python-red-alert) |
| [Python Pikud HaOref API](https://github.com/reinerstone/python-pikudHaoref-api) | reinerstone | Python API client for Pikud HaOref *(legacy)* | ![Stars](https://img.shields.io/github/stars/reinerstone/python-pikudHaoref-api?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/reinerstone/python-pikudHaoref-api) |
| [Oref Alert Proxy](https://github.com/danielrosehill/Oref-Alert-Proxy) | danielrosehill | Local relay proxy for Pikud HaOref alert data | ![Stars](https://img.shields.io/github/stars/danielrosehill/Oref-Alert-Proxy?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Oref-Alert-Proxy) |

## SDKs & Libraries

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Pikud HaOref API Go](https://github.com/5c077m4n/pikud-haoref-api-go) | 5c077m4n | Go SDK for querying Pikud HaOref alert data | ![Stars](https://img.shields.io/github/stars/5c077m4n/pikud-haoref-api-go?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/5c077m4n/pikud-haoref-api-go) |

## CLI

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [War Alerts](https://github.com/yprez/waralerts) | yprez | Terminal-based alert monitor with real-time output | ![Stars](https://img.shields.io/github/stars/yprez/waralerts?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/yprez/waralerts) |

## Home Automation

### Home Assistant

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Oref Alert](https://github.com/amitfin/oref_alert) | amitfin | HACS integration providing alert sensors and automations | ![Stars](https://img.shields.io/github/stars/amitfin/oref_alert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/amitfin/oref_alert) |
| [Home Assistant Red Alert Automations](https://github.com/danielrosehill/Home-Assistant-Red-Alert-Automations) | danielrosehill | Ready-made HA automation YAML configs for red alerts | ![Stars](https://img.shields.io/github/stars/danielrosehill/Home-Assistant-Red-Alert-Automations?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Home-Assistant-Red-Alert-Automations) |

### Homebridge

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Homebridge Pikud HaOref](https://github.com/GhostOnyx/homebridge-pikud-haoref) | GhostOnyx | Homebridge plugin exposing alerts as HomeKit accessories | ![Stars](https://img.shields.io/github/stars/GhostOnyx/homebridge-pikud-haoref?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/GhostOnyx/homebridge-pikud-haoref) |

### MQTT / Snapcast

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Red Alert Actuator](https://github.com/danielrosehill/Red-Alert-Actuator) | danielrosehill | Physical alert outputs: pre-recorded TTS via Snapcast whole-house audio + smart light color control via MQTT | ![Stars](https://img.shields.io/github/stars/danielrosehill/Red-Alert-Actuator?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Red-Alert-Actuator) |

### Philips Hue

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Oref Lights](https://github.com/sashka-ltd/oref-lights) | sashka-ltd | Flashes Hue lights red on incoming alerts | ![Stars](https://img.shields.io/github/stars/sashka-ltd/oref-lights?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/sashka-ltd/oref-lights) |

### Roborock

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Roborock Missile Alert](https://github.com/DeDuckProject/roborock-missile-alert) | DeDuckProject | Sends Roborock vacuum to dock on missile alert | ![Stars](https://img.shields.io/github/stars/DeDuckProject/roborock-missile-alert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/DeDuckProject/roborock-missile-alert) |

## MagicMirror

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [MMM Red Alert](https://github.com/Moran-k/MMM-RedAlert) | Moran-k | MagicMirror module displaying active red alerts | ![Stars](https://img.shields.io/github/stars/Moran-k/MMM-RedAlert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/Moran-k/MMM-RedAlert) |
| [MMM Pikud HaOref](https://github.com/oriyaakov/MMM-PikudHaoref) | oriyaakov | MagicMirror module for Pikud HaOref alert display | ![Stars](https://img.shields.io/github/stars/oriyaakov/MMM-PikudHaoref?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/oriyaakov/MMM-PikudHaoref) |

## Notifiers

### ![Pushover](https://img.shields.io/badge/-Pushover-249DF1?logo=pushover&logoColor=white)

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Red Alert Pushover](https://github.com/danielrosehill/Red-Alert-Pushover) | danielrosehill | Pushover push notifications when nationwide alert count crosses thresholds (50/100/200/.../1000 areas) for large-scale situational awareness | ![Stars](https://img.shields.io/github/stars/danielrosehill/Red-Alert-Pushover?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Red-Alert-Pushover) |
| [Red Alert OSINT Notifier](https://github.com/danielrosehill/Red-Alert-OSINT-Notifier) | danielrosehill | Unified Pushover notification + OSINT module: monitors Telegram channels (EN/HE) for missile launches, Oref volumetric thresholds, and Groq-powered intel reports for configurable local-area events | ![Stars](https://img.shields.io/github/stars/danielrosehill/Red-Alert-OSINT-Notifier?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Red-Alert-OSINT-Notifier) |

### ![macOS](https://img.shields.io/badge/-macOS-000000?logo=apple&logoColor=white)

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Israel Homefront macOS Notifier](https://github.com/amito/israel-homefront-macos-notifier) | amito | Native macOS notification center alerts for incoming rockets | ![Stars](https://img.shields.io/github/stars/amito/israel-homefront-macos-notifier?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/amito/israel-homefront-macos-notifier) |

### ![Windows](https://img.shields.io/badge/-Windows-0078D6?logo=windows&logoColor=white)

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Red Alert](https://github.com/Amtrtm/RedAlert) | Amtrtm | Windows desktop toast notifications for red alerts | ![Stars](https://img.shields.io/github/stars/Amtrtm/RedAlert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/Amtrtm/RedAlert) |

### ![MQTT](https://img.shields.io/badge/-MQTT-660066?logo=mqtt&logoColor=white)

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Red Alert MQTT Desktop Notifier](https://github.com/danielrosehill/Red-Alert-MQTT-Desktop-Notifier-Public) | danielrosehill | Publishes alerts to MQTT broker for desktop notifications | ![Stars](https://img.shields.io/github/stars/danielrosehill/Red-Alert-MQTT-Desktop-Notifier-Public?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Red-Alert-MQTT-Desktop-Notifier-Public) |
| [Pikud HaOref MQTT](https://github.com/yeheskel2016/pikud_haoref_mqtt) | yeheskel2016 | Bridges Pikud HaOref alerts to MQTT topics | ![Stars](https://img.shields.io/github/stars/yeheskel2016/pikud_haoref_mqtt?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/yeheskel2016/pikud_haoref_mqtt) |

### ![Raspberry Pi](https://img.shields.io/badge/-Raspberry%20Pi-A22846?logo=raspberrypi&logoColor=white)

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Pikud](https://github.com/erikzaadi/pikud) | erikzaadi | RPi alert notifier with LED and sound output | ![Stars](https://img.shields.io/github/stars/erikzaadi/pikud?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/erikzaadi/pikud) |
| [Miklat Alert](https://github.com/t0mer/miklat-alert) | t0mer | RPi visual indicator with LED strip for shelter alerts | ![Stars](https://img.shields.io/github/stars/t0mer/miklat-alert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/t0mer/miklat-alert) |

### ![VoIP](https://img.shields.io/badge/-VoIP-4B8BBE?logo=phone&logoColor=white)

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Alert Call](https://github.com/ophiri/alert_call) | ophiri | Triggers automated phone calls on incoming alerts | ![Stars](https://img.shields.io/github/stars/ophiri/alert_call?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/ophiri/alert_call) |

## Bots

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Pikud HaOref Memukad Bot](https://github.com/roigreenberg/pikud-haoref-memukad-bot) | roigreenberg | Automated Pikud HaOref alert aggregation bot | ![Stars](https://img.shields.io/github/stars/roigreenberg/pikud-haoref-memukad-bot?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/roigreenberg/pikud-haoref-memukad-bot) |
| [Pikud HaOref Bot](https://github.com/zitzman/pikud-haoref-bot) | zitzman | Pikud HaOref alert relay bot | ![Stars](https://img.shields.io/github/stars/zitzman/pikud-haoref-bot?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/zitzman/pikud-haoref-bot) |

## Integrations

### Claude Code

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [CC Red Alerts Statusline](https://github.com/alonw0/cc-redalerts-statusline) | alonw0 | Claude Code statusline showing active red alerts | ![Stars](https://img.shields.io/github/stars/alonw0/cc-redalerts-statusline?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/alonw0/cc-redalerts-statusline) |
| [Red Alert Statusline](https://github.com/lirantal/red-alert-statusline) | lirantal | Claude Code statusline plugin for red alert awareness | ![Stars](https://img.shields.io/github/stars/lirantal/red-alert-statusline?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/lirantal/red-alert-statusline) |

### MCP

Model Context Protocol servers that expose alert and shelter data to AI assistants.

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Pikud HaOref Alerts](https://github.com/yaniv-golan/pikud-haoref-alerts) | yaniv-golan | MCP server providing live alert data to Claude | ![Stars](https://img.shields.io/github/stars/yaniv-golan/pikud-haoref-alerts?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/yaniv-golan/pikud-haoref-alerts) |
| [Miklat MCP](https://github.com/danielrosehill/Miklat-MCP) | danielrosehill | MCP server providing shelter (miklat) location data to AI agents | ![Stars](https://img.shields.io/github/stars/danielrosehill/Miklat-MCP?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Miklat-MCP) |

### Slack

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Pikud HaOref Slack](https://github.com/zivhundert/pikud-haoref-slack) | zivhundert | Posts alerts to Slack channels in real time | ![Stars](https://img.shields.io/github/stars/zivhundert/pikud-haoref-slack?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/zivhundert/pikud-haoref-slack) |
| [Oref Alerts Bot](https://github.com/anthonyangel/oref-alerts-bot) | anthonyangel | Slack bot relaying Oref alerts with location details | ![Stars](https://img.shields.io/github/stars/anthonyangel/oref-alerts-bot?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/anthonyangel/oref-alerts-bot) |

### Discord

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Pikud HaOref Discord](https://github.com/Avir4m/PikudHaoref-Discord) | Avir4m | Discord bot posting alert notifications to channels | ![Stars](https://img.shields.io/github/stars/Avir4m/PikudHaoref-Discord?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/Avir4m/PikudHaoref-Discord) |

### Telegram

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Multi City Alert Monitor](https://github.com/rinad12/multi-city-alert-monitor) | rinad12 | Monitors multiple cities and sends Telegram alerts | ![Stars](https://img.shields.io/github/stars/rinad12/multi-city-alert-monitor?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/rinad12/multi-city-alert-monitor) |
| [Red Alert Telegram Bot](https://github.com/danielrosehill/Red-Alert-Telegram-Bot) | danielrosehill | On-demand situational intelligence bot with dual-model AI sitrep generation via OpenRouter | ![Stars](https://img.shields.io/github/stars/danielrosehill/Red-Alert-Telegram-Bot?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Red-Alert-Telegram-Bot) |

### WhatsApp

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Pikud HaOref WhatsApp Bot](https://github.com/lkeness/pikued-haoref-whatsapp-bot) | lkeness | WhatsApp bot forwarding Pikud HaOref alerts | ![Stars](https://img.shields.io/github/stars/lkeness/pikued-haoref-whatsapp-bot?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/lkeness/pikued-haoref-whatsapp-bot) |

## Hardware

| Project | Author | Platform | Description | Stars | Last Commit |
|---------|--------|----------|-------------|-------|-------------|
| [ESP32-C3 Red Alert](https://github.com/amir684/esp32c3-red-alert) | amir684 | ESP32 | ESP32-C3 microcontroller alert notifier with LED/buzzer | ![Stars](https://img.shields.io/github/stars/amir684/esp32c3-red-alert?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/amir684/esp32c3-red-alert) |

## Analysis & Infographics

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [HaOref Alert Analysis](https://github.com/TomerAntman/haoref-alert-analysis) | TomerAntman | Statistical analysis and visualization of historical alert data | ![Stars](https://img.shields.io/github/stars/TomerAntman/haoref-alert-analysis?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/TomerAntman/haoref-alert-analysis) |
| [Infographic Generator Pikud HaOref](https://github.com/Shalev-Aviv/Infographic-Generator-Pikud-Haoref) | Shalev-Aviv | Generates shareable infographics from Pikud HaOref data | ![Stars](https://img.shields.io/github/stars/Shalev-Aviv/Infographic-Generator-Pikud-Haoref?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/Shalev-Aviv/Infographic-Generator-Pikud-Haoref) |

## Civilian Readiness & Preparedness

Guides, SOPs, and reference material for civilian preparedness in Israel.

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Israel Civilian Readiness Guide](https://github.com/danielrosehill/Israel-Civilian-Readiness-Guide) | danielrosehill | Comprehensive civilian readiness guide for emergencies in Israel | ![Stars](https://img.shields.io/github/stars/danielrosehill/Israel-Civilian-Readiness-Guide?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Israel-Civilian-Readiness-Guide) |
| [Israel Preparedness SOPs](https://github.com/danielrosehill/Israel-Preparedness-SOPs) | danielrosehill | Standard operating procedures for household emergency preparedness | ![Stars](https://img.shields.io/github/stars/danielrosehill/Israel-Preparedness-SOPs?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Israel-Preparedness-SOPs) |
| [Pikud HaOref Guidelines 03/26](https://github.com/danielrosehill/Pikud-Haoref-Guidelines-0326) | danielrosehill | Pikud HaOref safety guidelines formatted for AI context ingestion | ![Stars](https://img.shields.io/github/stars/danielrosehill/Pikud-Haoref-Guidelines-0326?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Pikud-Haoref-Guidelines-0326) |

## Full Monitoring Stacks

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Red Alert Monitoring Stack](https://github.com/danielrosehill/Red-Alert-Monitoring-Stack) | danielrosehill | Complete microservices stack: alert proxy, geo-dashboard, Pushover notifications, Telegram intelligence bot, Snapcast TTS + MQTT smart lights | ![Stars](https://img.shields.io/github/stars/danielrosehill/Red-Alert-Monitoring-Stack?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/danielrosehill/Red-Alert-Monitoring-Stack) |

## Resource Lists

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Magen](https://github.com/thewh1teagle/Magen) | thewh1teagle | Curated resource list for civilian protection tools and services | ![Stars](https://img.shields.io/github/stars/thewh1teagle/Magen?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/thewh1teagle/Magen) |


## Other

| Project | Author | Description | Stars | Last Commit |
|---------|--------|-------------|-------|-------------|
| [Alerts](https://github.com/noam767/alerts) | noam767 | Alert notification project | ![Stars](https://img.shields.io/github/stars/noam767/alerts?style=flat) | ![Last Commit](https://img.shields.io/github/last-commit/noam767/alerts) |

---

## FAQ

**How do these alerts work?**

There is no official public API for Home Front Command alerts. Consequently, all open-source projects listed here are unofficial wrappers and integrations built around the Home Front Command's internal data streams.

**Should I rely on these for my safety?**

No. These are community projects and may experience downtime, delays, or inaccuracies. Always use the official [Home Front Command app](https://www.oref.org.il/en) and your local municipal alert system as your primary source.

---

## Contributing

We welcome contributions to this list! If you have a project you would like to add, please submit a [pull request](https://github.com/danielrosehill/Awesome-Red-Alerts/pulls) or email [opensource@danielrosehill.com](mailto:opensource@danielrosehill.com).
