![FemboyDev AION 2 Brawler Field Guide](assets/femboydev-brawler-banner.svg)

# Brawler Content Builds

**FemboyDev Field Notes 001-F** · Taiwan server · PvE-first · Reviewed 12 November 2026

Use these as four saved presets or as a swap checklist. Skill names follow the [canonical English name list](SKILLS.md). For the key map and macro page numbers, see the [Brawler Build Sheet](BRAWLER_BUILD.md); for stat and board progression, see [Gear and Daevanion](GEAR_DAEVANION.md).

## Evidence Labels

| Label | Meaning |
|---|---|
| **Official** | Confirmed by a Taiwan update or guide. |
| **Taiwan sample** | Observed in high-combat-power character data gathered 7 October 2026. |
| **Player-tested** | Reported by a Taiwan player; may be patch- or gear-dependent. |
| **Suggested** | FemboyDev synthesis of the sources above. Test it against your own content. |

## Choose a Preset

| Preset | Use it when | Primary focus |
|---|---|---|
| [Boss PvE](#boss-pve) | A single target stays in melee | Frontal damage and short Martial Arts windows |
| [AoE / farming](#aoe--farming) | Enemies are grouped and die quickly | Reaching packs and using area skills without wasting movement |
| [Solo / survival](#solo--survival) | You are dying or losing uptime | Defensive Arcana, manual block and recovery |
| [PvP](#pvp) | Fighting players | Control, status stats and a separate PvP board/gear profile |

## Boss PvE

**Default profile.** Use the main setup in the [build sheet](BRAWLER_BUILD.md).

| Component | Setup |
|---|---|
| Filler | Flurry → Roundhouse → Chain Fist; optional Typhoon Flurry if it does not delay important skills |
| Buffs | Ferocity, Phantom, Pulverize |
| Burst | Cast Rampage manually; use Ascending Blow or Exploding Fist during Martial Arts |
| Arcana | Four Punishment pieces plus two flexible pieces; prioritize core skill rolls |
| Defense | Focused Block and movement remain manual |
| Positioning | Attack from the front when safe; leave for mechanics and return quickly |

**Official patch note:** Rampage's cooldown is 15 seconds. Its fifth specialization now grants a brief Martial Arts effect on cast. A hit with Shoulder Tackle can also trigger Martial Arts. The window is short, so prioritize the attack that will land in it.

## AoE / Farming

Use **Macro Preset 3** from the build sheet only while enemies are grouped and in range.

```text
Ground Slam
Typhoon Flurry
Surging Cleave
Flurry / Roundhouse filler
```

**Swap rules:**

- Use Gale Strike or Shoulder Tackle manually to reach a pack. Do not let a macro dash into a mechanic or past the group.
- Drop Typhoon Flurry or Surging Cleave from the loop if targets die before it resolves or move out of range.
- Keep Rampage for a pack that will survive long enough to benefit from it.

These are suggested macro priorities, not verified optimal frame timings. The August minimum-cancellation change makes old ultra-fast sequences unreliable.

## Solo / Survival

Switch to this when deaths, forced disengages or healer pressure reduce actual damage uptime.

| Slot | Swap toward |
|---|---|
| Arcana | Keep the best core-skill rolls; use flexible slots for Protection or other defensive effects rather than forcing a full damage set. |
| Recovery | Blood Flow Block when its recovery is more useful than the damage alternative. |
| Defense | Focused Block stays on a manual key; its active window is one second. |
| Specializations | Trade a Rage-recovery or damage option for life absorption when the encounter demands it. Check the current tooltip. |
| Macro | Boss filler only. Do not automate Focused Block, Defiance or movement. |

**Player-tested note:** Taiwan Brawler discussions recommend exchanging a Rage-recovery option for life absorption when survival is the limiting factor. The choice is encounter-dependent, not a permanent default.

## PvP

Use a separate skill, gear and Arcana preset. PvE boss stats and a frontal damage cycle are not a complete PvP build.

| Component | PvP direction | Confidence |
|---|---|---|
| Daevanion | Use the **Azphel** board for PvP-oriented stats. | **Database:** board contains PvP Attack, PvP Damage Boost, Status Effect Chance and Status Effect Resist nodes. |
| Equipment | Use PvP gear when available; balance status-effect accuracy and defense rather than copying PvE soul engraving. | **Player-tested, dated:** August 2026 guide. Recheck current season and item tooltips. |
| Arcana | Consider a Guardian / Unyielding defensive setup instead of the PvE Punishment mix. An older player template used four Guardian pieces plus two Unyielding pieces. | **Player discussion, dated:** verify current card options and rolls before spending resources. |
| Skills | Keep Defiance, Focused Block and movement skills on direct inputs. Use macros only for basic filler. | **Suggested** from control-focused play and current block timing. |
| Engagement | Enter during an opponent's cooldown gap, use control manually, then disengage if the burst fails. | **Player-tested, dated:** not a guaranteed matchup rotation. |

The older community PvP advice recommends status-effect chance, Critical Hit Resist and survival stats. Treat those as starting ideas, not current stat caps. PvP balance and equipment change by season.

**PvP source:** [Taiwan player Arcana discussion](https://forum.gamer.com.tw/C.php?bsn=82913&snA=5604) and [August 2026 macro / PvP commentary](https://news.17173.com/z/aion2/content/08282026/105153923.shtml). Both predate the current patch and should be treated as starting references.

## Preset Checklist

Before entering content, verify:

- **Content:** boss, AoE, solo or PvP profile selected.
- **Macro:** correct preset bound; no block, movement or burst skill in an unattended loop.
- **Rage:** enough to activate Rampage without wasting its uptime.
- **Martial Arts:** Ascending Blow or Exploding Fist ready when the short window begins.
- **Arcana:** set bonus and skill rolls fit the selected profile.
- **Survival:** if deaths interrupt damage, swap a flex slot or specialization before adding more damage.

## Sources

- [Official Taiwan update, 11 November 2026](https://tw.ncsoft.com/aion2/board/update/view?articleId=6af393e028c745263507304c)
- [Taiwan Brawler build statistics](https://gamewith.ai/aion2/en/build-stats/tw/fighter), gathered 7 October 2026
- [Brawler Daevanion boards](https://aion2.dvg.cn/en/daevanion_board_list.php?category=%E6%8B%B3%E6%98%9F)
- [August 2026 macro and PvP commentary](https://news.17173.com/z/aion2/content/08282026/105153923.shtml), community coverage, not an official build
- [PvE Arcana player discussion](https://forum.gamer.com.tw/C.php?bsn=82913&snA=5604)
- [Full research notes](RESEARCH_NOTES.md)
