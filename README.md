# 🔮 Crystal Mapper — Diablo 2: ESR Mod

> A tool to help **ESR mod** players quickly determine which monsters drop specific crystals and ores.

[![Discord](https://img.shields.io/badge/ESR%20Mod%20Discord-Join%20Us-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/tWRCZauB)

*Vibe coded with [Claude AI](https://claude.ai)* ✨

---

## 📖 About

Crystal Mapper provides a clean, browser-based UI that maps crystals and their containing ores to specific monsters, sourced directly from the mod's data files.

Select one or more crystals and the results panel will automatically sort by highest drop count.

> ⚠️ This is not perfect — just something thrown together to help folks out! 🙂

---

## 🎬 Preview

<div align="center">

https://github.com/user-attachments/assets/8e9b8ac8-6e89-4616-ab49-3b1b7e869104

</div>

---

## 🚀 How To Use

1. Download the HTML file from this repository
2. Run it on your local machine by opening it in any web browser

---

## 📂 Data Sources

### Excel Sheets
| File | Purpose |
|------|---------|
| `misc.txt` | Item data |
| `treasureclassesex.txt` | Drop data |
| `uniqueitems.txt` | Ores that contain crystals are considered unique items |
| `itemstatcost.txt` | Crystal name cross-reference |
| `monstats.txt` | Monster data |
| `levels.txt` | Level/area data |

### Strings
| File | Purpose |
|------|---------|
| `item-names.json` | Item name strings |

---

## 🛠️ Built With

- HTML / CSS / JavaScript
- Diablo 2 ESR Mod data files
- [Claude AI](https://claude.ai) — did basically all the actual coding 😅
