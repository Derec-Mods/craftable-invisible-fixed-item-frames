# CraftableInvFrames
### A fork of [Survival Invisiframes](https://github.com/techchrism/survival-invisiframes)
### Also a fork of [Craftable Invisiframes](https://modrinth.com/plugin/craftableinvframes)

This plugin enables the crafting of invisible, and fixed item frames for Players

Invisible item frames are crafted similar to tipped arrows - one invisibility potion surrounded by 8 item frames\
![Recipe Screenshot](https://i.imgur.com/RtX84ic.png)

Fixed item frames use one iron in the middle

In 1.17+, an invisible item frame can be crafted with a glow ink sac to create a glowing invisible item frame

## Permissions
Permission | Description
--- | ---
`craftableinvframes.place` | Allows the player to place an invisible item frame (enabled by default)
`craftableinvframes.craft`| Allows the player to craft an invisible item frame (enabled by default)
`craftableinvframes.cmd` | Allows the player to run commands from this plugin
`craftableinvframes.reload` | Permission to run `/iframe reload`
`craftableinvframes.forcerecheck` | Permission to run `/iframe force-recheck`
`craftableinvframes.get` | Permission to run `/iframe get`
`craftableinvframes.give` | Permission to run `/iframe give <player>`
`craftableinvframes.setitem` | Permission to run `/iframe setitem`

## Commands
Permission required for all commands: `craftableinvframes.cmd`

Command | Description | Permission
--- | --- | ---
`/iframe` or `/iframe get` | Gives the player an invisible item frame | `craftableinvframes.get`
`/iframe give` | Gives a certain player an invisible item frame | `craftableinvframes.give`
`/iframe reload` | Reloads the config | `craftableinvframes.reload`
`/iframe force-recheck` | Rechecks all loaded invisible item frames to add/remove slimes manually | `craftableinvframes.forcerecheck`
`/iframe setitem` | Sets the recipe center item to the held item | `craftableinvframes.setitem`

## Config
```yaml
# Whether or not to enable invisible item frames glowing when there's no item in them
# This will also make them visible when there's no item in them
item-frames-glow: true

itemname-invframe: "Invisible Item Frame"
itemname-glow-invframe: "Glow Invisible Item Frame"

messages:
  no-access: "§cSorry, you don't have permission to run this command"
  not-player: "§cSorry, you must be a player to use this command!"
  player-not-found: "§cPlayer %player% is not online."
  give-success: "§aAdded an invisible item frame to your inventory"
  reload-success: "§aReloaded!"
  recheck-success: "§aRechecked invisible item frames"
  recipe-update-success: "§aRecipe item updated!"
```

## Social
<p align="center">
    <a href="https://discord.gg/UBaauaN">
        <img src="https://img.shields.io/badge/Discord-%235865F2.svg?&logo=discord&logoColor=white">
            </a>
    <a href="https://mastodon.social/@wlorigin">
        <img src="https://img.shields.io/mastodon/follow/112151761663236004">
            </a>
    <a href="https://mastodon.social/@SpiritOTHawk">
        <img src="https://img.shields.io/mastodon/follow/110688157603004224">
            </a>
    <a href="https://modrinth.com/plugin/craftableinvframes">
        <img src="https://img.shields.io/modrinth/followers/wtE6hwEA">
            </a>
</p>
