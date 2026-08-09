<a href="https://www.rawtoh.io/"><img src="../logo.svg" alt="Rawtoh" width="120"></a>

**[Rawtoh](https://www.rawtoh.io/)** is the collaborative control room for live streams. Connect your stack, script your
automations, and hand your crew a shared board they can operate from any device.

## One stream. Every hand on deck.

While you stream, your mods co-pilot from a shared **Board** — switching OBS scenes, triggering alerts, launching
giveaways from their phone, tablet or laptop. Everyone sees the same live state, and everyone acts within the role you
gave them.

## How it works

Rawtoh sits between your services. When something happens on one of them — a new subscriber on Twitch, a scene change in
OBS, a mod tapping a button on the Board — Rawtoh picks it up and runs the automation you defined. Automations are
TypeScript, they run server-side, and they keep working even when you are offline.

```
Twitch, OBS, Board, …  ──→  Rawtoh  ──→  Your automations (TypeScript)  ──→  Actions, across every connected service
```

## Modules

Modules are the connectors that bridge external services to the platform:

| Module                                               | What it covers                                                                                 |
| ---------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| [Twitch](https://github.com/rawtoh-io/module-twitch) | Chat, subs, raids, bits, channel points, polls, predictions — 41 events and 50 actions          |
| [OBS](https://github.com/rawtoh-io/module-obs)       | Scenes, sources, audio, streaming, recording, filters, transitions — 54 events and 127 actions  |
| [Board](https://github.com/rawtoh-io/module-board)   | The shared control panel your crew operates — custom buttons, live state, role-based access     |

Modules are **open source** — self-host them, customize them, or
[build your own](https://www.rawtoh.io/docs/modules/create-your-own).

## Get started

- **[rawtoh.io](https://www.rawtoh.io/)** — spin up your board and invite your mods, free to start
- **[Documentation](https://www.rawtoh.io/docs/getting-started)** — core concepts, scripting, storage, modules
- **[Discord](https://discord.gg/u7hywMkBah)** — ask questions and share what you built
