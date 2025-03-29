# Minecraft Towny

Plugin Configs for a Towney MC server with the boys

## Rules

1. No PVP unless consented by both players.
2. No griefing
3. All builds must be approved by town mayors. Unapproved builds can be built but must be 2000 blocks away. If not they are fair game to griefing. Any builds that violate this in the way of town expansion will be removed.
4. Glitches, bugs and unbalanced / unintentional mechanics should be reported immediately. Abusers will be banned.
   Eg.

- Player rank prices are wrong
- Item in the shop that shouldn't be there. Examples include elytras, beacons, etc.
- Money exploits
- Cheats / Hacks
- Commands other than the ones listed or `/help`

## Town Mayors

- Ace
- Euphelia
- DEtoX

## Banned Items

- Elytra

## Settings

```bash
FireGrief: Off
Mob Grief: off
Keep Inventory: Off
```

## Plugins

- Essentials
- Vault
- LuckPerms
- EconomyShopGui
- Aura Skils
- Aura Mobs
- Mythic Drops
- Mythic Mobs
- Graves
- LWC

## Teleports

TP's and Home's are disabled to help build community.

Spawn warp is enabled.
TPR (teleport random)

### Commands

```bash
# warp to town spawn
/warp spawn

# teleport to random location
# use this for job grinding
/tpr
```

## Ranks

- Peasant 🏡
  - 1 Job
- Novice 📜
  - 2 Jobs
- Adept ⚒
- Squire 🏇
- Knight 🛡
  - 3 Jobs
- Warrior ⚔
- Champion 🏆
- Elite 🌟
- Sentinel 👁
  - /repair
    - Cost: 100K
- Vanguard 🚀
- Warlord 🔥
- Baron 🎩
- Overseer 🎭
- Master 🏆
- Overlord 🏯
- Grandmaster 👑

### Commands

```bash
# see all ranks
/ranks

# rankup
/rankup
```

## Graves

Plugin to help players get their stuff back if they die.

Dying will spawn a grave, player will revive with a compass pointing to it.

Other players cannot access the grave. Graves last for 3 hours.

## Jobs

The main and only source of currency. See jobs reborn docs for more info.

Note that when you leave a job, you will lose 30 levels in that job.

Do NOT grind your jobs near the town. Use TPR command above.
When grinding try to leave the landscape as presentable as possible.
If massive holes and other leftover disasters like floating trees are found,
you will be punished.

### Commands

```bash
# see available jobs
/ jobs join

# join a new job
/jobs join <job>

# leave a job
/ jobs leave <job>
```

## Chest Shops

Allows buying and selling between players with just a chest!
Check the docs on how to setup a sign:
https://www.spigotmc.org/resources/chestshop.51856/

Eg. Place a sign on a chest like this:

```bash
# leave first line blank
    16 # amount
B 10 : S 5 # Buy 16 item for 10, sell 16 for 5
    ? # leave as ?, it will populate with what's in the chest
```

## Aura Skills

Skill system for infinite progression!

```bash
# see your skills
/skills

# see leaderboard
/skilltop

# see how your skills compare to others
/skillrank
```

## Donations

Let me know if you would like to help keep the server running!

## Upcoming Features

- More player ranks
- Mythic weapons / armor / tools gacha system
- more perks with rankups
