![FemboyDev AION 2 Brawler Field Guide](assets/femboydev-brawler-banner.svg)

# Brawler Research Notes

**FemboyDev Field Notes 001-D** · Taiwan server · Reviewed 12 November 2026

This page records the source hierarchy, patch history and data limits behind the repo. The actionable setup lives in the [Build Sheet](BRAWLER_BUILD.md), the skill system in [Skills and Specializations](SKILLS.md), and card choices in the [Arcana Guide](ARCANA.md).

## Contents

- [How to use this repo](#how-to-use-this-repo)
- [Source hierarchy](#source-hierarchy)
- [Patch timeline](#patch-timeline)
- [Data snapshots](#data-snapshots)
- [Research limitations](#research-limitations)
- [Sources](#sources)

## How to Use This Repo

| Page | Purpose |
|---|---|
| [Repository home](README.md) | Short overview and entry points. |
| [Brawler Build Sheet](BRAWLER_BUILD.md) | Copyable PvE setup, stigma picks, hotbar layout and macros. |
| [Content Builds](CONTENT_BUILDS.md) | Boss, AoE, solo-survival and PvP variants. |
| [Skills and Specializations](SKILLS.md) | Skill names, aliases, level priorities, stigma options and specialization updates. |
| [Arcana Guide](ARCANA.md) | Card types, skill pools, roll priorities and set direction. |
| [Gear and Daevanion](GEAR_DAEVANION.md) | Stats, sample equipment and class-specific Daevanion node priorities. |
| [English Resources for Taiwan](ENGLISH_RESOURCES.md) | English-language and translated Taiwan-specific sources. |
| [Community Guide Summary](PLAYER_GUIDE_SUMMARY.md) | English summary of the August 2026 player macro/build article, with patch caveats. |
| [Research Notes](RESEARCH_NOTES.md) | Source confidence, patch history and data caveats. |

## Source Hierarchy

1. **Official Taiwan patch notes** are the authority for current skill effects and cooldowns.
2. **English skill and Arcana databases** are used for readable labels, icons and card skill pools. Their names can differ from the Taiwan client.
3. **Taiwan character statistics** show what sampled high-combat-power characters used. They are observations, not proof of a best build.
4. **Player build posts and videos** provide tested starting points, especially for rotations and specialization choices. Treat them as patch-dated experiments, not universal rules.

## Patch Timeline

| Taiwan update | Brawler change relevant to this guide |
|---|---|
| **8 July 2026** | Blood Flow Block received a life-absorption effect. |
| **22 July 2026** | A Gale Strike specialization changed to move Brawler in front of the target. Other attack and charge effects were adjusted. |
| **26 August 2026** | Minimum skill-cancellation timing affected older high-speed macros. |
| **14 October 2026** | Rampage gained 20% PvE damage resistance while active. |
| **11 November 2026** | Rampage cooldown increased to 15 seconds. Its fifth specialization now grants a short Martial Arts effect. Shoulder Tackle can also trigger Martial Arts. Exploding Fist and Focused Block specializations were changed. |

### Retired Advice

- Rampage is no longer a 10-second cooldown.
- Flurry's fourth specialization no longer reduces Ascending Blow's cooldown.
- Rampage's fifth specialization no longer reduces all skill cooldowns during the state.
- The old Gale Strike frontal-damage specialization should not be treated as a damage pick.
- Very fast launch-era cancellation macros need to be retested after the August timing change.

## Data Snapshots

### Taiwan Brawler build sample

The build tracker sampled **1,080 level-50 Taiwan Brawlers** using official character data gathered **7 October 2026**. The highest-use Arcana and average skill levels are summarized in [Skills and Specializations](SKILLS.md) and the [Arcana Guide](ARCANA.md).

**Important:** this sample predates the 11 November Brawler changes. Use it to understand established investment patterns, not as a current best-in-slot ranking.

### Arcana probabilities

The Arcana database and simulator reference Korea's public probability data. Taiwan rates may differ, and some card grades or options may not be available in every region.

## Research Limitations

- This is a **PvE-first** guide. The PvP section is a set of adjustments, not a full competitive build.
- Skill and item labels are rendered in English from community databases. The Taiwan client may use different localized names; the alias crosswalk is in [Skills and Specializations](SKILLS.md).
- Player-tested specialization numbers can become outdated after balance patches. The skill page separates current official changes from older tested starting points.
- A single gear or card configuration cannot account for every boss, party composition, hit requirement or survivability need.
- The hotbar image is a suggested layout based on the screenshot supplied for this guide. Rebind it to suit your own hands and existing controls.

## Sources

### Official Taiwan updates

- [Brawler skill guide](https://tw.ncsoft.com/aion2/guidebook/view?title=%E6%8B%B3%E6%98%9F%E6%8A%80%E8%83%BD)
- [11 November 2026 update](https://tw.ncsoft.com/aion2/board/update/view?articleId=6af393e028c745263507304c)
- [14 October 2026 update](https://tw.ncsoft.com/aion2/board/update/view?articleId=6acea4e328c7452635072b90)
- [26 August 2026 update](https://tw.ncsoft.com/aion2/board/update/view?articleId=6a8dfb48fa34c1011d627473)
- [Chapter 1 update coverage, including Stigma changes](https://www.4gamers.com.tw/news/detail/80410/nc-aion2-chapter1-land-of-sand-and-frost-update-launchd)

### Databases and player testing

- [English Brawler skill database](https://aion2.dvg.cn/en/skill_list.php?category=%E6%8B%B3%E6%98%9F)
- [Taiwan Brawler build statistics](https://gamewith.ai/aion2/en/build-stats/tw/fighter)
- [Arcana database](https://gamewith.ai/aion2/en/arcana)
- [Arcana option simulator](https://gamewith.ai/aion2/en/arcana-simulator)
- [General skill system reference](https://aion2.wiki.fextralife.com/Skills)
- [Taiwan player testing: skills and specializations](https://forum.gamer.com.tw/C.php?bsn=82913&snA=5771)
- [Taiwan player testing: build and macros](https://forum.gamer.com.tw/C.php?bsn=82913&snA=5921)
- [Taiwan player discussion: PvE Arcana choices](https://forum.gamer.com.tw/C.php?bsn=82913&snA=5604)

---

*FemboyDev Field Notes 001-D · Independent player research · Not affiliated with NCSOFT.*
