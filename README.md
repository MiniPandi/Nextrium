# Nextrium Plugin Configuration Guide

Welcome to Nextrium! This is the config file for the Nextrium plugin! Here you can configure the features and settings of the plugin.

## General Instructions
- You can use hex colors like this: if the hex is `#ffffff`, you make it like this: `&x&f&f&f&f&f&f`
- It works like this: the `#` is replaced by an `x` and you always have to add the `&` or what you have set in the config.
- By default, it is `&`, then you just make `&` and then the hex, and then you get something like this: `&x&f&f&f&f&f&f`
- Please note that hex colors are only supported from version 1.16 of Minecraft and above.
- You will find more info about each setting above the setting.
- Good luck and have fun with Nextrium! :D

## Configuration Sections

### Messages
- **messages.enableMessage**: Message displayed when the plugin is enabled.
  - Default: `&x&a&a&f&f&f&fNextrium is now enabled!`
  
- **messages.disableMessage**: Message displayed when the plugin is disabled.
  - Default: `&x&6&f&a&b&c&fNextrium is now disabled!`
  
- **messages.reloadMessage**: Message displayed when the plugin is reloaded.
  - Default: `&x&a&a&f&f&f&fNextrium is now reloaded!`
  
- **messages.prefix**: Prefix for all plugin messages.
  - Default: `&7[&x&6&f&a&b&c&fNextrium&7] &8»`
  
- **messages.colorCodeCharacter**: Character used for color codes.
  - Default: `&`
  
- **messages.noPermission**: Message displayed when a user lacks permission.
  - Default: `&cYou don't have permission to use this command!`
  
- **messages.sudoUsage**: Usage message for the sudo command.
  - Default: `&x&a&a&f&f&f&fUsage: /sudo <player> <command>`
  
- **messages.playerNotFound**: Message displayed when a player is not found.
  - Default: `&cPlayer not found!`
  
- **messages.onlyPlayers**: Message displayed when a command is player-only.
  - Default: `&cOnly players can execute this command!`
  
- **messages.rtpYouAreInCombat**: Message displayed when a player is in combat.
  - Default: `&cYou are in combat!`
  
- **messages.rtpYouAreInCooldown**: Message displayed when a player is in cooldown for RTP.
  - Default: `&cYou are in cooldown for &c%cooldown% &cseconds!`
  
- **messages.rtpDelay**: Message displayed during teleport delay.
  - Default: `&x&6&f&a&b&c&fTeleporting in &c%delay% &x&6&f&a&b&c&fseconds...`
  
- **messages.rtpSuccess**: Message displayed when teleport is successful.
  - Default: `&x&a&a&f&f&f&fTeleported successfully!`
  
- **messages.rtpFailedToFindPosition**: Message displayed when RTP fails.
  - Default: `&cFailed to find position! This might happen sometimes. If it happens again, please contact an admin!`
  
- **messages.featureDisabled**: Message displayed when a feature is disabled.
  - Default: `&cThis feature is disabled. If this is a mistake, contact an admin!`
  
- **messages.gamemodeUsage**: Usage messages for gamemode commands.
  - Default:
    ```
    &x&a&a&f&f&f&fUsage: /gamemode <gamemode>
    &x&a&a&f&f&f&fUsage: /gamemode <gamemode> <player>
    &x&6&f&a&b&c&fUsage: /gms
    &x&6&f&a&b&c&fUsage: /gmc
    &x&6&f&a&b&c&fUsage: /gma
    &x&6&f&a&b&c&fUsage: /gmsp
    ```
  
- **messages.gamemodeSwitchMessage**: Message displayed when gamemode is switched.
  - Default: `&x&6&f&a&b&c&fYou are now in %gamemode% mode!`
  
- **messages.summonUsage**: Usage messages for summon commands.
  - Default:
    ```
    &x&6&f&a&b&c&fUsage: /summon <entity>
    &x&6&f&a&b&c&fUsage: /summon <entity> <amount>
    ```
  
- **messages.summonOneMessage**: Message displayed when one entity is summoned.
  - Default: `&x&a&a&f&f&f&fSummoned an %entity%!`
  
- **messages.summonMultipleMessage**: Message displayed when multiple entities are summoned.
  - Default: `&x&a&a&f&f&f&fSummoned %amount% %entity%'s!`
  
- **messages.invalidEntityType**: Message displayed when an invalid entity type is specified.
  - Default: `&cInvalid entity type!`
  
- **messages.maxSummonPerCommand**: Message displayed when exceeding max summon limit.
  - Default: `&cYou can only summon up to %maxSummons% entities per command!`

### Permissions
- **permissions.coloredChat**: Permission for colored chat.
  - Default: `nextrium.coloredchat`
  
- **permissions.sudoCommand**: Permission for sudo command.
  - Default: `nextrium.sudo`
  
- **permissions.reloadCommand**: Permission for reload command.
  - Default: `nextrium.reloadConfig`
  
- **permissions.rtpCommand**: Permission for RTP command.
  - Default: `nextrium.rtp`
  
- **permissions.rtpCooldownTimeBypass**: Permission to bypass RTP cooldown.
  - Default: `nextrium.rtpCooldownTimeBypass`
  
- **permissions.gamemodeCommand**: Permission for gamemode command.
  - Default: `nextrium.gamemodeCommand`
  
- **permissions.gamemodeOtherCommand**: Permission for changing other players' gamemode.
  - Default: `nextrium.gamemodeOtherCommand`
  
- **permissions.summonCommand**: Permission for summon command.
  - Default: `nextrium.summonCommand`

### Features
- **features.rtp**: Enable/Disable RTP feature.
  - Default: `true`
  
- **features.coloredChat**: Enable/Disable colored chat feature.
  - Default: `true`
  
- **features.sudoCommand**: Enable/Disable sudo command feature.
  - Default: `true`
  
- **features.reloadCommand**: Enable/Disable reload command feature.
  - Default: `true`
  
- **features.gamemodeCommand**: Enable/Disable gamemode command feature.
  - Default: `true`
  
- **features.summonCommand**: Enable/Disable summon command feature.
  - Default: `true`
  
- **features.debugCommand**: Enable/Disable debug command feature.
  - Default: `false`

### Settings
- **settings.rtpCenter.x**: Center of the RTP feature on the x-axis.
  - Default: `0`
  
- **settings.rtpCenter.y**: Center of the RTP feature on the y-axis.
  - Default: `0`
  
- **settings.rtpHeight.max**: Max height of the RTP feature.
  - Default: `319`
  
- **settings.rtpHeight.min**: Min height of the RTP feature.
  - Default: `-64`
  
- **settings.minRtpRadius**: Min radius of the RTP feature.
  - Default: `100`
  
- **settings.rtpAllowByPassPermission**: Enable/Disable the RTP cooldown bypass permission.
  - Default: `true`
  
- **settings.rtpCoolDownTime**: RTP cooldown time in seconds.
  - Default: `60`
  
- **settings.rtpDelay**: Countdown for the RTP command.
  - Default: `5`
  
- **settings.rtpSpawnBlockBlacklist**: List of blocks on which the player cannot spawn.
  - Default: `["LAVA", "MAGMA_BLOCK"]`
  
- **settings.rtpDefaultWorld**: Default world for the RTP command.
  - Default: `"world"`
  
- **settings.rtpMaxRetries**: Number of retries to find a location that meets all conditions before giving an error message.
  - Default: `100`
  
- **settings.rtpSpawnOnNonSolidBlocks**: Enable/Disable spawning on non-solid blocks during RTP.
  - Default: `false`
  
- **settings.maxRtpRadius**: Max radius of the RTP feature.
  - Default: `5000`
  
- **settings.rtpCanTpInCombat**: Enable/Disable teleporting in combat.
  - Default: `false`
  
- **settings.rtpWorlds**: List of worlds where the RTP command can be used.
  - Default:
    ```
    world: Overworld
    world_nether: Nether
    world_the_end: The End
    ```
  
- **settings.maxSummons**: Max entities you can summon using the custom summon command at once.
  - Default: `100`
