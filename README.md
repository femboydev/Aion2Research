![FemboyDev AION 2 Brawler Field Guide](assets/femboydev-brawler-banner.svg)

# AION 2 Brawler Guide

**FemboyDev Field Notes 001** · Taiwan server · PvE-first · Reviewed 12 November 2026

An independent, English-language player guide to the Brawler: skill priorities, specialization choices, Arcana, rotations and practical in-game macro templates. It is not an official NCSOFT guide.

**Want the compact class-page layout?** Open the [Brawler Build Sheet](BRAWLER_BUILD.md).

Skill names use English-language AION 2 database translations. Some databases use different English names for the same skill; common aliases are listed where useful. The Taiwan client may display localized names.

> **Patch warning:** Taiwan received a major Brawler update on 11 November 2026. Older player builds are still useful for understanding the class, but several specialization effects and macro assumptions changed. The current-patch corrections are called out below.

**Jump to:** [Build card](#build-card) · [Skills](#skill-reference) · [Leveling](#skill-progression) · [Specializations](#specializations) · [Arcana](#arcana) · [Rotation](#pve-rotation) · [Macros](#macros-and-combat-support) · [Patch notes](#patch-history-and-outdated-advice) · [Sources](#sources-and-research-notes)

## Build Card

| | Recommended PvE starting point |
|---|---|
| **Loop** | Flurry → Roundhouse → Chain Fist; use Typhoon Flurry if it fits your setup. |
| **Burst** | Ferocity + Phantom + Pulverize → Rampage → Ascending Blow or Exploding Fist during Martial Arts. |
| **Skills** | Bring core skills toward 16, then prioritize Ascending Blow, Exploding Fist, Rampage and Chain Fist toward 20. |
| **Arcana** | Work toward four Punishment pieces; keep two flexible for strong skill rolls or survival. |
| **Manual inputs** | Rampage, burst attacks, Focused Block and movement. |

> **Current version:** Taiwan, researched through **12 November 2026**. The 11 November update changed Rampage and several specializations.

<details>
<summary>Contents</summary>

- [Class summary](#class-summary)
- [Core mechanics](#core-mechanics)
- [Skill reference and icons](#skill-reference)
- [Skill progression](#skill-progression)
- [Specializations](#specializations)
- [Arcana](#arcana)
- [PvE rotation](#pve-rotation)
- [Macros and Combat Support](#macros-and-combat-support)
- [PvP notes](#pvp-notes)
- [Patch history](#patch-history-and-outdated-advice)
- [Sources and research notes](#sources-and-research-notes)

</details>

> **FemboyDev build note:** cute colors, serious uptime. This is a player-maintained reference, not an official guide or a claim of a universal best build.

---

## Class Summary

**Brawler** is a melee damage class whose output depends on keeping Rage flowing, timing Rampage and exploiting brief Martial Arts windows.

| What works | What can break the cycle |
|---|---|
| Sustained attacks while the boss stays in range | Forced movement, control effects or downtime can interrupt Rage and Rampage uptime. |
| Frontal damage and Rage-generating attacks | Front positioning may conflict with boss mechanics. Move when unsafe. |
| Manual blocks can reward good timing | The current Focused Block window is short, so do not automate it. |

**Positioning rule:** front when safe, dodge when necessary, then return to the boss. Do not trade a death for frontal uptime.

---

## Core Mechanics

| Mechanic | Practical rule |
|---|---|
| **Rage** | Build it with attacks; **Exploding Fist** is a key damage and recovery skill. Avoid wasting recovery near cap or letting Rage run out unnoticed. |
| **Rampage** | Activate when you can stay in melee. Since 11 November, its cooldown is **15 seconds** and the fifth specialization can trigger Martial Arts. |
| **Frontal damage** | Stay in front only when safe. Never eat a boss attack just to keep the frontal bonus. |
| **Martial Arts** | Rampage's fifth specialization and a successful Shoulder Tackle can trigger a brief window. Use **Ascending Blow** or **Exploding Fist** during it. |

> The Taiwan patch notes list Martial Arts bonuses for Ascending Blow and Exploding Fist. The window is short, so prioritize the attack that is ready and will land in time. Do not assume both fit every window.

---

## Skill Reference

English skill translations vary slightly between databases. For example, the basic attack **Flurry** is also listed as **Combo Strike**, and **Roundhouse** is also listed as **Flying Kick**. The table focuses on each skill's practical role rather than reproducing every tooltip line.

### Skill Icon Gallery

The icons below are linked from the public [AION 2 Brawler skill database](https://aion2.dvg.cn/en/skill_list.php?category=%E6%8B%B3%E6%98%9F). They are externally hosted game-reference images, not files stored in this guide. The names beneath each icon use the English database labels.

<details>
<summary>Open the full skill icon gallery</summary>

#### Core Active Skills

| Icon | Skill | Icon | Skill | Icon | Skill |
|---|---|---|---|---|---|
| ![Flurry icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/97/ICON_GT_SKILL_001.png) | Flurry | ![Roundhouse icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/5d/ICON_GT_SKILL_004.png) | Roundhouse | ![Rampage icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/61/ICON_GT_SKILL_013.png) | Rampage |
| ![Ascending Blow icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/d1/ICON_GT_SKILL_016.png) | Ascending Blow | ![Exploding Fist icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/22/ICON_GT_SKILL_020.png) | Exploding Fist | ![Chain Fist icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/86/ICON_GT_SKILL_042.png) | Chain Fist |
| ![Gale Strike icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/a6/ICON_GT_SKILL_007.png) | Gale Strike | ![Ground Slam icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/dd/ICON_GT_SKILL_009.png) | Ground Slam | ![Spinning Kick icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/a3/ICON_GT_SKILL_017.png) | Spinning Kick |
| ![Shoulder Tackle icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/df/ICON_GT_SKILL_023.png) | Shoulder Tackle | ![Typhoon Flurry icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/dc/ICON_GT_SKILL_025.png) | Typhoon Flurry | ![Ferocity icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/0c/ICON_GT_SKILL_028.png) | Ferocity |
| ![Surging Cleave icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/9d/ICON_GT_SKILL_029.png) | Surging Cleave | ![Focused Block icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/f6/ICON_GT_SKILL_035.png) | Focused Block | ![Phantom icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/2f/ICON_GT_SKILL_033.png) | Phantom |
| ![Pulverize icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/d5/ICON_GT_SKILL_031.png) | Pulverize | ![Blood Flow Block icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/59/ICON_GT_SKILL_032.png) | Blood Flow Block | ![Defiance icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/db/ICON_CO_SKILL_002.png) | Defiance |

#### Additional Active and Utility Skills

| Icon | Skill | Icon | Skill | Icon | Skill |
|---|---|---|---|---|---|
| ![Quake icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/67/ICON_GT_SKILL_030.png) | Quake | ![Unstoppable icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/33/ICON_GT_SKILL_036.png) | Unstoppable | ![Full Force icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/ff/ICON_GT_SKILL_037.png) | Full Force |
| ![Assault Blow icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/4e/ICON_CO_SKILL_003.png) | Assault Blow | ![Discharge Energy icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/b4/ICON_GT_SKILL_039.png) | Discharge Energy | ![Time Bomb icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/01/ICON_GT_SKILL_040.png) | Time Bomb |
| ![Flash Step icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/3e/ICON_GT_SKILL_046.png) | Flash Step |  |  |  |  |

#### Passive Skill Icons

| Icon | Passive | Icon | Passive |
|---|---|---|---|
| ![Dominance icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/22/ICON_GT_SKILL_Passive_004.png) | Dominance | ![Rampage Amplification icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/b8/ICON_GT_SKILL_Passive_005.png) | Rampage Amplification |
| ![Impact Hit icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/9c/ICON_GT_SKILL_Passive_006.png) | Impact Hit | ![Frontal Breakthrough icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/62/ICON_GT_SKILL_Passive_002.png) | Frontal Breakthrough |
| ![Massive Rage icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/0d/ICON_GT_SKILL_Passive_007.png) | Massive Rage | ![Hold the Line icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/2a/ICON_GT_SKILL_Passive_001.png) | Hold the Line |
| ![Mental Conversion icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/63/ICON_GT_SKILL_Passive_003.png) | Mental Conversion | ![Impact Blow icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/d0/ICON_GT_SKILL_Passive_008.png) | Impact Blow |
| ![Revitalization Contract icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/e6/ICON_GT_SKILL_Passive_009.png) | Revitalization Contract | ![Lightweight icon](https://aion2.dvg.cn/dbsource/tw/125/images/skills/3a/ICON_GT_SKILL_Passive_010.png) | Lightweight |

Other Brawler skill icons are available from the linked database. The icon source is maintained externally, so a source-site change could break the images.

</details>

### Core Active Skills

| Skill | Common alternate name | Practical role |
|---|---|---|
| **Flurry** | Combo Strike | Basic attack and part of the repeating attack cycle. |
| **Roundhouse** | Flying Kick | Basic-cycle attack, commonly paired with Flurry. |
| **Ferocity** | Fury | Rage-related combat buff. |
| **Rampage** | — | Main combat state; its current fifth specialization can trigger Martial Arts. |
| **Exploding Fist** | Explosive Fist | Damage and Rage recovery; a major skill to time with Martial Arts. |
| **Ascending Blow** | Ascending Strike | High-priority damage skill; use during Martial Arts when possible. |
| **Chain Fist** | — | Important repeated damage skill. |
| **Phantom** | — | Offensive buff or combat skill, commonly used during the opening setup. |
| **Pulverize** | Shatter | Offensive buff or combat skill, commonly used during the opening setup. |
| **Air Rending Slash** | Surging Cleave | Damage and approach option. |
| **Gale Strike** | Whirlwind | Approach or repositioning skill; one specialization was changed to move Brawler in front of the target. |
| **Shoulder Tackle** | Iron Mountain Charge | Positioning skill that can trigger Martial Arts when it hits. |
| **Typhoon Flurry** | Typhoon Barrage | Damage and follow-up skill; specialization can trade damage for sustain. |
| **Focused Block** | — | Manually timed block. Use it against readable attacks. |
| **Blood Flow Block** | — | Recovery or sustain option. |
| **Ground Slam** | Smite Ground | Situational damage, control or utility. |
| **Spinning Kick** | Sweeping Kick | Follow-up or conditional attack; useful when its trigger is available. |
| **Flash Step** | — | Mobility option. |
| **Defiance** | — | Crowd-control escape skill. |

### Other Brawler Skills

These skills appear in the English-language Brawler database. Their usefulness depends on the build, content and current tooltip:

- **Quake**
- **Unstoppable**
- **Full Force**
- **Assault Blow**
- **Discharge Energy**
- **Time Bomb**

### Brawler Passives

| Passive | Build relevance |
|---|---|
| **Dominance** | Also translated as Intimidation. A high-priority offensive passive in the Taiwan build sample. |
| **Rampage Amplification** | Also translated as Rampage Boost. A high-priority Rampage-related passive. |
| **Impact Hit** | Commonly prioritized damage passive. |
| **Frontal Breakthrough** | Also translated as Shatter Frontline. Fits Brawler's frontal damage pattern. |
| **Massive Rage** | Also translated as Colossal Rage. Relevant when Rage capacity or sustain is a concern. |
| **Hold the Line** | Defensive or sustain-oriented passive. |
| **Mental Conversion** | Also translated as Mind Shift. Passive option in the Arcana skill pool. |
| **Impact Blow** | Passive option in the Arcana skill pool. |
| **Revitalization Contract** | Passive option in the Arcana skill pool. |
| **Lightweight** | Passive option in the Arcana skill pool. |

---

## Skill Progression

Skill levels come from several systems, including normal skill investment, Daevanion, equipment and Arcana. A high-level character's displayed skill level may include bonuses from several of these sources.

### Recommended Investment Order

| Priority | Skills | Reason |
|---|---|---|
| **Top** | **Ferocity, Rampage, Phantom, Pulverize** | Core buffs and Rage-cycle support. |
| **Top** | **Ascending Blow, Exploding Fist** | Major damage skills; Exploding Fist also supports Rage recovery. |
| **High** | **Flurry, Roundhouse, Chain Fist** | Main attack cycle and frequent damage skills. |
| **High** | **Air Rending Slash** | Damage and approach utility. |
| **Passive priority** | **Dominance, Rampage Amplification, Impact Hit, Frontal Breakthrough** | Core offensive passives. |
| **Situational** | **Focused Block, Blood Flow Block, Ground Slam, Shoulder Tackle, Typhoon Flurry, Spinning Kick** | Defense, healing, movement and conditional use. |
| **Later** | **Flash Step, Full Force, Unstoppable, Time Bomb, Assault Blow, Discharge Energy** | Invest according to content and actual use. |

### Practical Milestones

1. **Reach 16:** Flurry, Roundhouse, Exploding Fist, Ascending Blow, Chain Fist and Rampage.
2. **Push toward 20:** Ascending Blow, Exploding Fist, Rampage and Chain Fist.
3. **Then improve:** Ferocity, Phantom, Pulverize and the offensive passives.
4. Check Arcana, gear and Daevanion bonuses before spending more resources on a skill. If Rage or survival is your bottleneck, prioritize Massive Rage or defensive skills instead of more damage ranks.

An early Taiwan player build used Flurry 20, Roundhouse 20, Exploding Fist 20, Chain Fist 20, Rampage 20 and Ascending Blow 16. Treat that as an old progression example, not a reason to stop leveling Ascending Blow.

### Taiwan Build Statistics

<details>
<summary>Show the October Taiwan skill-level sample</summary>

Third-party tracker sample: **1,080 Taiwan Brawlers**, based on official character data gathered on **7 October 2026**. These are average levels among sampled characters who had learned each skill.

| Skill | Average level |
|---|---:|
| Dominance / Intimidation | 24.9 |
| Ferocity / Fury | 24.8 |
| Rampage Amplification | 24.3 |
| Phantom | 23.0 |
| Pulverize / Shatter | 22.8 |
| Impact Hit | 20.5 |
| Rampage | 20.1 |
| Ascending Blow | 19.4 |
| Roundhouse | 19.4 |
| Chain Fist | 19.3 |
| Massive Rage / Colossal Rage | 18.8 |
| Exploding Fist | 18.7 |
| Air Rending Slash | 18.3 |
| Flurry | 18.1 |
| Focused Block | 17.7 |
| Frontal Breakthrough | 16.6 |
| Blood Flow Block | 15.8 |
| Gale Strike | 14.9 |
| Ground Slam | 14.6 |
| Shoulder Tackle | 14.0 |
| Typhoon Flurry | 13.6 |
| Spinning Kick | 12.5 |

These are observed high-combat-power character averages, not a leveling order or a guaranteed best build. The sample predates the 11 November patch.

</details>

---

## Specializations

Skill Specializations change how an active skill works. Work toward the skill-level thresholds that open more choices, especially **16** and **20**. Verify each current tooltip in the Taiwan client before committing to a numbered choice.

### Current-Patch Changes

| Skill | Current change | What to do |
|---|---|---|
| **Flurry attack chain, specialization 4** | Cooldown reduction for Ascending Blow was replaced with skill critical rate. | Do not select it for the removed cooldown effect. |
| **Rampage** | Cooldown is now **15 seconds**. Specialization 5 grants a short Martial Arts window on cast. | Plan a high-value hit after casting. |
| **Exploding Fist, specialization 5** | Adds damage against targets immune to incapacitation. | Consider it for bosses with that immunity. |
| **Focused Block** | 1-second block, 10-second cooldown; successful blocks reduce cooldown. | Time it manually. |
| **Gale Strike** | An earlier patch changed one specialization to move Brawler in front of the target. | Treat it as movement utility, not the old damage effect. |

### Player-Tested Starting Choices

<details>
<summary>Show older player-tested specialization starting points</summary>

These numbered choices predate the latest patch. Treat them as starting points and confirm each effect in the Taiwan client.

| Skill | Previously recommended setup | Current-patch note |
|---|---|---|
| **Flurry** | **1 / 4 / 5** or **2 / 4 / 5** | The fourth specialization is now a skill-critical option, not an Ascending Blow cooldown reduction. |
| **Roundhouse** | **2 / 4 / 5** | Common player-tested baseline. |
| **Rampage** | **1 / 3 / 5** | Fifth specialization now supports the short Martial Arts burst window. |
| **Gale Strike** | **3 / 4** | The fourth option is useful for movement; do not assume it is a frontal damage bonus. |
| **Typhoon Flurry** | **1 / 4 / 5** or **2 / 4 / 5** | Choose between damage, Rage recovery and survival. |
| **Chain Fist** | **3 / 4 / 5** | An August update changed its fourth and fifth specialization effects. Check the current tooltip. |
| **Exploding Fist** | **1 / 2 / 5** | The fifth specialization now has a damage option against incapacitation-immune targets. |
| **Ascending Blow** | **2 / 5** | Keep it ready for Martial Arts windows. |
| **Spinning Kick** | **2 / 4** | Player-tested boss-damage choice. |
| **Shoulder Tackle** | **2 / 4** | Older player testing favored range and cooldown utility; its Martial Arts trigger also makes a hit valuable. |

For survival, earlier player testing recommended swapping a Rage-recovery choice on Flurry or Typhoon Flurry for a life-absorption option. That can be sensible in difficult content, but compare the current tooltip and your actual healing needs.

</details>

---

## Arcana

Arcana provides skill levels, stats and set bonuses. Arcana grade determines how many options a card grants:

| Grade | Options |
|---|---:|
| Common | 1 |
| Rare | 2 |
| Epic | 3 |
| Unique | 4 |

A skill option can be especially valuable when it moves a core skill across a specialization breakpoint. Once your important skills have reached their target levels, compare remaining options by their actual stats and set value.

### PvE Set Direction

A player-discussed PvE target is **four pieces of Punishment** with two flexible pieces. Use the remaining pieces for useful skill rolls, survivability or another set bonus.

Do not treat “four Punishment plus two” as a universal best-in-slot build. In the October Taiwan sample, high-use cards included both Punishment and Protection cards. Compare individual skill rolls and set bonuses instead of forcing one exact card combination.

### Arcana Type and Brawler Skill Pools

| Arcana type | Skills it can roll |
|---|---|
| **Chalice** | Broad pool of 22 Brawler skills |
| **Parchment** | Flurry, Rampage, Chain Fist, Spinning Kick, Exploding Fist, Ascending Blow |
| **Compass** | Roundhouse, Gale Strike, Typhoon Flurry, Ground Slam, Shoulder Tackle, Defiance |
| **Bell** | Mental Conversion, Frontal Breakthrough, Rampage Amplification, Impact Blow, Revitalization Contract |
| **Mirror** | Hold the Line, Dominance, Impact Hit, Massive Rage, Lightweight |
| **Scales** | Broad pool of 22 Brawler skills |

### Skill-Roll Priorities

| Arcana | Look for these Brawler rolls |
|---|---|
| **Parchment / Scales** | Ascending Blow, Exploding Fist, Rampage, Chain Fist, Flurry |
| **Bell** | Rampage Amplification, Frontal Breakthrough, Impact Blow |
| **Mirror** | Dominance, Impact Hit; Massive Rage if Rage sustain is a problem |
| **Compass** | Utility and movement skills; keep it for a useful skill roll or set bonus |
| **Chalice** | Flexible broad pool; keep a strong core-skill or passive roll |

### Common Stat Targets

| Arcana | Common offensive stat target |
|---|---|
| **Chalice** | Time |
| **Compass** | Death |
| **Bell** | Destruction |
| **Mirror** | Wisdom |
| **Scales** | Destruction and Destiny |

These are player-reported targets, not official rules. Compare the stat, skill level and set bonus together.

### Taiwan Arcana Sample

<details>
<summary>Show October card usage from the Taiwan sample</summary>

In the 7 October character sample, frequently used Arcana included:

| Card | Sample usage |
|---|---:|
| Chalice of Protection | 10% |
| Bell of Punishment | 10% |
| Scales of Punishment | 9% |
| Parchment of Protection | 8% |
| Compass of Punishment | 7% |
| Hourglass of Protection | 6% |
| Key of Protection | 6% |
| Mirror of Protection | 6% |

This is usage frequency, not a ranking of card strength. The data predates the 11 November skill changes.

</details>

---

## PvE Rotation

Use this as a priority system, not a fixed second-by-second script.

### Opening

1. Start with Rage and important cooldowns ready.
2. Use **Phantom**, **Pulverize** and **Ferocity** when appropriate.
3. Activate **Rampage** when you can stay in melee and attack.
4. Trigger Martial Arts through Rampage's fifth specialization or a successful **Shoulder Tackle** hit.
5. Use **Ascending Blow** or **Exploding Fist** during the short Martial Arts window.

### Single-Target Boss Priority

Once the opening buffs are active, use this priority while the boss is attackable:

1. **Ascending Blow** or **Exploding Fist** during Martial Arts. Use the skill that is ready and will land inside the short window.
2. **Exploding Fist** when Rage recovery is needed or when it is ready and does not displace a higher-value Martial Arts hit.
3. **Chain Fist** when available.
4. **Flurry** and **Roundhouse** as the repeating filler cycle.
5. Use **Air Rending Slash**, **Gale Strike** or **Shoulder Tackle** to approach or reposition when necessary.

Avoid spending movement skills just before a boss mechanic that will force you away. Track Rage and Rampage uptime instead of repeating the same sequence without checking the fight.

### Defense and Mechanics

- Use **Focused Block** manually against attacks you can read. Its block window is now one second.
- Follow a successful block with an available counterattack or damage skill.
- Use recovery tools before your health becomes critical.
- Leave frontal danger zones when required. Frontal damage bonuses are not worth being knocked down or killed.

### Rotation Infographic

<details>
<summary>Open the rotation diagram</summary>

```mermaid
%%{init: {"theme":"base","themeVariables":{"primaryColor":"#eee4f6","primaryTextColor":"#2b2034","primaryBorderColor":"#765395","lineColor":"#a987d5","secondaryColor":"#f7f2fb","tertiaryColor":"#f7eaf1"}}}%%
flowchart TD
    A[Before the pull: check Rage and cooldowns] --> B[Apply Ferocity, Phantom and Pulverize when useful]
    B --> C{Can you stay in melee?}
    C -- No --> D[Save Rampage and handle the mechanic]
    D --> C
    C -- Yes --> E[Activate Rampage]
    E --> F{Martial Arts active?}
    F -- Yes --> G[Use Ascending Blow or Exploding Fist]
    F -- No --> H[Build Rage and use the filler cycle]
    G --> I[Continue with Chain Fist, Flurry and Roundhouse]
    H --> I
    I --> J{Dangerous attack or forced movement?}
    J -- Yes --> K[Manual block or dodge, then return to the front]
    K --> C
    J -- No --> L[Maintain Rage and repeat the priority]
    L --> C
```

</details>

---

## Macros and Combat Support

The recommended setup is a **basic-cycle macro plus manual burst and defense**. The templates below are ordered skill priorities for the in-game system, not timed mouse scripts.

### Macro A: Basic Single-Target Cycle

Set a repeating or priority sequence like this:

```text
Flurry
Roundhouse
Chain Fist
Flurry
Roundhouse
Typhoon Flurry, if ready and appropriate
```

**Purpose:** keep basic attacks and reliable fillers moving while you handle Rage, Martial Arts and mechanics yourself.

Do not add these to the repeating filler macro:

- Rampage
- Ferocity
- Phantom
- Pulverize
- Exploding Fist
- Ascending Blow
- Focused Block
- Shoulder Tackle or other movement skills

Those skills need timing or judgment. A macro can waste Exploding Fist or Ascending Blow outside the Martial Arts window.

### Macro B: Buff Preparation

<details>
<summary>Show the optional buff sequence</summary>

If the in-game system supports a separate ordered sequence, use this as a **buff setup**, not an unattended loop:

```text
Ferocity
Phantom
Pulverize
Rampage
```

Check that each skill is ready before starting the sequence. With the current Rampage fifth specialization, casting Rampage can start a short Martial Arts window. Follow it manually with a high-value attack.

</details>

### Manual Burst Sequence

Use this after the buffs are ready:

```text
Ferocity + Phantom + Pulverize
Rampage
Ascending Blow or Exploding Fist during Martial Arts
```

If **Shoulder Tackle** is needed to reach the boss, a successful hit can trigger another short Martial Arts window. Follow it with the highest-priority available attack that can land before the effect expires.

### Macro C: Area Filler

<details>
<summary>Show the area filler sequence</summary>

For groups, a simple area-oriented priority can be:

```text
Ground Slam
Typhoon Flurry
Surging Cleave
Flurry
Roundhouse
```

Leave movement and control skills manual. If the macro spends an area skill after enemies have moved or spread out, remove that skill from the automatic sequence.

</details>

### Manual Defensive Controls

Keep these skills easy to reach:

- **Focused Block**
- **Defiance**
- **Blood Flow Block**
- **Shoulder Tackle**
- **Gale Strike**
- **Flash Step**

Focused Block's current window is only one second. Do not leave it to an unattended loop.

### Macro Setup Principles

- Prefer the built-in game system. Avoid copying early macros that depend on extremely short delays.
- Let the macro handle **Flurry, Roundhouse and simple fillers**.
- Use manual inputs for **Exploding Fist, Ascending Blow and Rampage** so you can align them with Martial Arts.
- Keep block, escape and movement skills out of the unattended cycle.
- Test the sequence on a target dummy and watch which skills actually cast. Remove any skill that delays a more important one or fires at the wrong time.
- Re-test after patches. Skill-timing changes can invalidate a previously good sequence.

A Taiwan player macro setup used **Typhoon Flurry** as part of the repeating cycle so the player could continue attacking while **Ferocity, Phantom and Pulverize** came back around. That remains a useful concept, but old high-speed versions need adjustment after the August cancellation-timing change and November Martial Arts changes.

### Macro Infographic

<details>
<summary>Open the macro diagram</summary>

```mermaid
%%{init: {"theme":"base","themeVariables":{"primaryColor":"#eee4f6","primaryTextColor":"#2b2034","primaryBorderColor":"#765395","lineColor":"#a987d5","secondaryColor":"#f7f2fb","tertiaryColor":"#f7eaf1"}}}%%
flowchart LR
    A[In-game macro or Combat Support] --> B[Flurry]
    B --> C[Roundhouse]
    C --> D[Chain Fist]
    D --> E[Optional Typhoon Flurry]
    F[Manual controls] --> G[Rampage and buffs]
    F --> H[Ascending Blow and Exploding Fist]
    F --> I[Focused Block and movement]
    G --> J[Align attacks with Martial Arts]
    H --> J
```

</details>

---

## PvP Notes

PvP requires a different setup from boss damage:

- Consider a defensive Arcana or secondary set instead of forcing the PvE damage setup.
- Keep **Defiance** and control-response skills accessible.
- Save **Gale Strike**, **Shoulder Tackle** and **Flash Step** for approach, escape or repositioning.
- Use **Focused Block** manually.
- Prioritize control, survival and timing over a stationary PvE rotation.

The PvE skill and Arcana priorities above are not intended as a finished PvP build.

---

## Patch History and Outdated Advice

<details>
<summary>Expand patch timeline and retired recommendations</summary>

| Update | Relevant Brawler change |
|---|---|
| **8 July 2026** | Blood Flow Block received a life-absorption effect. |
| **22 July 2026** | Gale Strike's fourth specialization changed to move Brawler in front of the target. Other attack and charge effects were adjusted. |
| **26 August 2026** | Minimum skill-cancellation timing was introduced, affecting very fast macro-based cancellation. |
| **14 October 2026** | Rampage gained **20% PvE damage resistance** while active. |
| **11 November 2026** | Rampage cooldown increased to 15 seconds; its fifth specialization now grants brief Martial Arts. Shoulder Tackle can trigger Martial Arts. Exploding Fist's fifth specialization and Focused Block were also changed. |

### Outdated Advice to Avoid

- Do not use the old claim that Rampage has a 10-second cooldown.
- Do not choose Flurry's fourth specialization expecting it to reduce Ascending Blow's cooldown.
- Do not expect Rampage's old fifth specialization to reduce all skill cooldowns.
- Do not assume Gale Strike's old fourth-specialization damage effect is still present.
- Do not copy an early ultra-fast macro without testing it under the newer skill-cancellation rules.

</details>

---

## Sources and Research Notes

<details>
<summary>Expand source list and data caveats</summary>

**How to weigh the sources:** official Taiwan patch notes take priority for live effects; databases provide English labels and Arcana pools; player builds provide tested starting points, not universal best-in-slot answers. Build statistics are snapshots, not recommendations.

- [Official Taiwan Brawler skill guide](https://tw.ncsoft.com/aion2/guidebook/view?title=%E6%8B%B3%E6%98%9F%E6%8A%80%E8%83%BD)
- [Official Taiwan update, 11 November 2026](https://tw.ncsoft.com/aion2/board/update/view?articleId=6af393e028c745263507304c)
- [Official Taiwan update, 14 October 2026](https://tw.ncsoft.com/aion2/board/update/view?articleId=6acea4e328c7452635072b90)
- [Official Taiwan update, 26 August 2026](https://tw.ncsoft.com/aion2/board/update/view?articleId=6a8dfb48fa34c1011d627473)
- [English Brawler skill database](https://aion2.dvg.cn/en/skill_list.php?category=%E6%8B%B3%E6%98%9F)
- [Taiwan Brawler build statistics](https://gamewith.ai/aion2/en/build-stats/tw/fighter)
- [Arcana database](https://gamewith.ai/aion2/en/arcana)
- [Arcana option simulator](https://gamewith.ai/aion2/en/arcana-simulator)
- [Player testing: Brawler skills and specializations](https://forum.gamer.com.tw/C.php?bsn=82913&snA=5771)
- [Player testing: Brawler build and macro setup](https://forum.gamer.com.tw/C.php?bsn=82913&snA=5921)
- [Player discussion: PvE Arcana choices](https://forum.gamer.com.tw/C.php?bsn=82913&snA=5604)

**Data caveat:** Taiwan build and Arcana statistics were gathered on 7 October, before the 11 November Brawler changes. Use them to understand established investment patterns, not as a post-patch ranking. Arcana probability data may also vary by region.

</details>

---

## FemboyDev Guide Notes

<details>
<summary>About this guide</summary>

- **Guide owner:** FemboyDev
- **Guide type:** independent player reference
- **Last research review:** 12 November 2026
- **Patch region:** Taiwan
- **Visual identity:** warm paper, plum, orchid and blush, chosen for a readable, friendly developer-notes style.
- **Skill icons:** externally hosted by the linked public skill database. If an icon stops loading, use the database link in the [Skill Icon Gallery](#skill-icon-gallery).
- **Diagrams:** Mermaid source is embedded in this Markdown file and is rendered natively by GitHub.

</details>
