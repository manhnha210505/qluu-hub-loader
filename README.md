# Qluu-Hub

Qluu-Hub is a key-gated loader for explicitly allowlisted Roblox Is Unbreakable places.

## Current release

The current release is `v0.1.2`. Use the matching immutable tag and artifact URL below; do not use a mutable branch such as `main`.

## Installation

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/manhnha210505/qluu-hub-loader/v0.1.2/releases/v0.1.2/entry.lua"))()
```

The `v0.1.2` tag contains the matching entry point and module artifacts.

## Authentication and key privacy

Enter your PandaAuth key only in the loader's authentication window. Do not post or share it, and do not save it in scripts, screenshots, logs, or public issue reports. Qluu-Hub does not require users to provide owner credentials or decryption secrets.

## Compatibility

- The initial adapter covers the allowlisted places in Roblox Is Unbreakable universe `2324018757`.
- v0.1.2 authentication, allowlist routing, and loader shutdown were exercised in the authorized Windows Real 3.2.2 session.
- The game adapter is currently a no-op placeholder. After successful authentication, the loader closes; this release does not provide gameplay UI or features.
- Delta on Android/iOS is **untested**; compatibility is unverified.
- Executor behavior may differ by version and platform. Do not treat local Luau tests as proof of live compatibility.

## Obfuscation and attribution

Build-time Prometheus `Weak` obfuscation is intended only to discourage casual copying. Client code can be inspected, modified, or captured at runtime; obfuscation is not encryption or a confidentiality guarantee.

Based on Prometheus by Elias Oelschner, https://github.com/prometheus-lua/Prometheus
