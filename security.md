# 🚜 Data Dump for Farming Simulator Steam

<p align="center">
  <img src="https://img.shields.io/badge/Downloads-93K+-1B5E20?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Rating-4.9/5-1B5E20?style=for-the-badge&logo=star" />
  <img src="https://img.shields.io/badge/Release-2026.16-263238?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-1B5E20?style=for-the-badge&logo=steam" />
  <img src="https://img.shields.io/badge/Type-Game%20Data%20Dump-1B5E20?style=for-the-badge&logo=databricks" />
  <img src="https://img.shields.io/badge/License-Free%20Forever-1B5E20?style=for-the-badge&logo=opensourceinitiative" />
</p>

**🚜 Data Dump for Farming Simulator Steam** is the complete English-language reference for extracting, browsing, and analyzing game data from Farming Simulator on Steam. Get full access to vehicles, tools, crops, economy values, map layouts, mods, and savegame structures — all in clean, machine-readable formats. Built for modders, data analysts, and hardcore farmers who want to understand the game under the hood. **Completely free.** No account. No ads. No DRM.

<p align="center">
  <img src="https://skillicons.dev/icons?i=python" />
  <img src="https://skillicons.dev/icons?i=sqlite" />
  <img src="https://skillicons.dev/icons?i=cs" />
  <img src="https://skillicons.dev/icons?i=git" />
  <img src="https://skillicons.dev/icons?i=blender" />
  <img src="https://skillicons.dev/icons?i=windows" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=66BB6A&size=27&center=true&vCenter=true&width=920&lines=🚜+Data+Dump+for+Farming+Simulator;📊+Vehicles+%2B+Crops+%2B+Economy;🧩+Modding+%2B+Savegame+Data;💚+100%25+Free+%7C+No+Account">
</p>

<!-- Button 1 -->
<div align="center">
  <a href="https://share.google/dSh6nDD4xiNGzulkf">
    <img src="https://img.shields.io/badge/⬇️%20DOWNLOAD%20DATA%20DUMP-1B5E20?style=for-the-badge&logo=google&labelColor=263238&color=66BB6A" alt="Download Data Dump" />
  </a>
</div>

<div align="center">
  <img width="1600" height="900" alt="Data-Dump-v1 03" src="https://github.com/user-attachments/assets/104ebbc9-e4e2-42b9-93c7-a704778765cd" />

</div>

---

## 📊 What's Inside the Dump

| **Category** | **Entries** | **Format** |
|--------------|-------------|-------------|
| 🚜 **Vehicles** | 480+ | JSON / CSV |
| 🛠️ **Implements** | 620+ | JSON / CSV |
| 🌾 **Crops** | 40+ | JSON / YAML |
| 💰 **Economy** | Full price tables | CSV / SQLite |
| 🗺️ **Maps** | Every base + DLC | GeoJSON |
| 💾 **Savegame** | Structure + schema | JSON Schema |
| 🧩 **Mods** | Metadata schema | JSON |
| 📖 **Localization** | All languages | JSON |

---

## 🎁 What You Get

| **Feature** | **Description** | **Status** |
|-------------|------------------|------------|
| 📦 **Full Data Dump** | Vehicles, tools, crops | ✅ Active |
| 💰 **Economy Tables** | Prices, sell points | ✅ Active |
| 🗺️ **Map Data** | Fields, roads, POIs | ✅ Active |
| 💾 **Savegame Parser** | Read any save | ✅ Active |
| 🧩 **Mod Schema** | Standardized format | ✅ Active |
| 🔍 **Query Tools** | SQLite + Python | ✅ Active |

<table>
<tr>
<td align="center" width="33%">
  <img width="320" height="280" alt="deepseek_svg_20261009_ffff87" src="https://github.com/user-attachments/assets/ea5add83-cf4c-415d-b5f9-fb280cf7679b" />
</td>
<td align="center" width="33%">
  <img width="320" height="280" alt="deepseek_svg_20261009_345e8d" src="https://github.com/user-attachments/assets/fc27e6e0-cebf-401f-a766-279955cbc1fe" />
</td>
<td align="center" width="33%">
  <img width="320" height="280" alt="deepseek_svg_20261009_1c8f63" src="https://github.com/user-attachments/assets/75a05bb0-cd53-4722-882a-3ec229ff2884" />
</td>
</tr>
</table>

---

## 🚀 Quick Start (Under 3 Minutes)

| **Step** | **Action** | **Time** |
|----------|-----------|----------|
| 1 | Download the data dump archive | ~25 sec |
| 2 | Extract to a working folder | ~15 sec |
| 3 | Open the SQLite database | ~10 sec |
| 4 | Load the Python query tools | ~20 sec |
| 5 | Run your first query | ~30 sec |
| 6 | Export results | ~15 sec |

> **💡 Pro Tip:** Use the included `fs_query.py` script — it lets you filter any table by game version, DLC, or mod.

---

## 🚜 Vehicle Database

| **Field** | **Type** | **Example** |
|-----------|-----------|-------------|
| **Name** | string | "John Deere 8R" |
| **Brand** | string | "John Deere" |
| **Category** | enum | Tractor |
| **Price** | int | 285000 |
| **Power** | int (hp) | 410 |
| **Max Speed** | int (km/h) | 50 |
| **Fuel Capacity** | int (L) | 600 |
| **DLC** | string | "Platinum" |

---

## 💰 Economy Tables

| **Table** | **Description** | **Rows** |
|------------|-----------------|-----------|
| **Sell Points** | Locations + prices | 120 |
| **Crop Prices** | Historical averages | 42 |
| **Fuel Costs** | Per region | 15 |
| **Lease Rates** | Per vehicle class | 30 |
| **Contract Rewards** | By type and difficulty | 60 |

---

## 🗺️ Map Data Format

| **Element** | **Geometry** | **Extra Data** |
|--------------|---------------|----------------|
| **Fields** | Polygon | Ownership, crop |
| **Roads** | LineString | Type, speed |
| **Buildings** | Polygon | Function, owner |
| **POIs** | Point | Category, icon |
| **Water** | Polygon | Depth, use |

---

## 💾 Savegame Structure

| **File** | **Purpose** | **Format** |
|-----------|--------------|------------|
| **careerSavegame.xml** | Player + farm data | XML |
| **vehicles.xml** | Owned vehicles | XML |
| **fields.xml** | Field states | XML |
| **economy.xml** | Money + prices | XML |
| **placeables.xml** | Buildings | XML |

---

## 🔧 Query Tools

| **Tool** | **Language** | **Purpose** |
|-----------|---------------|--------------|
| **fs_query.py** | Python | Filter tables |
| **fs_export.py** | Python | Export to CSV / JSON |
| **fs_merge.py** | Python | Merge DLC + base |
| **fs_savegame.py** | Python | Parse saves |
| **fs_visualize.py** | Python | Plot economy data |

---

## 📋 System Requirements

| **Component** | **Minimum** | **Recommended** |
|---------------|-------------|------------------|
| **OS** | Win 10 / macOS 12 / Ubuntu 20.04 | Latest |
| **CPU** | Dual-core 2.0 GHz | Quad-core 3.0 GHz+ |
| **RAM** | 4 GB | 16 GB |
| **Storage** | 300 MB | 1 GB SSD |
| **Python** | 3.9+ | 3.11+ |
| **Download Size** | ~78 MB | ~78 MB |

---

## 🛠️ Troubleshooting

| **Problem** | **Solution** |
|--------------|---------------|
| **DB won't open** | Update SQLite |
| **Missing DLC data** | Re-run merge script |
| **Savegame fails** | Check game version |
| **Encoding issues** | Force UTF-8 |
| **Query too slow** | Add index |
| **CSV broken** | Use comma separator |
| **Mod schema mismatch** | Update schema |
| **Python import error** | Install requirements |

---

## ❓ FAQ

<details>
<summary><b>Is it free?</b></summary>
Yes — fully free, no account required.
</details>

<details>
<summary><b>Which FS versions are supported?</b></summary>
FS19, FS22, FS25, plus DLCs.
</details>

<details>
<summary><b>Can I use this for modding?</b></summary>
Yes — it's designed for modders.
</details>

<details>
<summary><b>Does it include DLC data?</b></summary>
Yes — all major DLCs are included.
</details>

<details>
<summary><b>Can I parse my savegame?</b></summary>
Yes — the parser handles all common saves.
</details>

<details>
<summary><b>Does it work on Linux?</b></summary>
Yes — the tools are Python-based.
</details>

<details>
<summary><b>Can I export to Excel?</b></summary>
Yes — via CSV.
</details>

<details>
<summary><b>Is it updated?</b></summary>
Yes — updated with each game patch.
</details>

---

## ⚠️ Terms of Use

| ✅ Allowed | ❌ Forbidden |
|------------|--------------|
| Personal use | Selling the dump |
| Modding | Claiming authorship |
| Data analysis | Redistributing as paid |
| Sharing with credits | Removing license files |

---

## 🏁 Conclusion

**Data Dump for Farming Simulator Steam** gives modders and analysts complete access to the game's inner data:

- ✅ 480+ vehicles, 620+ tools
- ✅ Full economy tables
- ✅ Every map in GeoJSON
- ✅ Savegame parser
- ✅ Python query tools
- ✅ ~78 MB download
- ✅ **Completely free**

**Understand the farm, master the data — with a full FS data dump.**

<!-- Button 2 -->
<div align="center">
  <a href="https://share.google/dSh6nDD4xiNGzulkf">
    <img src="https://img.shields.io/badge/🚀%20GET%20DATA%20DUMP-1B5E20?style=for-the-badge&logo=google&labelColor=263238&color=66BB6A" alt="Get Data Dump" />
  </a>
</div>

---

## 🔍 SEO Keywords and Tags

**Primary Keywords:** Farming Simulator Data Dump, FS Data Extraction, FS22 Data Dump, FS25 Vehicle Database, Farming Simulator Steam Data.

**Secondary Keywords:** FS Savegame Parser, FS Economy Table, FS Map Data, FS Modding Data, FS Vehicle Stats.

**Long-Tail Keywords:** Farming Simulator full data dump 2026, How to extract FS22 vehicle data, FS25 savegame parser tool, Farming Simulator economy spreadsheet, FS modding data reference, FS map GeoJSON data.

**Tags:** Farming Simulator, Data Dump, Modding, FS22, FS25, Steam, 2026.

**SEO Description:** Data Dump for Farming Simulator Steam — full vehicle, crop, economy, map, and savegame data. Python tools, SQLite, ~78 MB. Free download now!

<!-- Button 3 -->
<div align="center">
  <a href="https://share.google/dSh6nDD4xiNGzulkf">
    <img src="https://img.shields.io/badge/⬇️%20START%20FREE%20EXPORT-1B5E20?style=for-the-badge&logo=google&labelColor=263238&color=66BB6A" alt="Start Free Export" />
  </a>
</div>
