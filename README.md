# Discord Quests Database

🇬🇧 **You are in the English version** | 🇫🇷 [README version française.md](https://github.com/shizeh/discord-quests-database/blob/main/README%20version%20fran%C3%A7aise.md)

A community-maintained database of executable names, folder structures, and installation paths commonly used by **Discord Desktop Quests**.

---

## 📖 About

Discord Quests are promotional campaigns that reward users for completing specific tasks, such as launching a game.

This repository documents the executable names and folder structures most commonly used by Discord Desktop Quests for game detection. It also explains a lightweight setup that has historically worked for Quests that only verify whether a specific executable is running, without requiring the full game to be downloaded or installed.

> ⚠️ Discord may change how Quests work at any time. Detection methods evolve, and newer Quests may use additional verification mechanisms beyond executable detection.

---

# 📚 Tutorial

For Quests that only rely on executable detection, the process is straightforward.

## 1. Choose an executable

Pick any lightweight executable that you don't mind leaving running in the background.

Examples include:

- Everything Installer (Voidtools)
- Notepad++
- Any lightweight application

  > 💡 **Personally, I use `cmd.exe` (Windows Command Prompt), since it's lightweight and already included with Windows, so there's no need to install any additional software.**

---

## 2. Rename the executable

Rename it to the executable name expected by the Discord Quest.

Example:

```text
FortniteClient-Win64-Shipping.exe
```

---

## 3. Recreate the expected folder structure

Place the renamed executable inside the folder structure expected by the Quest.

Example:

```text
Win64/
└── FortniteClient-Win64-Shipping.exe
```

Another example:

```text
Fallout4/
└── Fallout4.exe
```

---

## 4. Launch the executable

Start the renamed executable and leave it running in the background.

# ⚠️ IMPORTANT

If the executable is not detected, try **removing the `.exe` extension** from its name.

**Example:**
- ❌ `FortniteClient-Win64-Shipping.exe`
- ✅ `FortniteClient-Win64-Shipping`

➡️ Modify **only the file name**. Do not change the rest of the path (`Fortnite\Win64\`).

---

## 5. Accept the Discord Quest

Open Discord and accept the corresponding **Desktop Quest**.

---

## 6. Complete the Quest

If the Quest only checks for a running executable, Discord should detect it automatically.

> **ℹ️ Note**
>
> Some newer Discord Quests—especially Steam titles—also verify that the game is actually installed.
>
> In these cases, simply renaming an executable is **not** sufficient.

---

# 🎮 Steam-only Quests

Some recent Discord Quests perform additional installation checks through Steam.

Known examples include:

- Marathon
- John Carpenter's Toxic Commando

These Quests may require the expected Steam installation directory to exist in addition to the executable.

---

# 📂 Game Database

The paths below are the executable names and folder structures **most commonly used by Discord Quests**.

| Game | Executable Path |
|------|-----------------|
| 2XKO | `..\2XKO\Live\Lion\Binaries\Win64\Lion-Win64-Shipping.exe` |
| Arc Raiders | `..\Arc Raiders\PioneerGame.exe` |
| Arena Breakout Infinite | `..\Arena Breakout Infinite\ABInfinite\Binaries\Win64\UAGame.exe` |
| Arknights Endfield | `..\Arknights Endfield\EndField Game\Endfield.exe` |
| Battlefield 6 | `..\Battlefield 6\bf6.exe` |
| Blue Protocol Star Resonance | `..\Blue Protocol Star Resonance\bpsr\BPSR_STEAM.exe` |
| Comet Browser | `..\Comet\Perplexity\Comet\Application\comet.exe` |
| Delta Force | `..\Delta Force\Game\DeltaForce\Binaries\Win64\DeltaForceClient-Win64-Shipping.exe` |
| Destiny 2 | `..\Destiny 2\destiny2.exe` |
| Duet Night Abyss | `..\Duet Night Abyss\EM-Win64-Shipping.exe` |
| EA Sports FC 26 | `..\EA SPORTS FC 26\FC26.exe` |
| EMPULSE | `..\EMPULSE Demo\Orion\Binaries\Win64\OrionClient-Win64-Shipping.exe` |
| Enginefall | `..\Enginefall Demo\Coltrane\Binaries\Win64\ColtraneClient-Win64-Shipping.exe` |
| Escape The Backrooms | `..\Win64\Backrooms-Win64-Shipping.exe` |
| EVE Online | `..\Eve Online\exefile.exe` |
| Fallout 4 | `..\Fallout 4\Fallout4.exe` |
| Fallout 76 | `..\Fallout76\Fallout76.exe` |
| Fortnite | `..\Fortnite\FortniteGame\Binaries\Win64\FortniteClient-Win64-Shipping.exe` |
| Genshin Impact | `..\Genshin Impact\Genshin Impact game\GenshinImpact.exe` |
| GearUP | `..\Gearup_ball.exe` |
| GODDESS OF VICTORY: NIKKE | `..\NIKKE\NIKKE\Game\nikke.exe` |
| Grounded 2 | `..\Grounded 2\WinGRTS\Grounded2-WinGRTS-Shipping.exe` |
| Highguard | `..\Highguard\Win64\HighguardClient-Win64-Shipping.exe` |
| Honkai: Star Rail | `..\Star Rail\Games\StarRail.exe` |
| Hunt: Showdown 1896 | `..\Hunt Showdown\bin\win_x64\HuntGame.exe` |
| Marvel Rivals | `..\MarvelRivals\MarvelRivals_Launcher.exe` |
| NTE: Neverness to Everness | `..\Neverness To Everness\Client\WindowsNoEditor\HT\Binaries\Win64\HTGame.exe` |
| OldSchool RuneScape | `..\win64\osclient.exe` |
| Once Human | `..\Once Human\ONCE_HUMAN.exe` |
| Opera | `..\Opera GX\opera.exe` |
| Path of Exile 2 | `..\Grinding Gear Games\Path of Exile 2\pathofexile.exe` |
| PUBG: Battlegrounds | `..\PUBG\TslGame\Binaries\Win64` |
| Pragmata | `..\PRAGMATA SKETCHBOOK\PRAGMATA_SKETCHBOOK.exe` |
| RAID: Shadow Legends | `..\RAID Shadow Legends\Raid.exe`<br>`..\build\Raid.exe` |
| Risk of Rain 2 | `..\Risk of Rain 2\Risk of Rain 2.exe` |
| Roblox | `..\Roblox\Versions\version-xxxxxxxx\RobloxPlayerBeta.exe` |
| Rune Dice | `..\Rune Dice\Rune Dice.exe` |
| RuneScape | `..\win64\runescape.exe` |
| Shift At Midnight *(Steam Demo Required)* | `..\Shift At Midnight Demo\ShiftAtMidnight.exe` |
| skate. | `..\skate\skate.exe` |
| STALZONE | `..\bin\stalcraftw.exe` |
| Storm Lancers *(Steam Demo Required)* | `..\Storm Lancers Demo\StormLancersDemo.exe` |
| Summoners War | `..\Summoners War\common\Summoners War\SummonersWar.exe` |
| Terminull Brigade | `..\TerminullBrigade\Project Rogueteers\Rogueteers\Binaries\Win64\Rouge-Win64-Shipping.exe` |
| The Mound: Omen of Cthulhu | `..\The Mound Omen of Cthulhu\Binaries\Win64\TheMound-Win64-Shipping.exe` |
| Torchlight Infinite | `..\Torchlight_Infinite\UE_game\Binaries\Win64\Torchlight_Infinite.exe` |
| Umamusume: Pretty Derby | `..\UmamusumePrettyDerby\UmamusumePrettyDerby.exe` |
| Valorant | `..\Riot Games\VALORANT\live\ShooterGame\Binaries\Win64\VALORANT-Win64-Shipping.exe` |
| Vindictus | `..\Vindictus\Vindictus_x64` |
| Where Winds Meet | `..\wwm_standard\Engine\Binaries\Win64r\wwm.exe` |
| World of Tanks: HEAT | `..\WoT HEAT\wgcs_api.exe` |
| World of Warcraft: Midnight | `..\World of Warcraft\_retail_\Wow.exe` |
| Wuthering Waves | `..\Wuthering Waves\Wuthering Waves Game\Client\Binaries\Win64\Wuthering Waves.exe` |
| Yu-Gi-Oh! Master Duel | `..\Yu-Gi-Oh! Master Duel\masterduel.exe` |
| Zenless Zone Zero | `..\ZenlessZoneZero Game\ZenlessZoneZero.exe` |

---

# 🤝 Contributing

Found a new Discord Quest?

Notice a changed executable name, folder structure, launcher requirement, or installation path?

Contributions are always welcome!

Please open an **Issue** or submit a **Pull Request** so the database can stay up to date for everyone.

---

# ❤️ Credits

This project is based on information gathered from:

- The Discord community
- Reddit users
- Community contributors
- Personal testing

A huge thank you to everyone who has shared paths, executable names, and discoveries over time. Every contribution helps keep this repository accurate and useful.

---

# ⚠️ Disclaimer

This repository is provided for **documentation and educational purposes only**.

The information collected here reflects community observations and may become outdated as Discord changes its Quest detection methods.

This project is **not affiliated with or endorsed by Discord**.
