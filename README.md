<div align="center">

<img src="icon.png" width="128" alt="Farm Search icon">

# Farm Search

**Every RaysWorks farm in one searchable in-game hub, plus community farms, Litematica schematics and one-click loading.**

[![Modrinth](https://img.shields.io/badge/Modrinth-farm--search-1bd96a?logo=modrinth&logoColor=white)](https://modrinth.com/mod/farm-search)
[![Release](https://img.shields.io/github/v/release/DaPiCu/Farm-Search-?label=Release&color=blue)](https://github.com/DaPiCu/Farm-Search-/releases/latest)
![Minecraft](https://img.shields.io/badge/Minecraft-26.2-62b47a)
![Fabric](https://img.shields.io/badge/Loader-Fabric-dbd0b4)

**[⬇ Download on Modrinth](https://modrinth.com/mod/farm-search)** · **[📦 GitHub Releases](https://github.com/DaPiCu/Farm-Search-/releases)**

</div>

> **All RaysWorks farm designs and tutorial videos are made by [RaysWorks](https://www.youtube.com/@RaysWorks).**
> Farm Search is only an in-game index of his work. Full credit for every RaysWorks farm goes to him, so please support his channel!
> Custom farms belong to their respective creators, and every entry shows who made and uploaded it.

Press **H** in-game and you get a searchable library of **1,700+ items and 120+ entities**. For each one you see how to farm it, which method it uses, a link to the tutorial video, and, where a schematic exists, a button that downloads it straight into Litematica and places it at your position.

---

## The RaysWorks library

![RaysWorks items](https://cdn.modrinth.com/data/cached_images/681e0065a8a665d42a78d8b057801585431e72f0.png)

- **Live search** across item names, IDs, farm types, methods and categories
- **Filters** for *Type of Farm* (Playerless, Player Loaded, Player Interacting), *Category*, *Method* and *Schematic status*; every dropdown can be typed into to narrow it down
- **Sortable columns**: Farm · Type of Farm · Method · Category · Schematic
- **Icons are rendered from your own game**, so resource packs change them too
- **▶ Tutorial button** opens the matching RaysWorks video
- **★ Favorites** stay at the top (custom color) and **✔ Built** farms move to the bottom, dimmed (custom color and opacity)

![RaysWorks entities](https://cdn.modrinth.com/data/cached_images/247b7a03f2238ee74d449ebbeb1dc863c844da91.png)

Entities have their own tab, with spawn eggs as icons. Allays, Armadillos, Iron Golems and everything else you can farm are all there.

---

## Community farms (Custom)

![Custom farms](https://cdn.modrinth.com/data/cached_images/255e8e1c38b80b4db891a1f04cd083aa58384c84.png)

Sometimes another creator's design suits you better. Switch the toggle at the top from **RaysWorks** to **Custom** to browse farms uploaded by the community:

- Every entry shows its **creator and uploader**
- **Several farms for the same item?** They are grouped into one line with a counter on the icon; click it to expand and pick the design you like
- Same features as the RaysWorks tab: search, filters, favorites, built markers, video, download, load

---

## Schematics: Download → Load → Materials

Wherever a schematic is linked, every row has its own buttons:

| Button | What it does |
|---|---|
| **Download** | Saves the `.litematic` into `schematics/Dapicu-ADDONS/`. The first time, you choose your schematics folder (or keep Minecraft's default) |
| **Load** | Loads the schematic with Litematica and places it at your position |
| **Materials** | Opens Litematica's material list for that schematic |
| **Update** | Appears when a newer version has been uploaded |
| **CSV** | Shows the material list online, before you download anything |

![Download finished](https://cdn.modrinth.com/data/cached_images/f8027f5b18e7ea780ca88f3760d134994270437c.png)

---

## Share your own schematics

![Upload screen](https://cdn.modrinth.com/data/cached_images/b46dbd892458271015f061bce92a77ea9e8c00ca.png)

Built a farm worth sharing? There are two ways to upload it:

- the **UPLOAD+** button in the Farm Search menu
- the new **"⬆ Upload to Farm Search"** button in Litematica's **Schematic Manager**

Then choose between:

- **RaysWorks farm:** link your schematic to an existing RaysWorks farm. It is attached to every item that farm produces.
- **Custom farm:** add a new community farm. Pick the item or entity it produces (**Shift+Click** selects several, e.g. *Oak Log + Stick* for one tree farm), then fill in the farm name, type, tutorial video, category and optionally the method, original creator and a short description.

**Every upload is checked before it goes public:**
- the server only accepts real `.litematic` files
- every file is scanned with **VirusTotal**
- tutorial links must be **YouTube** links (`youtube.com` / `youtu.be`)

You get a chat message as soon as your farm is live.

---

## More features

- **Liquid-glass look**: blurred, translucent panels with a modern, clean design
- **Fast startup**: the farm list is cached locally and refreshed in the background
- **Languages**: English (default) and German, switchable in the settings
- **In-game settings (⚙)**: colors, opacity, language, schematics folder, refresh interval
- **Rebindable hotkey**: default **H**, under *Options → Controls → Farm Search*
- **Client-side only**: works on any server, including vanilla ones

---

## Requirements

| | Version |
|---|---|
| Minecraft | 26.2 |
| Fabric Loader | 0.19.5+ |
| [Fabric API](https://modrinth.com/mod/fabric-api) | required |
| [Litematica](https://modrinth.com/mod/litematica) | required (0.28.4+) |
| [MaLiLib](https://modrinth.com/mod/malilib) | required (0.29.3+) |
| Java | 25 |

---

## Installation

1. Install [Fabric Loader](https://fabricmc.net/use/) for Minecraft 26.2
2. Put **Fabric API**, **Litematica**, **MaLiLib** and the **Farm Search** `.jar` into your `mods` folder
   (get the jar from [Modrinth](https://modrinth.com/mod/farm-search) or from the [Releases](https://github.com/DaPiCu/Farm-Search-/releases))
3. Start the game and press **H**

---

## Bugs & ideas

Found a bug or have an idea? Open an [issue](https://github.com/DaPiCu/Farm-Search-/issues). Please include your Minecraft and mod versions and, for crashes, your `latest.log`.

---

## Privacy

Farm Search reads the public farm list and downloads schematics only when you click a button. When **you upload** a schematic, the file, its Litematica metadata, its material list and your **Minecraft username** (shown as the uploader) are sent to the Farm Search server. Nothing else is collected.

---

## Credits

- **RaysWorks farm designs & tutorials:** [RaysWorks](https://www.youtube.com/@RaysWorks). Subscribe and support him!
- **Custom farms:** their respective creators and uploaders, credited on every entry
- **Litematica & MaLiLib:** masa
- **Farm Search:** DaPiCu

---

<div align="center">

© DaPiCu · All Rights Reserved · Not affiliated with RaysWorks, Mojang or Microsoft

</div>
