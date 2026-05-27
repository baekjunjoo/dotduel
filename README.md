# DotDuel — Tactile 1v1 Card Duel

The 4th game in **Dot Arcade**: a 1v1 dueling card game designed from the ground up for blind users. Built around the **Dot Pad** multi-line braille graphic display, with voice narration and SFX so it plays end-to-end without any screen.

**Concept**: Spear vs Shield vs Special. Each turn both players commit a card; clash resolves; HP ticks down. First to 0 HP (or higher HP at turn 15) wins.

**For**: [Dot Pad](https://www.dotincorp.com) — the world's first multi-line braille graphic display
**Built with**: Web Bluetooth / Web Serial, Web Audio, Web Speech API + (Azure Neural TTS optional later)

> **Status**: v0.1 — Bot duel works end-to-end. Quick / Friend / Tutorial modes scheduled for v0.2+.

---

## How to play

1. Open the game (Chrome/Edge desktop required for Dot Pad)
2. (Optional) Click `PAD` in the header → Bluetooth → pair with your Dot Pad
3. Splash → `START` → Lobby
4. Pick **Bot Duel** → choose difficulty → start
5. In match: Pan keys (or `←/→`) to focus a card → `F3` (double-tap) to commit
6. Voice narrates everything; Dot Pad shows opponent card / clash / your card in 3 zones

### Key Mapping

| Key | Action |
|---|---|
| `F1` or `1` | Voice briefing (turn / HP / opponent HP) |
| `F2` or `2` | Read current focused card description (full TTS) |
| `F3` or `3` or `Enter` | Commit selected card |
| `F4` or `4` or `Escape` | Cancel / return |
| `←` `→` or Pan left/right | Move card focus |
| `⊙` Pan center | Repeat last speech |

---

## Card Pool (12 cards)

### Spear ▲ (Attack)
| Card | ATK | Effect |
|---|---|---|
| Wooden Spear | 1 | — |
| Steel Spear | 2 | — |
| Long Spear | 3 | Next turn: defense −1 |
| Lightning Spear | 2 | Ignores opponent shield |
| Twin Spear | 1×2 | Two strikes (both checked against shield) |

### Shield ■ (Defense)
| Card | DEF | Effect |
|---|---|---|
| Wood Shield | 1 | — |
| Iron Shield | 2 | — |
| Tower Shield | 3 | Persists 2 turns (no attack next turn) |
| Mirror Shield | 1 | Reflects half of blocked damage |

### Special ●
| Card | Effect |
|---|---|
| First Aid | Heal 2 HP |
| Feint | Hide your next card category from opponent |
| Challenge | Both sides take 2 damage |

---

## Dot Pad Layout (300 cells = 30 × 10)

| Rows | Zone | Content |
|---|---|---|
| 0-2 (3 rows) | **Opponent** | Rectangle frame + category hint (vertical bar = spear / horizontal = shield / center blob = special) |
| 3-6 (4 rows) | **Clash arena** | Impact animation on resolve |
| 7-9 (3 rows) | **Your card** | Large triangle/square/circle symbol of currently focused card |

20-cell text line shows `MY:HP T:TURN OP:HP` in compact braille.

---

## File Structure

```
dotduel-prototype/
├── index.html              # Single-file app (HTML + CSS + JS)
├── dotpad-sdk/
│   └── DotPadSDK-3.0.0.js  # Dot Pad Web SDK
├── assets/                 # Image assets (generate via IMAGE_PROMPTS.md)
│   ├── splash-hero.png
│   ├── duelist-fox.png
│   ├── duelist-bear.png
│   ├── arena-bg.png
│   └── cards/ (12 card images)
├── docs/
│   ├── GDD_v2.1.md         # Full design spec
│   └── IMAGE_PROMPTS.md    # 19 Nano Banana prompts (self-contained)
└── README.md
```

Settings persist in `localStorage` (`dotduel:save:v1`).

---

## Deployment (GitHub Pages)

```bash
cd ~/Documents/Claude/Projects/Dot\ Arcade/dotduel-prototype
git init
git add .
git commit -m "Initial DotDuel prototype v0.1"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/dotduel.git
git push -u origin main
```

Then enable GitHub Pages: Settings → Pages → Source `main` / root.

**HTTPS required** for Web Bluetooth. GitHub Pages provides this automatically.

---

## Roadmap

### v0.1 (current)
- [x] Bot duel (3 difficulties)
- [x] 12-card pool + combat resolution
- [x] Dot Pad 3-zone rendering
- [x] Voice (Samantha / Google US English)
- [x] SFX (Web Audio synthesis)
- [x] Splash + lobby + arena UI

### v0.2 (next)
- [ ] Tutorial mode (3 steps)
- [ ] Settings modal (rate, voice, planning-time)
- [ ] Replace ASCII duelists with `duelist-fox.png` / `duelist-bear.png` + arena bg

### v0.3 (multiplayer)
- [ ] Firebase Realtime Database integration
- [ ] Quick Duel — auto matchmaking (10s queue, bot fallback)
- [ ] Friend Duel — 4-digit room code
- [ ] Anonymous auth + rate limiting

### v1.0 launch
- [ ] All modes shipped, WCAG 2.1 AA audit, polished sound/visuals
- [ ] 19 Nano Banana images integrated

### v1.1
- 24 cards · deck builder · stats · server-side anti-cheat · multilingual (en/ko)

---

## Credits

- **Concept & design**: Dot Incorporation
- **Inspired by**: Dicey Dungeons (UI aesthetic) · classic 1v1 dueling card games
- **Dot Pad SDK**: Dot Incorporation
