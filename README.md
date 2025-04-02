CaensLogSpamRemover

Description

CaensLogSpamRemover is a BepInEx plugin for Valheim that removes specific spammy log messages from the game's console. This helps reduce unnecessary clutter in the logs, improving readability and performance for server hosts and mod developers.

Features

Suppresses log spam related to PlatformUserID parsing errors.

Ensures other debug logs remain functional.

Uses Harmony patching to modify Debug.Log behavior in Valheim.

Requirements

Valheim (latest version)

BepInEx 5 (installed and configured)

Installation

Download the latest version of CaensLogSpamRemover.dll.

Place the .dll file into your BepInEx/plugins folder.

Launch Valheim and enjoy a cleaner console log!

How It Works

The mod applies a Harmony patch to Debug.Log(object message).

It intercepts log messages and checks if they contain PlatformUserID.

If the message matches, it prevents it from being logged.

All other log messages are unaffected.

Notes

This mod is lightweight and only suppresses one specific log entry.

It does not affect other logging functionalities in Valheim.

If you encounter any issues, please report them!

Credits

Developer: CaenMod Version: 1.0.0License: MIT (Feel free to modify and share!)