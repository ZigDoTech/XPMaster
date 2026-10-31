# XPMaster

A free leveling guide addon for WoW: Forever. It shows the next quest step, points an arrow at where to go, and follows your quest log, so it picks up wherever your character already is.

This is a test build shared with friends and guildmates. Please don't repost it to addon sites.

## Install with WowUp

1. Update WowUp to 2.24.1 or newer, the first version that knows about WoW: Forever, then pick your Forever install at the top.
2. Open **Get Addons**, then **Install from URL**.
3. Paste `https://github.com/ZigDoTech/XPMaster` and install.

WowUp checks this page for updates like any other addon.

## Install by hand

Download the newest zip from [Releases](https://github.com/ZigDoTech/XPMaster/releases) and unzip it into the game's `Interface/AddOns` folder, so the path ends in `Interface/AddOns/XPMaster/XPMaster.toc`.

## Using it

Type `/xpm` to show or hide the guide, and `/xpm options` for settings.

## Reporting a problem

Open an [issue](https://github.com/ZigDoTech/XPMaster/issues/new/choose). It helps a lot to include:

- what `/xpm where` prints while you're standing at the spot, and the step the guide was showing;
- the debug log: type `/xpm log`, press Ctrl+A then Ctrl+C in the window, and paste it into the issue. It lists recent quests, step changes and any XPMaster errors. Type `/xpm bug <what went wrong>` right when it happens and your note lands in the log at that moment.
