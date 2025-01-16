# This is the main configuration file for Spigot.
# As you can see, there's tons to configure. Some options may impact gameplay, so use
# with caution, and make sure you know what each option does before configuring.
# For a reference for any variable inside this file, check out the Spigot wiki at
# http://www.spigotmc.org/wiki/spigot-configuration/
# 
# If you need help with the configuration or have any questions related to Spigot,
# join us at the IRC or drop by our forums and leave a post.
# 
# IRC: #spigot @ irc.spi.gt ( http://www.spigotmc.org/pages/irc/ )
# Forums: http://www.spigotmc.org/

config-version: 8
settings:
  late-bind: false
  bungeecord: false
  user-cache-size: 1000
  int-cache-limit: 1024
  player-shuffle: 0
  sample-count: 12
  netty-threads: 0
  timeout-time: 60
  restart-on-crash: true
  restart-script: start.command
  attribute:
    maxHealth:
      max: 2048.0
    movementSpeed:
      max: 2048.0
    attackDamage:
      max: 2048.0
  save-user-cache-on-stop-only: false
  moved-too-quickly-threshold: 100.0
  filter-creative-items: true
  moved-wrongly-threshold: 0.0625
  debug: false
  connection-throttle: -1
  moved-too-quickly-multiplier: 10.0
  global-api-cache: false
commands:
  replace-commands:
  - setblock
  - summon
  - testforblock
  log: true
  spam-exclusions:
  - /skill
  tab-complete: 0
  silent-commandblock-console: false
messages:
  restart: В§9Р�Р·РІРёРЅРёС‚Рµ СЃРµСЂРІРµСЂ РїРµСЂРµР·Р°РїСѓСЃРєР°РµС‚СЃСЏ, РїРѕР¶Р°Р№Р»СѓСЃС‚Р° РїРѕРґРѕР¶РґРёС‚Рµ.
  whitelist: В§9РўРµС…. СЂР°Р±РѕС‚С‹, РїРѕР¶Р°Р№Р»СѓСЃС‚Р° РїРѕРґРѕР¶РґРёС‚Рµ.
  unknown-command: В§7РўР°РєРѕР№ РєРѕРјР°РЅРґС‹ РЅРµС‚Сѓ В§9:/
  server-full: В§9РЎРµСЂРІРµСЂ РїРµСЂРµРїРѕР»РЅРµРЅ!
  outdated-client: В§9Р�Р·РІРµРЅРёС‚Рµ РІР°С€ РєР»РёРµРЅС‚ СѓСЃС‚Р°СЂРµР».
  outdated-server: В§9Р�Р·РІРµРЅРёС‚Рµ РЅРѕ СЃРµСЂРІРµСЂ СѓСЃС‚Р°СЂРµР»!
stats:
  disable-saving: false
  forced-stats: {}
world-settings:
  default:
    verbose: true
    arrow-despawn-rate: 1200
    view-distance: 5
    enable-zombie-pigmen-portal-spawns: true
    merge-radius:
      item: 2.5
      exp: 3.0
    item-despawn-rate: 6000
    zombie-aggressive-towards-villager: true
    hanging-tick-frequency: 100
    wither-spawn-sound-radius: 0
    chunks-per-tick: 650
    clear-tick-list: false
    hunger:
      walk-exhaustion: 0.2
      sprint-exhaustion: 0.8
      combat-exhaustion: 0.3
      regen-exhaustion: 3.0
    random-light-updates: false
    save-structure-info: true
    max-bulk-chunks: 10
    max-tnt-per-tick: 100
    max-tick-time:
      tile: 50
      entity: 50
    ticks-per:
      hopper-transfer: 8
      hopper-check: 8
    hopper-amount: 1
    entity-activation-range:
      animals: 32
      monsters: 32
      misc: 16
    mob-spawn-range: 3
    anti-xray:
      enabled: false
      engine-mode: 2
      hide-blocks:
      - 14
      - 15
      - 16
      - 21
      - 48
      - 49
      - 54
      - 56
      - 73
      - 74
      - 82
      - 129
      - 130
      replace-blocks:
      - 1
      - 5
    entity-tracking-range:
      players: 48
      animals: 48
      monsters: 48
      misc: 32
      other: 64
    nerf-spawner-mobs: false
    growth:
      cactus-modifier: 100
      cane-modifier: 100
      melon-modifier: 100
      mushroom-modifier: 100
      pumpkin-modifier: 100
      sapling-modifier: 100
      wheat-modifier: 100
      netherwart-modifier: 100
    dragon-death-sound-radius: 0
    max-entity-collisions: 8
    seed-village: 10387312
    seed-feature: 14357617
    hopper-alt-ticking: false
