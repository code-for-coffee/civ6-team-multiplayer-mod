# Civilization 6 Team Multiplayer Mod (beta)

## Installation Instructions

1. [Download the zip archive in this repository here](https://github.com/code-for-coffee/civ6-team-multiplayer-mod/raw/master/Civ6TeamMultiplayerMod.zip).
2. Locate your Civilization 6 folder. This can be found in `Steam\steamapps\common\Sid Meier's Civilization VI` on Windows. On Mac OS X, locate your `Civilization VI.app` file and _show package contents_.
3. Extract the zip archive inside of your Steam folder. It will ask to replace three files (do so).
4. Start Civ 6 as usual.
5. Create a multiplayer game.
6. Select a team (number 0 through 5) from the drop down.
7. Play as usual (with teams)!

## FAQ

> Will this break my game?

Unsure. It hasn't for our alpha testers so far.

> Is this stable?

No; this mod just enables a feature that was disabled for a future '0 DAY PATCH'. However, there was no 0 day patch - hence this mod. Each time you select a drop down for a team, a new number will be added. The team list begin at `0` and `1` and will cap out up to `5` (requiring a few clicks of the dropdown). 

> What do I get out of enabling teams?

We have noticed that you see where your teammates start on the map. This allows for building embassies with each other faster (in theory) and earlier strategizing. It provides no further benefits until later ages where it appears research agreements (when unlocked) are available faster. Let us know what you find by [Creating a new issue](https://github.com/code-for-coffee/civ6-team-multiplayer-mod/issues/new)!

> What files are modified?

```bash
├── Base
│   └── Assets
│       ├── Text
│       │   └── en_US
│       │       └── FrontEndText.xml
│       └── UI
│           └── FrontEnd
│               └── Multiplayer
│                   ├── StagingRoom.lua
│                   └── StagingRoom.xml
```
