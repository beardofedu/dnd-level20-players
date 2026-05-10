# ⚔️ D&D Level 20 Players

Resources for the players of our D&D campaign.

---

## 📄 Files

### [`cheat-sheet.md`](cheat-sheet.md) — Combat & Mechanics Cheat Sheet

A comprehensive quick-reference for D&D 5e covering:

- **Turn structure** — Movement, Action, Bonus Action, Reaction, Free Interaction
- **Common Actions** — Attack, Cast a Spell, Dash, Disengage, Dodge, Help, Hide, Ready, Search, Grapple, Shove, and more
- **Attack rolls** — How to hit, critical hits, Advantage/Disadvantage
- **Death Saving Throws** — Successes, failures, nat 20 / nat 1 rules
- **Healing** — Short rest, long rest, potions
- **Spellcasting** — Spell attack rolls, save DCs, concentration, upcasting, rituals, reaction spells
- **Ability Checks & Saving Throws** — DC table and proficiency
- **Conditions** — All 14 conditions with their key effects
- **Movement & Positioning** — Difficult terrain, jumping, climbing, cover types
- **Area of Effect shapes** — Cone, Cube, Cylinder, Line, Sphere
- **Opportunity Attacks** — When they trigger and how they work
- **Inspiration** — How to earn and spend it

---

### [`inventory.html`](inventory.html) — Interactive Inventory Sheet

Open this file in any web browser — no server or internet connection required.

**Features:**
- 🧑 **Character Info** — Name, class/level, race, background, player name, STR score
- 🪙 **Currency Tracker** — Platinum, Gold, Electrum, Silver, Copper with automatic gold-piece total
- ⚖️ **Encumbrance Bar** — Live weight tracking vs. carrying capacity (STR × 15 lb) with color-coded status
- 📦 **Item Table** — Add unlimited items with:
  - Name, Type (16 categories), Quantity, Weight (lb), Value (gp), Notes
  - Equipped toggle (green highlight when active)
  - Attunement toggle — enforces the 3-item attunement limit
  - Running totals (qty, total weight, total value)
- 🔍 **D&D Beyond Integration** — Look up any item on [D&D Beyond](https://www.dndbeyond.com) to confirm its existence and view its official description:
  - Click 🔍 on any item to search D&D Beyond (auto-routes to equipment or magic-items based on item type)
  - Click 🔗 to save a direct D&D Beyond URL for the item
  - Saved links are highlighted and persist with save/export
- 📝 **Notes** — Free-text area for quest items, party loot, reminders
- 💾 **Persistence** — Save/load to browser `localStorage`, export to JSON, import from JSON

**To use:**
1. Download or clone this repo.
2. Open `inventory.html` in your browser (double-click the file).
3. Fill in your character info and start adding items.
4. Click **"💾 Save to Browser"** to persist your data between sessions.
5. Use **"⬇ Export JSON"** to back up or share your sheet.

---

## 🎲 Quick Tips

- Hold **Ctrl+F** (or **Cmd+F**) in `cheat-sheet.md` to search for any rule quickly.
- Bookmark `inventory.html` after opening it — your saves are stored in that browser profile.
- Export your JSON after each session so you never lose progress!
