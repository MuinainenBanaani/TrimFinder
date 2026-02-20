# ⚔️ Trim Finder

A fancy, dark-themed checklist site for Minecraft armor trim collectors. Track which smithing templates you've found, see exactly where to get them, calculate your odds, and view the duplication recipe — all in one place.

**Live site:** [muinainenbanaani.github.io/TrimFinder](https://muinainenbanaani.github.io/TrimFinder)

---

## ✨ Features

- ✅ **Checklist** — Click any trim card to mark it as found. Progress saves automatically in your browser.
- 📍 **Location info** — Each card shows where to find the trim, which dimension it's in, and how to obtain it (chest, mob drop, vault, suspicious gravel).
- 🎲 **Probability Calculator** — Enter how many chests/kills/vaults you've opened and see your real chance of finding the trim at least once.
- ⚒️ **Duplication Recipe** — Every card shows the full crafting recipe with real Minecraft textures.
- 🔍 **Filters** — View All, Found only, or Missing only.
- 💾 **Persistent progress** — Your collection is saved in localStorage, so it survives page refreshes and browser restarts.

---

## 🗂️ Repository Structure

```
TrimFinder/
├── index.html        ← Main site file
├── README.md         ← This file
└── images/           ← All Minecraft texture images
    ├── sentry_armor_trim_smithing_template.png
    ├── dune_armor_trim_smithing_template.png
    ├── coast_armor_trim_smithing_template.png
    ├── wild_armor_trim_smithing_template.png
    ├── ward_armor_trim_smithing_template.png
    ├── silence_armor_trim_smithing_template.png
    ├── eye_armor_trim_smithing_template.png
    ├── vex_armor_trim_smithing_template.png
    ├── tide_armor_trim_smithing_template.png
    ├── snout_armor_trim_smithing_template.png
    ├── rib_armor_trim_smithing_template.png
    ├── spire_armor_trim_smithing_template.png
    ├── bolt_armor_trim_smithing_template.png
    ├── flow_armor_trim_smithing_template.png
    ├── wayfinder_armor_trim_smithing_template.png
    ├── raiser_armor_trim_smithing_template.png
    ├── shaper_armor_trim_smithing_template.png
    ├── host_armor_trim_smithing_template.png
    ├── diamond.png
    ├── cobblestone.png
    ├── sandstone.png
    ├── mossy_cobblestone.png
    ├── cobbled_deepslate.png
    ├── end_stone.png
    ├── prismarine.png
    ├── blackstone.png
    ├── netherrack.png
    ├── purpur_block.png
    ├── copper_block.png
    ├── breeze_rod.png
    └── terracotta.png
```

---

## 🪄 All 18 Trims

| Trim | Location | Chance | Dimension | Duplicate With |
|------|----------|--------|-----------|----------------|
| Sentry | Pillager Outpost | 25% | Overworld | Cobblestone |
| Dune | Desert Pyramid | 14.3% | Overworld | Sandstone |
| Coast | Shipwreck | 16.7% | Overworld | Cobblestone |
| Wild | Jungle Temple | 33.3% | Overworld | Mossy Cobblestone |
| Ward | Ancient City | 5% | Overworld | Cobbled Deepslate |
| Silence | Ancient City | 1.2% | Overworld | Cobbled Deepslate |
| Eye | Stronghold | 10% | Overworld | End Stone |
| Vex | Woodland Mansion | 50% | Overworld | Cobblestone |
| Tide | Ocean Monument (Elder Guardian) | 20% | Overworld | Prismarine |
| Snout | Bastion Remnant | 8.3% | Nether | Blackstone |
| Rib | Nether Fortress | 6.7% | Nether | Netherrack |
| Spire | End City | 6.7% | The End | Purpur Block |
| Bolt | Trial Chamber (Vault) | 6.3% | Overworld | Copper Block |
| Flow | Trial Chamber (Ominous Vault) | 22.5% | Overworld | Breeze Rod |
| Wayfinder | Trail Ruins (Suspicious Gravel) | 8.3% | Overworld | Terracotta |
| Raiser | Trail Ruins (Suspicious Gravel) | 8.3% | Overworld | Terracotta |
| Shaper | Trail Ruins (Suspicious Gravel) | 8.3% | Overworld | Terracotta |
| Host | Trail Ruins (Suspicious Gravel) | 8.3% | Overworld | Terracotta |

---

## 🚀 Hosting on GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Under *Branch*, select `main` and `/ (root)`
3. Click **Save**
4. Your site will be live at `https://muinainenbanaani.github.io/TrimFinder` within a minute

> 💡 Rename `trim_finder.html` to `index.html` so the URL doesn't include the filename.

---

## 🛠️ Built With

- Pure HTML, CSS & JavaScript — no frameworks, no dependencies
- Minecraft textures from the game files
- Google Fonts (Cinzel, Inter)

---

## 👤 Author

Created by [MuinainenBanaani](https://fi.namemc.com/profile/MuinainenBanaani.1)
