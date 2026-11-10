# Verbal — Bug reports and suggestions

This is the issue tracker for **Verbal**, a Minecraft mod that presses any keybind when you say its name.
It covers **every version**: Fabric 26.3 and NeoForge 1.21.1. The issue form asks which one you play.

Get it on [CurseForge](https://www.curseforge.com/minecraft/mc-mods/verbal) or
[Modrinth](https://modrinth.com/mod/verbal).

**The mod's source is private, so there is no code here.** This repository exists only so that
anyone can report a problem without joining anything.

## Reporting a bug

[Open an issue.](https://github.com/scarabx/verbal-issues/issues/new/choose) Please include:

1. **Which version you play** (Fabric 26.3 or NeoForge 1.21.1) and the exact Verbal version. It is in the
   file name, e.g. `verbal-1.0.0+26.3.jar` or `verbal-neoforge-1.0.0+1.21.1.jar`.
2. **Your loader's version:** Fabric Loader and Fabric API, or NeoForge.
3. **Other mods installed**, or at least whether you are in a modpack.
4. **What you said and what happened.** For example: "I said *open world map* and nothing happened",
   or "I said *jump* and it pressed sneak". Mention your accent or language if words are often misheard.
5. **Your operating system and microphone** (built-in, headset, USB).
6. **A crash report or log** if something went wrong — `.minecraft/crash-reports/` or `logs/latest.log`.

To show exactly what Verbal heard, set `"logTranscripts": true` in `config/verbal.json`, play until it
happens again, and attach `logs/latest.log`. Every command is then logged with what the speech
recogniser wrote down. Nothing is recorded or sent anywhere: speech recognition runs on your own computer.

## Before you report

- **The first launch downloads the speech model once** (about 161 MB), so it needs internet that one
  time. A loading circle beside the Verbal button on the title screen shows the progress.
- **Your computer may block the microphone.** Allow it for your launcher or Java, e.g. on macOS under
  System Settings › Privacy & Security › Microphone. Voice Settings shows a level meter and warns you
  when the microphone is blocked.
- **A word that keeps being misheard can be changed.** Open Voice Controls (C) and type a different word
  for that keybind, or set matching to a more relaxed strictness in Voice Settings.
- **Push to talk or always listening** is chosen in Voice Settings. With push to talk, press V once to
  start listening and again to stop.

## Suggestions

Welcome, in the same place. Say what the idea is and how you imagine it working in game.
