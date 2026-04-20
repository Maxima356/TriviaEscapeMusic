# Trivia Escape Music

![Lethal Company](https://img.shields.io/badge/Lethal%20Company-Mod-orange?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.3.0-blue?style=for-the-badge)
![Thunderstore](https://img.shields.io/badge/Thunderstore-Download-success?style=for-the-badge)

A custom apparatus escape music mod for Lethal Company.

## 🎵 Features

### Dynamic Escape Sequence
When a player takes the **apparatus**, this mod triggers:
- **Initial alarm**: Map-wide warning sound (5 random alarm variations)
- **Tower Unite OST**: Reversed "Sunshine Day" and music from Tower Unite begins playing
- **Progressive intensity**: Music speeds up and alarm gets louder after 1 minute
- **Nuclear ending**: At 1:50, a nuclear alarm sounds before the explosion

### What Makes It Special
- **Immersive pressure**: The escalating music and alarm create intense dungeon escape moments
- **Tower Unite tribute**: A nostalgic reference for Tower Unite fans
- **Random variety**: 5 different alarm sounds keep each apparatus grab fresh

## 📦 Installation

### Prerequisites
- [BepInEx](https://thunderstore.io/c/lethal-company/p/BepInEx/BepInExPack/) installed
- [PizzaTowerEscapeMusic](https://thunderstore.io/c/lethal-company/p/BGN/PizzaTowerEscapeMusic/) (base mod)
- [FacilityMeltdown](https://thunderstore.io/c/lethal-company/p/loaforc/FacilityMeltdown/) (More immersion)

### Steps
1. Download the latest version from [Thunderstore](https://thunderstore.io/c/lethal-company/p/Maxima356/TriviaEscapeMusic/)
2. Extract the archive
3. Copy the contents to your BepInEx plugins folder:
   ```
   Lethal Company/BepInEx/plugins/TriviaEscapeMusic/
   ```
4. Launch the game

## 🎮 How It Works

| Timeline | Event |
|----------|-------|
| **0:00** | Player takes apparatus → Alarm sounds throughout map |
| **0:01** | Trivia/Tower OST begins playing |
| **1:00** | Music speeds up, alarm gets progressively louder |
| **1:50** | Nuclear alarm sounds |
| **2:00** | Explosion and radioactivity kill all players |

> **Note**: The special ship takeoff sound plays for any reason **except** nuclear events.

## 🛠️ Technical Details

- **Base mod**: PizzaTowerEscapeMusic by BGN
- **Audio source**: Tower Unite
- **Alarm variations**: 5 random sounds
- **File structure**:
  ```
  TriviaEscapeMusic/
  └── BepInEx/
      └── plugins/
          └── DefaultMusic
          |   └──[Contains the sounds]
          └──DefaultScripts
          |   └──[Contains Script/Settings]
          └──PizzaTowerEscapeMusic.dll
          └──Use PizzaTowerEspaceMusic.txt

  ```

## 🤝 Credits

- **Original concept**: Maxima356
- **Base mod**: [PizzaTowerEscapeMusic](https://thunderstore.io/c/lethal-company/p/BGN/PizzaTowerEscapeMusic/) by BGN
- **Music**: Tower Unite OST
- **Created for**: [LethalReloaded](https://thunderstore.io/c/lethal-company/p/ASTeam/LethalReloaded/) modpack (but works standalone!)

## ⚠️ Disclaimer

This mod is for entertainment purposes only. Audio used under fair use for parody/transformative purposes.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Maxima356/TriviaEscapeMusic/blob/main/LICENSE) file for details.

## 🔗 Links

- [Thunderstore Page](https://thunderstore.io/c/lethal-company/p/Maxima356/TriviaEscapeMusic/)
- [LethalReloaded Modpack](https://thunderstore.io/c/lethal-company/p/ASTeam/LethalReloaded/)
- [Original PizzaTowerEscapeMusic](https://thunderstore.io/c/lethal-company/p/BGN/PizzaTowerEscapeMusic/)
- [FacilityMeltdownExperimental](https://thunderstore.io/c/lethal-company/p/loaforc/FacilityMeltdownExperimental/)
- [GitHub Repository](https://github.com/Maxima356/TriviaEscapeMusic)

---

**Enjoying the mod? Give it a ⭐ on GitHub and consider checking out ModPack LethalReloaded!**

