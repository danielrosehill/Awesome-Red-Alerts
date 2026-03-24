# Awesome Red Alerts

A curated list of red alert (צבע אדום) civilian notification projects for Israel.

## Contents

- [Official Resources & Services](#official-resources--services)
- [Geo-Dashboards](#geo-dashboards)
- [API / Alert Feed Wrappers](#api--alert-feed-wrappers)
- [SDKs (Unofficial)](#sdks-unofficial)
- [CLI](#cli)
- [Automation Hooks](#automation-hooks)
- [Wrappers - Node.js](#wrappers---nodejs)
- [Wrappers - Python](#wrappers---python)
- [Home Assistant - Integrations](#home-assistant---integrations)
- [Home Assistant - Automations](#home-assistant---automations)
- [Homebridge](#homebridge)
- [MagicMirror](#magicmirror)
- [Notifiers](#notifiers)
- [Bots](#bots)
- [Integrations - Claude](#integrations---claude)
- [Claude Code Statusline](#claude-code-statusline)
- [Integrations - Slack](#integrations---slack)
- [Integrations - Discord](#integrations---discord)
- [Integrations - Telegram](#integrations---telegram)
- [Integrations - WhatsApp](#integrations---whatsapp)
- [Integrations - VoIP / Calls](#integrations---voip--calls)
- [Smart Home - Philips Hue](#smart-home---philips-hue)
- [ESP32](#esp32)
- [Analysis](#analysis)
- [Infographics](#infographics)
- [Civilian Readiness](#civilian-readiness)
- [Pikud HaOref Guidelines for AI Context](#pikud-haoref-guidelines-for-ai-context)
- [Resource Lists](#resource-lists)
- [Other](#other)

---

## Official Resources & Services

### Home Front Command (Pikud HaOref)

- [Alerts History](https://www.oref.org.il/eng/alerts-history) — Official alert history *(geo-restricted)*
- [Pikud HaOref Telegram](https://t.me/PikudHaOref_all) — Official Telegram channel for all alerts

### Tzofar (צופר)

- [Tzofar Website](https://www.tzevaadom.co.il/en/) — Real-time alert website
- [Tzofar Android App](https://play.google.com/store/apps/details?id=com.red.alert) — Google Play
- [Tzofar iOS App](https://apps.apple.com/il/app/tzofar-red-alert/id1480129320) — App Store
- [Tzofar Chrome Extension](https://chromewebstore.google.com/detail/%D7%A6%D7%95%D7%A4%D7%A8-%D7%A6%D7%91%D7%A2-%D7%90%D7%93%D7%95%D7%9D/hpbdhanjafnpeeobgejmdaajkiamfdpi?hl=en&pli=1) — Browser extension *(highly recommended)*
- [Tzofar WhatsApp Channel](https://www.whatsapp.com/channel/0029Va6c4jpIHphPAwLl4j0q) — WhatsApp alert channel

### Other Services

- [RocketAlert.live](https://rocketalert.live/) — Live rocket alert tracker
- [Tzevadom](https://tzevadom.com/en/) — Real-time alert website
- [ILRedAlert on X](https://x.com/ILRedAlert) — Alert feed on X (Twitter)

---

## Geo-Dashboards

- [oref-map](https://github.com/maorcc/oref-map) — Oref alert map
- [Red-Alert-Geodash](https://github.com/danielrosehill/Red-Alert-Geodash) — Red alert geographic dashboard
- [pikud-haoref-map](https://github.com/avisratmp-stack/pikud-haoref-map) — Pikud HaOref alert map
- [oref](https://github.com/jilaboon/oref) — Oref alert map
- [red-alert-map](https://github.com/aviv4339/red-alert-map) — Red alert map
- [hatraot](https://github.com/adipalko/hatraot) — Alert map
- [tilon](https://github.com/gunr1984-jonost/tilon) — Alert map
- [HA-Red-Alert-News-Dash](https://github.com/danielrosehill/HA-Red-Alert-News-Dash) — Home Assistant red alert news dashboard *(legacy)*

## API / Alert Feed Wrappers

### GraphQL

- [pikud-haoref-api-graphql](https://github.com/TuvalSimha/pikud-haoref-api-graphql) — GraphQL wrapper for the Pikud HaOref API

## SDKs (Unofficial)

- [pikud-haoref-api-go](https://github.com/5c077m4n/pikud-haoref-api-go) — Go SDK for the Pikud HaOref API

## CLI

- [waralerts](https://github.com/yprez/waralerts) — Command-line alert monitor

## Automation Hooks

- [roborock-missile-alert](https://github.com/DeDuckProject/roborock-missile-alert) — Roborock vacuum automation triggered by missile alerts

## Wrappers - Node.js

- [pikud-haoref-api](https://github.com/eladnava/pikud-haoref-api) — Node.js wrapper for the Pikud HaOref API

## Wrappers - Python

- [python-red-alert](https://github.com/Zontex/python-red-alert) — Python red alert wrapper *(legacy/unmaintained)*
- [python-pikudHaoref-api](https://github.com/reinerstone/python-pikudHaoref-api) — Python Pikud HaOref API wrapper *(legacy/unmaintained)*

## Home Assistant - Integrations

- [oref_alert](https://github.com/amitfin/oref_alert) — Home Assistant integration for Oref alerts

## Home Assistant - Automations

- [Home-Assistant-Red-Alert-Automations](https://github.com/danielrosehill/Home-Assistant-Red-Alert-Automations) — Home Assistant automation configurations for red alerts

## Homebridge

- [homebridge-pikud-haoref](https://github.com/GhostOnyx/homebridge-pikud-haoref) — Homebridge plugin for Pikud HaOref alerts

## MagicMirror

- [MMM-RedAlert](https://github.com/Moran-k/MMM-RedAlert) — MagicMirror red alert module
- [MMM-PikudHaoref](https://github.com/oriyaakov/MMM-PikudHaoref) — MagicMirror module for Pikud HaOref alerts

## Notifiers

### macOS

- [israel-homefront-macos-notifier](https://github.com/amito/israel-homefront-macos-notifier) — macOS desktop notifier for Israel homefront alerts

### MQTT

- [Red-Alert-MQTT-Desktop-Notifier-Public](https://github.com/danielrosehill/Red-Alert-MQTT-Desktop-Notifier-Public) — MQTT-based desktop notifier for red alerts
- [pikud_haoref_mqtt](https://github.com/yeheskel2016/pikud_haoref_mqtt) — MQTT integration for Pikud HaOref alerts

### Raspberry Pi

- [pikud](https://github.com/erikzaadi/pikud) — Raspberry Pi red alert notifier
- [miklat-alert](https://github.com/t0mer/miklat-alert) — Raspberry Pi visual alert indicator

### Windows

- [RedAlert](https://github.com/Amtrtm/RedAlert) — Windows desktop red alert notifications

## Bots

- [pikud-haoref-memukad-bot](https://github.com/roigreenberg/pikud-haoref-memukad-bot) — Pikud HaOref Memukad bot
- [pikud-haoref-bot](https://github.com/zitzman/pikud-haoref-bot) — Pikud HaOref bot

## Integrations - Claude

- [pikud-haoref-alerts](https://github.com/yaniv-golan/pikud-haoref-alerts) — Pikud HaOref alerts integration for Claude

## Claude Code Statusline

- [cc-redalerts-statusline](https://github.com/alonw0/cc-redalerts-statusline) — Claude Code statusline for red alerts
- [red-alert-statusline](https://github.com/lirantal/red-alert-statusline) — Red alert statusline for Claude Code

## Integrations - Slack

- [pikud-haoref-slack](https://github.com/zivhundert/pikud-haoref-slack) — Pikud HaOref Slack integration
- [oref-alerts-bot](https://github.com/anthonyangel/oref-alerts-bot) — Oref alerts Slack bot

## Integrations - Discord

- [PikudHaoref-Discord](https://github.com/Avir4m/PikudHaoref-Discord) — Pikud HaOref Discord notifications

## Integrations - Telegram

- [multi-city-alert-monitor](https://github.com/rinad12/multi-city-alert-monitor) — Multi-city alert monitor for Telegram

## Integrations - WhatsApp

- [pikued-haoref-whatsapp-bot](https://github.com/lkeness/pikued-haoref-whatsapp-bot) — Pikud HaOref WhatsApp bot

## Integrations - VoIP / Calls

- [alert_call](https://github.com/ophiri/alert_call) — VoIP/phone call alerts for red alerts

## Smart Home - Philips Hue

- [oref-lights](https://github.com/sashka-ltd/oref-lights) — Philips Hue light integration for Oref alerts

## ESP32

- [esp32c3-red-alert](https://github.com/amir684/esp32c3-red-alert) — ESP32-C3 red alert notifier

## Analysis

- [haoref-alert-analysis](https://github.com/TomerAntman/haoref-alert-analysis) — Analysis of HaOref alert data

## Infographics

- [Infographic-Generator-Pikud-Haoref](https://github.com/Shalev-Aviv/Infographic-Generator-Pikud-Haoref) — Infographic generator for Pikud HaOref data

## Civilian Readiness

- [Israel-Civilian-Readiness-Guide](https://github.com/danielrosehill/Israel-Civilian-Readiness-Guide) — Civilian readiness guide for Israel
- [Israel-Preparedness-SOPs](https://github.com/danielrosehill/Israel-Preparedness-SOPs) — Standard operating procedures for preparedness in Israel

## Pikud HaOref Guidelines for AI Context

- [Pikud-Haoref-Guidelines-0326](https://github.com/danielrosehill/Pikud-Haoref-Guidelines-0326) — Pikud HaOref guidelines formatted for AI context ingestion

## Resource Lists

- [Magen](https://github.com/thewh1teagle/Magen) — Curated resource list for civilian protection

## Other

- [alerts](https://github.com/noam767/alerts) — Alerts project
