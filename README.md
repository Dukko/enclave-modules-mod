# Drukhal's Enclave Additions

A Stellaris mod that adds starbase buildings and waystation modules for the enclaves that never got them. Each enclave unlocks content through a partnership event once your opinion reaches 50+.

**[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3746975952)**

---

## What's Included

### Shroudwalkers
- **Shroud Conduit** (starbase building) — Unity, tradition cost reduction, and psionic bonuses. Psionic empires gain deeper rewards including Zro production.
- **Shroud Communion Chamber** (waystation module) — Same themes for nomadic empires, with wayline network effects.

### Mindwardens
- **Warden's Vigil** (starbase building) — Cloaking detection, hull hardening, ship upkeep reduction, and spy network bonuses. Not available to psionic empires.
- **Warden's Monitoring Post** (waystation module) — Nomadic equivalent, with wayline network effects.

### Curators *(Leviathans DLC)*
- **Curator Archive** (starbase building) — Physics and society research, anomaly generation bonuses. Available to all non-homicidal empires including gestalts.
- **Curator Survey Terminal** (waystation module) — Nomadic equivalent, with wayline network effects.

### Artisan Troubadours *(Leviathans DLC)*
- **Artisan Grand Stage** (starbase building) — Unity, pop happiness, and amenity bonuses. Spiritualist empires get extra rewards.
- **Artisan Touring Stage** (waystation module) — Nomadic equivalent with morale and unity wayline effects.

### Trader Enclaves (XuraCorp, Riggan, Muutagan)
One building and one waystation module per enclave, each producing their respective strategic resource (exotic gases, volatile motes, rare crystals) and improving empire-wide yields.

If all three trader enclaves like you simultaneously, they'll offer **The Traders' Compact** — all three partnerships at a discount.

### Caravaneers / Numistic Order *(MegaCorp DLC)*
- **Caravaneer Credit Exchange** (starbase building) — Trade collection, empire size reduction, trade fee savings. Not available to gestalt empires.
- **Caravaneer Waypoint Exchange** (waystation module) — Nomadic equivalent with wayline network effects.

---

## Special Events

**The Traders' Compact** — fires when all three trader enclaves reach opinion 50+ simultaneously. Unlocks all three trader partnerships at a bundled discount.

**Grand Commercial Network** — hold all three Trader Compact partnerships *and* the Caravaneer partnership and the four commercial enclaves propose a unified economic framework. One-time permanent bonus: 1000 energy, 200 alloys, rare resources, plus empire-wide −10% trade fee, −5% empire size, −3% ship upkeep. *(MegaCorp DLC required)*

---

## Design Notes

- Each building/module is **limited to one per empire**. The option hides once you've built one anywhere.
- Buildings are for traditional (non-nomadic) empires; waystation modules require **Overlord DLC** and nomadic play.
- Wayline network modifiers on waystation modules are empire-wide bonuses from the partnership agreement — they don't require the enclave to be present in the same system.
- All content is gated behind partnership events, consistent with how the other enclave modules work. No content unlocks at game start.

---

## Compatibility

- **Required:** Base Stellaris (4.x)
- **Required for waystation modules:** Overlord DLC
- **Required for Curator/Artisan content:** Leviathans DLC
- **Required for Caravaneer content:** MegaCorp DLC
- Does not overwrite any vanilla files. Should be compatible with most other mods.

---

## Structure

```
common/
  starbase_buildings/   # Buildings for traditional empires
  starbase_modules/     # Waystation modules for nomadic empires
  on_actions/           # Five-year pulse partnership events
  static_modifiers/     # Grand Commercial Network permanent bonus
events/                 # Partnership proposal events
localisation/english/   # All text strings
gfx/                    # Icons
interface/              # Icon definitions
```

---

## Feedback & Bugs

Issues and suggestions welcome via GitHub or the Steam Workshop comments.
