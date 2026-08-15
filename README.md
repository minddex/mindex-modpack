# MindEX Minecraft Modpack

This repository stores the official client modpack for **MindEX Minecraft**.

## Server details

- **Server:** `mc.savioserra.dev:25565`
- **Game version:** `26.2`
- **Loader:** `NeoForge`

## Why a modpack?

This server now uses NeoForge with mod support, so vanilla Minecraft is not enough. All players must use the same modpack to avoid mismatched client/server versions.

## Quick start (recommended)

### 1) Install dependencies

- Install **Minecraft Java**
- Install **Prism Launcher** (recommended) or use **CurseForge App**
- Use **NeoForge** for this pack

### 2) Import the pack

#### Prism Launcher

1. Open **Prism Launcher**.
2. Create a new instance from **Import**.
3. Choose **Import from URL**.
4. Paste the latest pack URL from the release page.
5. Launch with profile named for this pack.

#### CurseForge App

1. Open **Minecraft > Modpacks**.
2. Import the pack from the shared URL.
3. Launch the imported pack profile.

### 3) Join server

- Address: `mc.savioserra.dev:25565`
- Allowlist required

## Pack releases

Download the latest pack from the **Releases** page and keep your client on the latest announced version.

### Versioning

- Start at **v1**.
- Increase version whenever client-visible mod/config compatibility changes.
- Players should always use the latest version for a stable join experience.

## Troubleshooting

If you cannot connect:

- Confirm you launched the **MindEX pack profile**.
- Confirm it is **Minecraft 26.2 + NeoForge**.
- Confirm you imported the latest pack version.
- Check client logs for mod/version mismatch errors.
- Confirm allowlist access.

## Rollback and updates

If there is a bad pack update:

- Use the previously announced pack version URL.
- Re-import the older version.

The official announcement messages and step-by-step player process are also documented in the server-side operational docs:

- `/etc/minecraft/CLIENT_MODPACK_SETUP.md`
- `/etc/minecraft/MODPACK_PLAYBOOK.md`
- `/etc/minecraft/MODPACK_MESSAGES.md`

## Notes

- This repo is intended for distributing the official modpack artifact(s).
- Keep server-side/world-impacting mod changes aligned with this pack version.
