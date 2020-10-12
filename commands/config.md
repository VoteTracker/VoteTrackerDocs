---
description: How to configure Vote Tracker for your guild
---

# Config

## Usage

| Command | Description |
| :--- | :--- |
| `vt!config help` | Display all help commands |
| `vt!config list` | List all modules that can be configured |
| `vt!config info <module>` | List the settings for this module |
| `vt!config set <module> <setting> <value>` | Set a value for a specific setting in a module |
| `vt!config reset <module> [setting]` | Reset a module or a specific setting inside a module to the default settings. |

## Commonly Used

| Command | Description |
| :--- | :--- |
| `vt!config set bot prefix .` | Change the bots prefix to `.` |
| `vt!config set votetracker log-channel #vote-logs` | Set the channel for vote logs to `#vote-logs` |
| `vt!config set votetracker voted-description %user#votes% has voted!` | Change the description part of the vote log embed |

## Current Available Settings

The latest settings can always be found through the bot. This list may not be always fully updated.

| Module | Setting | Description |
| :--- | :--- | :--- |
| `bot` | prefix | The bots prefix |
| `votetracker` | log-channel | The channel that vote logs will be sent to |
| `votetracker` | voted-title | The title of the vote log embed |
| `votetracker` | voted-description | The description of the vote log embed |

