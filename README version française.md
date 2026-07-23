# Discord Quests Database

🇫🇷 **Français** | 🇬🇧 [English](README.md)

Une base de données collaborative recensant les noms d'exécutables, les structures de dossiers et les chemins d'installation les plus couramment utilisés par les **Discord Desktop Quests**.

---

## 📖 À propos

Les Discord Quests sont des campagnes promotionnelles permettant d'obtenir des récompenses en réalisant certaines actions, comme lancer un jeu.

Ce dépôt documente les noms d'exécutables et les structures de dossiers les plus fréquemment utilisés par les Discord Desktop Quests pour détecter un jeu en cours d'exécution. Il présente également une méthode légère qui a historiquement permis de compléter les quêtes se contentant de vérifier la présence d'un exécutable, sans avoir à télécharger ou installer le jeu complet.

> ⚠️ Discord peut modifier le fonctionnement de ses Quests à tout moment. Les méthodes de détection évoluent régulièrement et certaines quêtes récentes utilisent des mécanismes de vérification supplémentaires.

---

# 📚 Tutoriel

Pour les quêtes qui reposent uniquement sur la détection d'un exécutable, la procédure est simple.

## 1. Choisir un exécutable

Prenez n'importe quel exécutable léger que vous pouvez laisser tourner en arrière-plan.

Quelques exemples :

- Everything Installer (Voidtools)
- Notepad++
- Toute autre application légère

> 💡 **Personnellement, j'utilise `cmd.exe` (l'Invite de commandes Windows), car il est léger, déjà inclus avec Windows et ne nécessite l'installation d'aucun logiciel supplémentaire.**

---

## 2. Renommer l'exécutable

Renommez-le avec le nom attendu par la quête Discord.

Exemple :

```text
FortniteClient-Win64-Shipping.exe
```

---

## 3. Recréer la structure de dossiers

Placez l'exécutable renommé dans la structure de dossiers attendue par la quête.

Exemple :

```text
Win64/
└── FortniteClient-Win64-Shipping.exe
```

Autre exemple :

```text
Fallout4/
└── Fallout4.exe
```

---

## 4. Lancer l'exécutable

Exécutez le programme renommé et laissez-le fonctionner en arrière-plan.

# ⚠️ IMPORTANT

Si l'exécutable n'est pas détecté, essayez de **retirer l'extension `.exe`** de son nom.

**Exemple :**
- ❌ `FortniteClient-Win64-Shipping.exe`
- ✅ `FortniteClient-Win64-Shipping`

➡️ Modifiez **uniquement le nom du fichier**, ne touchez pas au reste du chemin (`Fortnite\Win64\`).

---

## 5. Accepter la quête Discord

Ouvrez Discord puis acceptez la **Desktop Quest** correspondante.

---

## 6. Compléter la quête

Si la quête repose uniquement sur la détection d'un exécutable, Discord devrait détecter automatiquement le programme en cours d'exécution.

> **ℹ️ Remarque**
>
> Certaines quêtes plus récentes, notamment celles liées à Steam, vérifient également que le jeu est réellement installé.
>
> Dans ce cas, renommer un exécutable ne suffit plus.

---

# 🎮 Quêtes Steam

Certaines Discord Quests récentes effectuent des vérifications supplémentaires concernant l'installation du jeu via Steam.

Exemples connus :

- Marathon
- John Carpenter's Toxic Commando

Ces quêtes peuvent nécessiter que le dossier d'installation Steam du jeu existe en plus de l'exécutable attendu.

---

# 📂 Base de données des jeux

Les chemins ci-dessous correspondent aux noms d'exécutables et aux structures de dossiers **les plus couramment utilisés par les Discord Quests**.

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

# 🤝 Contribuer

Vous avez découvert une nouvelle Discord Quest ?

Vous avez trouvé un nouveau nom d'exécutable, une structure de dossiers différente, un changement de chemin ou une particularité liée à un launcher ?

Les contributions sont les bienvenues !

N'hésitez pas à ouvrir une **Issue** ou à proposer une **Pull Request** afin d'aider à maintenir cette base de données à jour.

---

# ❤️ Crédits

Ce projet est basé sur des informations recueillies auprès de :

- La communauté Discord
- Des utilisateurs de Reddit
- Des contributeurs de la communauté
- Des tests personnels

Un immense merci à toutes les personnes qui ont partagé leurs découvertes au fil du temps. Chaque contribution permet de rendre cette base de données plus complète et plus fiable.

---

# ⚠️ Avertissement

Ce dépôt est fourni à des fins **de documentation et d'information**.

Les informations présentées sont issues d'observations de la communauté et peuvent devenir obsolètes à mesure que Discord fait évoluer ses méthodes de détection.

Ce projet n'est **ni affilié, ni approuvé par Discord**.
