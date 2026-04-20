# Orka Giant Spiders

The best AFK combat XP/h method in F2P. Train on Giant Spiders (3rd floor of the Stronghold of Security) with automatic aggro resetting and Edgeville banking.

---

## 🚀 Features

- 🎯 **AFK Training:** Automatic aggro resetting.
- 🏦 **Banking:** Full Edgeville restock loop with multi-floor ladder + portal navigation.
- 🚪 **Security Gates:** Solves the Stronghold of Security gate dialogs automatically. Behavior is configurable via the `GATE_BEHAVIOR` constant near the top of the script:
  - `0` — always brute-force (ignore questions, re-click the gate until player passes through).
  - `1` — BioDice decides per gate (randomly brute-force or answer). **Default.**
  - `2` — always answer the security questions (with a small configurable chance of intentionally failing, via `GATE_FAIL_ANSWER_CHANCE`).
- 🧪 **Consumables:** Supports food (Swordfish, Lobster, Tuna, Salmon, Pike, Trout) and optional Strength potions.
- 💬 **Discord:** Hourly reports, level-ups, session summary on termination, optional anonymous screenshots.
- 🤖 **Antiban:** Breaks, sleeps, scheduled shutdown, and humanized mouse / camera / idle behavior.

---

## 📋 Requirements

- **Recommended Melee Levels:** 40+ Attack / Strength, 30+ Defence, with at least Adamant-tier gear.
- **XP Bar:** Must be visible.

---

## ⚙️ Setup

### 📍 Starting Position

The script auto-detects the starting location. Start from either of the following:

- **Stronghold of Security — 3rd floor:** at the floor entrance, between the first set of security gates, or already in the combat area.
- **Around Edgeville:** Edgeville bank, Barbarian Village, Grand Exchange, or West Varrock bank.

### 🏦 Bank Setup

- Place required items in the **first bank tab, at the top**:
  - Chosen food (e.g. Swordfish).
  - Strength potions (4-dose) if potions are enabled.
- The script searches for missing items but this is slower.

---

## 💡 Tips

- Higher combat stats mean faster kills and safer AFK windows between aggro resets.

---

## 💬 Support

For issues, feedback, or suggestions, visit the [script post on Discord](https://discord.com/channels/795071177475227709/1495604429888557176).
