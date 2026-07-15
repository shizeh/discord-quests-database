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

| Game | Expected Path |
|------|---------------|
| 2XKO | `2XKO\Live\Lion\Binaries\Win64\Lion-Win64-Shipping.exe` |
| Arc Raiders | `Arc Raiders\PioneerGame.exe` |
| Arena Breakout: Infinite | `Win64\UAGame.exe` |
| Arknights: Endfield | `Game\Endfield.exe` |
| Blue Protocol: Star Resonance | `Win64\bpsr.exe` |
| Comet AI Browser | `Perplexity\Comet\Application\comet.exe` |
| Delta Force | `Win64\DeltaForceClient-Win64-Shipping.exe` |
| Destiny 2 | `Destiny 2\destiny2.exe` |
| EA SPORTS FC 26 | `Deskstop\EA SPORTS FC 26\FC26.exe` |
| Fallout 4 | `Fallout4\Fallout4.exe` |
| Fallout 76 | `Fallout76\Fallout76.exe` |
| Fortnite | `Win64\FortniteClient-Win64-Shipping.exe` |
| Grounded 2 | `WinGRTS\Grounded2-WinGRTS-Shipping.exe` |
| Highguard | `Win64\HighguardClient-Win64-Shipping.exe` |
| Hunt: Showdown 1896 | `win_x64\HuntGame.exe` |
| Marvel Rivals | `Win64\Marvel-Win64-Shipping.exe` |
| Once Human | `Once Human\Once_Human.exe` |
| Opera GX | `Opera GX\opera.exe` |
| Path of Exile 2 | `Grinding Gear Games\Path of Exile 2\pathofexile.exe` |
| Pragmata | `PRAGMATA SKETCHBOOK\PRAGMATA_SKETCHBOOK.exe` |
| PUBG | `Win64\TslGame.exe` |
| RAID: Shadow Legends | `build\Raid.exe` |
| Risk of Rain 2 | `Risk of Rain 2\Risk of Rain 2.exe` |
| Roblox | `Win64\Roblox.exe` |
| Storm Lancers Demo | `Storm Lancers Demo\StormLancersDemo.exe` |
| Summoners War | `Summoners War\SummonersWar.exe` |
| Terminull Brigade | `Win64\Rouge-Win64-Shipping.exe` |
| Torchlight: Infinite | `Win64\torchlight_infinite.exe` |
| Valorant | `Win64\Valorant-Win64-Shipping.exe` |
| Vindictus | `Vindictus\Vindictus.exe` |
| Where Winds Meet | `Win64\wwm.exe` |
| World of Warcraft: Midnight | `World of Warcraft\_retail_\Wow.exe` |
| Wuthering Waves | `Win64\Wuthering Waves.exe` |

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
