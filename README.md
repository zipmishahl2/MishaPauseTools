# Mpt_Mishamodhl_plugin
[![Actions Status](https://github.com/zipmishahl2/Mpt_Mishamodhl_plugin/workflows/CI/badge.svg?branch=master)](https://github.com/zipmishahl2/Mpt_Mishamodhl_plugin/actions?query=branch%3Amaster)

A plugin for all your pausing needs.

### Usage
1. Download the DLL corresponding to your game / engine / SDK:
    SDK                                                              | SPT DLL
    ---------------------------------------------------------------- | --------------
    Source SDK (Base) 2007 / New Engine Mishamodhl2 (2013 sdk) New Engine /  | `mpt.dll`
3. Place the DLL into the correct folder:
    SDK                        | Folder
    -------------------------- | -----------------------------------------
    Old Engine mods            | `Source SDK Base\bin`
    Half-Life: Source          | `hl1`
    Half-Life 2                | `hl2`
    Half-Life 2: Episode 1     | `episodic`
    Half-Life 2: Episode 2     | `ep2`
    Half-Life 2: Lost Coast    | `lostcoast`
4. Launch the game.
5. Go to `Options > Keyboard > Advanced`, check `Enable developer console`, and press OK.
6. Press the tilde key (<kbd>~</kbd>) and enter `plugin_load mpt` into the developer console.
    * You must `disconnect` first in Black Mesa.
    * Add `plugin_load mpt` to `cfg/autoexec.cfg` to load MptPauseTool automatically.
    * *Loading MptPauseTool more than once will crash the game!*
