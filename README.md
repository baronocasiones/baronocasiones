# Vinceric Baron G. Ocasiones

I build software for hardware that actually exists — mid-range Android phones with **no reliable signal**, ESP32s with a flaky uplink, and Django backends that outlive their deadline. Comfortable anywhere in the split between backend, mobile, and the metal underneath.

- On-device AI in production roles: detection, messaging, alerting — where a slow model means a failed alert
- Backend systems: game state machines, real-time flows, schemas that survive contact with reality
- IoT and on-chain pipelines that start at a sensor reading and end at something a person can cash in

## Featured Projects

### [Bantay](https://github.com/baronocasiones/Bantay)

Fall detection for seniors living alone, running entirely on-device. A native Kotlin pipeline watches accelerometer readings, runs a fixed 15-second countdown, and sends SMS alerts — **the alert path never waits on the network, and never waits on the model.** An optional Qwen3-0.6B language model via LiteRT-LM only proposes the wording of the alert; if it fails, a hardcoded bilingual template ships instead. Incident history lives in an app-private SQLite database, and location is optional: no fix, no delay — the message says *Location unavailable*.

Built for the AppBuildersPH Hackathon, Local AI track. Flutter + Kotlin, and the strongest argument I have for local inference: the golden hour doesn't care about your cloud budget.

### [OilTrace](https://github.com/baronocasiones/OilTrace)

Used cooking oil collection for Philippine *karinderyas*, end to end. An IoT sensor grades oil quality at the point of drop-off, a Solidity contract on Ethereum records the transaction, and consumers earn redeemable points at partner stores. Four stacks, one pipeline: **FastAPI backend (~112 tests), Solidity + Hardhat (20+ tests), React Native + Expo mobile, and PlatformIO ESP32 firmware** — with per-stack CI so a change to the firmware doesn't drag the backend suite with it.

### [coup-webbase](https://github.com/baronocasiones/coup-webbase)

The bluffing card game Coup as a web server. Python backend with a game state machine, lobby flow, and the challenge/block turns that make the game — built with strategy patterns so a move's declaration, verification, and resolution stay decoupled. Docs include state-machine diagrams for both server and frontend.

### [DormMarket](https://github.com/baronocasiones/DormMarket)

A React Native + Expo marketplace for campus students — the buy, sell, and "my roommate wants to get rid of a kettle" economy, packaged with EAS build profiles. TypeScript on the app side.

## Other Work

- [Intent-Gate](https://github.com/baronocasiones/Intent-Gate) — Python backend with smart contracts and a full pytest suite
- [3Vs](https://github.com/baronocasiones/3Vs) — Django + React full-stack application
- [opencode-config](https://github.com/baronocasiones/opencode-config) — my opinionated OpenAI/opencode setup: agents, skills, commands, and one-star proof that someone else uses it
- [express-multipage-site](https://github.com/baronocasiones/express-multipage-site) · [file-serving-node](https://github.com/baronocasiones/file-serving-node) — Node/Express fundamentals, done properly

## Tooling I Actually Use Daily

- [neovim-config](https://github.com/baronocasiones/neovim-config) — my Neovim configuration (Lua)
- [dotfiles](https://github.com/baronocasiones/dotfiles) — my Arch Linux dotfiles

## Stack

`Python` `Dart` `JavaScript / TypeScript` `Lua` `Shell` `Java` `Solidity` · Node/Express · FastAPI · pytest

---

<details>
<summary>Full project list</summary>

[**Bantay**](https://github.com/baronocasiones/Bantay) · [**OilTrace**](https://github.com/baronocasiones/OilTrace) · [**coup-webbase**](https://github.com/baronocasiones/coup-webbase) · [**DormMarket**](https://github.com/baronocasiones/DormMarket) · [**Intent-Gate**](https://github.com/baronocasiones/Intent-Gate) · [**3Vs**](https://github.com/baronocasiones/3Vs) · [**opencode-config**](https://github.com/baronocasiones/opencode-config) · [**neovim-config**](https://github.com/baronocasiones/neovim-config) · [**dotfiles**](https://github.com/baronocasiones/dotfiles) · [**express-multipage-site**](https://github.com/baronocasiones/express-multipage-site) · [**file-serving-node**](https://github.com/baronocasiones/file-serving-node)

</details>
