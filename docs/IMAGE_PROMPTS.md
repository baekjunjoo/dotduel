# DotDuel — Nano Banana 이미지 프롬프트 (19개, v2.2)

각 프롬프트는 self-contained. 공통 스타일 가이드(팔레트, 픽셀 스타일, 출력 비율 등) 가 모든 프롬프트에 그대로 포함되어 있어 바로 복붙해서 사용 가능.

**스타일 톤**: Dicey Dungeons + Into the Breach 풍 — 따뜻한 다크 브라운 배경, cozy 카툰 픽셀, 큰 머리/표정 풍부. 다크하고 grim한 톤이 아님.

**저장 위치 권장**: `dotduel-prototype/assets/...` (파일명은 각 프롬프트 위에 명시)

**카드 카테고리 컬러 매핑** (카드 12종은 이 컬러 시스템 적용):
- 창 (Spear) = 스틸 그레이 `#a0a8b8` 주조
- 방패 (Shield) = 황동/골드 `#d4a017` 주조
- 특수 (Special) = 보라 `#8e44ad` 주조

---

## 1. Hero Splash (메인 화면 타이틀)

**파일명**: `assets/splash-hero.png`
**비율 권장**: 1024×768 (4:3 가로)

```
16-bit pixel art game splash illustration for "DotDuel", a 1v1 tactile dueling card game. Style is inspired by Dicey Dungeons — cozy, expressive cartoon pixel art with warm earth tones rather than dark gritty. Scene: two small anthropomorphic animal duelists facing off in an underground dungeon arena. Left: a nimble fox warrior in leather armor with a red shoulder cape, holding a steel spear at the ready in a forward lunge stance. Right: a sturdy bear warrior in heavy iron plate armor with gold trim, holding a large round shield raised defensively. Between them, in the center of the dirt arena floor, a soft warm orange glow pulses. Background: an underground cavern with massive earth-brown stalagmites rising from the floor and stalactites descending from the ceiling, framing the duelists like natural pillars. Subtle scattered pebbles and gravel on the arena floor. Color palette: warm earth tones — dark brown #3a2a1c (background cave depth), cream #f5e9d4 (character highlights, fur), steel gray #a0a8b8 (armor and weapons), blood red #c0392b (fox cape), gold #d4a017 (bear armor trim, shield rim), warm orange #ff7a45 (center pulse glow), warm brown #8b5a2b (stalagmites, dirt floor). Crisp pixel edges, NO anti-aliasing, NO gradients. Cozy cartoon proportions (big heads, expressive faces) like Dicey Dungeons or Into the Breach. Symmetrical horizontal composition with empty space above the characters for the "DotDuel" title text to be overlaid. The mood is playful but tense — a friendly duel about to begin. Output as 1024×768 PNG.
```

---

## 2. 나무창 (Wooden Spear) 카드

**파일명**: `assets/cards/s_wood.png`
**비율**: 256×256 (정사각)

```
16-bit pixel art icon of a wooden spear, viewed from a 45-degree angle, centered on a 256×256 canvas. The spear has a plain whittled brown wood shaft and a small simple grayish iron tip — clearly the weakest, most basic version. Color palette strictly limited to six tones: dark navy #0a0c12 (background), cream #f5e9d4 (light highlights), steel gray #a0a8b8 (iron tip), warm brown #8b5a2b (wood shaft), warm orange #ff7a45 (single highlight pixel on tip), and a thin warm orange border frame around the entire icon. Crisp pixel edges, NO anti-aliasing, NO gradients. Centered composition with the spear running diagonally from bottom-left to top-right. Game card asset for DotDuel, an accessible 1v1 dueling card game. Output as 256×256 PNG.
```

---

## 3. 강철창 (Steel Spear) 카드

**파일명**: `assets/cards/s_steel.png`
**비율**: 256×256

```
16-bit pixel art icon of a steel spear, viewed from a 45-degree angle, centered on a 256×256 canvas. Standard military spear with a polished dark-gray steel shaft and a sharp arrowhead-shaped steel tip with a small blood-red ribbon tied where the head meets the shaft. Stronger and more refined than a wooden spear. Color palette strictly limited to six tones: dark navy #0a0c12 (background), cream #f5e9d4 (highlight pixels on the steel), steel gray #a0a8b8 (main steel body), blood red #c0392b (small ribbon), gold #d4a017 (one accent pixel on tip), and a thin warm orange #ff7a45 border frame around the entire icon. Crisp pixel edges, NO anti-aliasing, NO gradients. Centered composition with the spear running diagonally from bottom-left to top-right. Game card asset for DotDuel, an accessible 1v1 dueling card game. Output as 256×256 PNG.
```

---

## 4. 장창 (Long Spear) 카드

**파일명**: `assets/cards/s_long.png`
**비율**: 256×256

```
16-bit pixel art icon of a very long heavy two-handed spear (a pike), viewed from a 45-degree angle and barely fitting within a 256×256 canvas — the spear should clearly look LONGER and more unwieldy than a normal spear, extending from corner to corner. Dark steel double-edged blade at the tip, long polished wooden shaft with three iron bands wrapped around it for reinforcement. Color palette strictly limited to six tones: dark navy #0a0c12 (background), cream #f5e9d4 (light highlights), steel gray #a0a8b8 (steel blade and bands), warm brown #8b5a2b (wood shaft), blood red #c0392b (tiny tip droplet — implies power), and a thin warm orange #ff7a45 border frame around the entire icon. Crisp pixel edges, NO anti-aliasing, NO gradients. The spear runs diagonally corner-to-corner. Game card asset for DotDuel, an accessible 1v1 dueling card game. Output as 256×256 PNG.
```

---

## 5. 번개창 (Lightning Spear) 카드

**파일명**: `assets/cards/s_bolt.png`
**비율**: 256×256

```
16-bit pixel art icon of a magical lightning spear, viewed from a 45-degree angle, centered on a 256×256 canvas. The spear shaft is shaped like a jagged zigzag lightning bolt rather than a straight pole, with a crackling crystalline blue-white tip emitting small pixel sparks. The whole weapon glows softly. Color palette strictly limited to six tones: dark navy #0a0c12 (background), cream #f5e9d4 (bright highlights on the bolt body), cyan-white #b0e0ff (lightning glow and sparks), steel gray #a0a8b8 (tip core), gold #d4a017 (electric crackle accents), and a thin warm orange #ff7a45 border frame around the entire icon. Crisp pixel edges, NO anti-aliasing, NO gradients. The zigzag spear runs diagonally from bottom-left to top-right. Game card asset for DotDuel, an accessible 1v1 dueling card game. Output as 256×256 PNG.
```

---

## 6. 이중창 (Twin Spear) 카드

**파일명**: `assets/cards/s_twin.png`
**비율**: 256×256

```
16-bit pixel art icon of a pair of twin parallel spears (two short fighting spears side by side, like a dual-wield set), viewed from a 45-degree angle, centered on a 256×256 canvas. Both spears identical: short steel shafts with simple leaf-shaped blades. They are crossed slightly at their midpoints forming a wide X shape. Color palette strictly limited to six tones: dark navy #0a0c12 (background), cream #f5e9d4 (steel highlights), steel gray #a0a8b8 (main blade and shaft), warm brown #8b5a2b (handle grips), blood red #c0392b (two ribbon ties, one per spear), and a thin warm orange #ff7a45 border frame around the entire icon. Crisp pixel edges, NO anti-aliasing, NO gradients. Symmetrical X composition. Game card asset for DotDuel, an accessible 1v1 dueling card game. Output as 256×256 PNG.
```

---

## 7. 목방패 (Wood Shield) 카드

**파일명**: `assets/cards/d_wood.png`
**비율**: 256×256

```
16-bit pixel art icon of a small round wooden buckler shield, viewed straight on from the front, centered on a 256×256 canvas. The shield is a basic circular wooden disk with visible plank grain in horizontal stripes and a single small iron boss in the center. Plain and rustic — the cheapest defensive option. Color palette strictly limited to six tones: dark navy #0a0c12 (background), cream #f5e9d4 (highlight pixels on wood), warm brown #8b5a2b (main wood body), darker brown #5a3a1c (wood grain shadow lines), steel gray #a0a8b8 (iron boss in center), and a thin warm orange #ff7a45 border frame around the entire icon. Crisp pixel edges, NO anti-aliasing, NO gradients. Perfectly centered round shield. Game card asset for DotDuel, an accessible 1v1 dueling card game. Output as 256×256 PNG.
```

---

## 8. 철방패 (Iron Shield) 카드

**파일명**: `assets/cards/d_iron.png`
**비율**: 256×256

```
16-bit pixel art icon of a standard heater-style iron shield (kite-shape, flat top with tapered bottom), viewed straight on from the front, centered on a 256×256 canvas. Dark gray iron body with riveted edges (small visible pixel dots around the perimeter) and a vertical cream-colored stripe down the center. Solid medieval feel. Color palette strictly limited to six tones: dark navy #0a0c12 (background), cream #f5e9d4 (center stripe + highlight pixels), steel gray #a0a8b8 (main iron body), darker gray #5a606e (shadow side of shield), gold #d4a017 (single rivet pixels — small accent), and a thin warm orange #ff7a45 border frame around the entire icon. Crisp pixel edges, NO anti-aliasing, NO gradients. Centered shield filling most of the canvas. Game card asset for DotDuel, an accessible 1v1 dueling card game. Output as 256×256 PNG.
```

---

## 9. 타워방패 (Tower Shield) 카드

**파일명**: `assets/cards/d_tower.png`
**비율**: 256×256

```
16-bit pixel art icon of a massive rectangular tower shield (very tall and wide, almost filling the entire frame), viewed straight on from the front, centered on a 256×256 canvas. The shield is made of riveted iron plates arranged in three vertical sections with horizontal reinforcement bars. Imposing and heavy. A small slit visible at the top for the bearer to see through. Color palette strictly limited to six tones: dark navy #0a0c12 (background — minimal visible since shield fills frame), cream #f5e9d4 (highlight pixels on plates), steel gray #a0a8b8 (main iron plates), darker gray #5a606e (gaps between plates and shadows), gold #d4a017 (rivet accents along reinforcement bars), and a thin warm orange #ff7a45 border frame around the entire icon. Crisp pixel edges, NO anti-aliasing, NO gradients. Game card asset for DotDuel, an accessible 1v1 dueling card game. Output as 256×256 PNG.
```

---

## 10. 반사방패 (Mirror Shield) 카드

**파일명**: `assets/cards/d_mirror.png`
**비율**: 256×256

```
16-bit pixel art icon of a polished mirror shield (round, ornate), viewed straight on from the front, centered on a 256×256 canvas. The shield's face is highly reflective with a stylized cross-shape of bright cream highlight running through the center, suggesting that light is being bounced off. Ornate gold trim border around the rim. Mysterious, magical, valuable looking. Color palette strictly limited to six tones: dark navy #0a0c12 (background), cream #f5e9d4 (bright cross-reflection on shield face), steel gray #a0a8b8 (main polished mirror body), gold #d4a017 (ornate border trim), blood red #c0392b (small ruby accent at top center), and a thin warm orange #ff7a45 border frame around the entire icon. Crisp pixel edges, NO anti-aliasing, NO gradients. Centered round shield. Game card asset for DotDuel, an accessible 1v1 dueling card game. Output as 256×256 PNG.
```

---

## 11. 응급치료 (First Aid / Heal) 카드

**파일명**: `assets/cards/x_heal.png`
**비율**: 256×256

```
16-bit pixel art icon of a healing potion bottle plus a small green leaf, centered on a 256×256 canvas. The bottle is rounded with a cork stopper, filled with glowing red liquid suggesting health potion. A small fresh green leaf rests behind the bottle. Gentle, life-restoring energy. Color palette strictly limited to six tones: dark navy #0a0c12 (background), cream #f5e9d4 (bottle highlights, cork edge), steel gray #a0a8b8 (cork stopper), blood red #c0392b (potion liquid), green #4caf50 (single leaf — only this card uses green), and a thin warm orange #ff7a45 border frame around the entire icon. Crisp pixel edges, NO anti-aliasing, NO gradients. Centered composition. Game card asset for DotDuel, an accessible 1v1 dueling card game. Output as 256×256 PNG.
```

---

## 12. 속임수 (Feint) 카드

**파일명**: `assets/cards/x_feint.png`
**비율**: 256×256

```
16-bit pixel art icon of a stylized eye obscured by a swirl of fog or shadow tendrils, centered on a 256×256 canvas. The eye is half-hidden behind drifting smoky tendrils that seem to obscure vision. The pupil is gold and unsettling. Mysterious, deceptive feel — the card hides information from the enemy. Color palette strictly limited to six tones: dark navy #0a0c12 (background), cream #f5e9d4 (eye white and brightest highlights), steel gray #a0a8b8 (smoky tendrils), darker gray #5a606e (deeper smoke shadows), gold #d4a017 (eye pupil), and a thin warm orange #ff7a45 border frame around the entire icon. Crisp pixel edges, NO anti-aliasing, NO gradients. Centered composition. Game card asset for DotDuel, an accessible 1v1 dueling card game. Output as 256×256 PNG.
```

---

## 13. 결투 신청 (Challenge / Duel) 카드

**파일명**: `assets/cards/x_duel.png`
**비율**: 256×256

```
16-bit pixel art icon of two crossed swords with a small red banner flag draped between them (the universal symbol of a formal duel challenge), centered on a 256×256 canvas. Both swords identical, steel blades with simple cross-guards and dark grips, forming a perfect X. The banner is a small triangular pennant in blood red, draped where the swords meet. Bold, declarative, dangerous. Color palette strictly limited to six tones: dark navy #0a0c12 (background), cream #f5e9d4 (sword blade highlights), steel gray #a0a8b8 (main sword bodies), darker gray #5a606e (handle grips), blood red #c0392b (banner), and a thin warm orange #ff7a45 border frame around the entire icon. Crisp pixel edges, NO anti-aliasing, NO gradients. Symmetrical X composition. Game card asset for DotDuel, an accessible 1v1 dueling card game. Output as 256×256 PNG.
```

---

## 14. Victory Screen (승리 화면)

**파일명**: `assets/victory.png`
**비율**: 1024×768

```
16-bit pixel art victory illustration for DotDuel, an accessible 1v1 dueling card game. A single triumphant pixel-art warrior stands at the center of an arena platform with arms raised, holding a spear high in one hand and a shield low in the other. Behind them, a stylized large geometric sunrise — concentric rings of cream and gold pixels radiating outward from the warrior. Confetti-like small floating gold pixels scattered around the upper area. Color palette strictly limited to six tones: dark navy #0a0c12 (background base), cream #f5e9d4 (warrior body, sunrise rings, confetti), gold #d4a017 (sunrise highlights, banner), steel gray #a0a8b8 (weapons, ground), blood red #c0392b (small cape detail on warrior), warm orange #ff7a45 (single bright pulse at warrior's chest — heart of victory). Crisp pixel edges, NO anti-aliasing, NO gradients. Symmetrical horizontal composition with the warrior centered, space below for "VICTORY" text overlay. Mood is celebratory but quiet — like the moment after a duel ends. Output as 1024×768 PNG.
```

---

## 15. Defeat Screen (패배 화면)

**파일명**: `assets/defeat.png`
**비율**: 1024×768

```
16-bit pixel art defeat illustration for DotDuel, an accessible 1v1 dueling card game. A single pixel-art warrior kneels at the center of an empty arena platform with a broken spear lying on the ground beside them and their shield fallen flat. The warrior's head is bowed. Background is a stylized large geometric moonset — concentric rings of muted cream and steel-gray pixels radiating from the warrior, fading into the dark navy sky. A single small warm-orange ember floats above the warrior, like a quiet remembrance. Color palette strictly limited to six tones: dark navy #0a0c12 (background base, dominant), cream #f5e9d4 (warrior body, moonset rings), steel gray #a0a8b8 (broken spear, shield, ground), darker gray #5a606e (deeper shadows), blood red #c0392b (single small detail — maybe a torn ribbon on the broken spear), warm orange #ff7a45 (single floating ember). Crisp pixel edges, NO anti-aliasing, NO gradients. Symmetrical horizontal composition with the warrior centered, space below for "DEFEAT" text overlay. Mood is solemn, not despairing — quiet dignity in loss. Output as 1024×768 PNG.
```

---

## 16. Duelist A — 여우 창잡이 (Fox Spearmaster, 좌측)

**파일명**: `assets/duelist-fox.png`
**비율**: 256×384 (세로 2:3)

```
16-bit pixel art character sprite of a small anthropomorphic fox warrior, shown full body, centered on a 256×384 vertical canvas with transparent or solid dark brown #3a2a1c background. Style inspired by Dicey Dungeons — cozy cartoon proportions, large expressive eyes, big head relative to body, friendly but determined facial expression. The fox has cream and warm-orange fur (#f5e9d4 belly + #ff7a45 back), bushy tail visible behind, perked triangular ears. Equipment: simple leather chest armor with steel shoulder pauldrons, blood-red shoulder cape draped behind, fingerless leather gloves. Pose: standing in a forward-lunge spear stance, body slightly turned to the right (facing right toward an unseen opponent), front paw forward, holding a steel spear angled diagonally upward toward the upper right corner of the canvas. The spear has a leaf-shaped steel blade and a wooden shaft. Color palette strictly limited to seven tones: dark brown #3a2a1c (background), cream #f5e9d4 (fox belly, fur highlights), warm orange #ff7a45 (fox back fur, signature accent), steel gray #a0a8b8 (armor, spear), warm brown #8b5a2b (leather, wooden shaft), blood red #c0392b (cape), black #0a0c12 (outline + eye pupils). Crisp pixel edges, NO anti-aliasing, NO gradients. Clear silhouette readability. Game asset for DotDuel — this is the LEFT-SIDE player's character in the arena. Output as 256×384 PNG.
```

---

## 17. Duelist B — 곰 방패잡이 (Bear Shieldwarden, 우측)

**파일명**: `assets/duelist-bear.png`
**비율**: 256×384

```
16-bit pixel art character sprite of a stocky anthropomorphic bear warrior, shown full body, centered on a 256×384 vertical canvas with transparent or solid dark brown #3a2a1c background. Style inspired by Dicey Dungeons — cozy cartoon proportions, large expressive eyes, big head and broad shoulders, calm and watchful facial expression with a faint smile. The bear has cream-and-gray fur (#f5e9d4 face/belly + #a0a8b8 body fur), small round ears, a short snout. Equipment: heavy iron plate armor with gold trim across the chest piece, steel gauntlets, leather boots with gold buckles. Pose: standing in a stable defensive shield-up stance, body slightly turned to the left (facing left toward an unseen opponent — mirrored from the fox), holding a large round iron shield raised in front of the chest, the shield has gold rim trim and a small gold boss in the center. A thick wooden club or mace is sheathed at the bear's belt as a sidearm. Color palette strictly limited to seven tones: dark brown #3a2a1c (background), cream #f5e9d4 (bear face/belly, highlights), steel gray #a0a8b8 (armor, fur, shield body), darker gray #5a606e (armor shadows), gold #d4a017 (armor trim, shield rim), warm brown #8b5a2b (club handle, boots), black #0a0c12 (outline + eye pupils). Crisp pixel edges, NO anti-aliasing, NO gradients. Clear silhouette readability. The bear should feel BIGGER and HEAVIER than a fox character — broader shoulders, lower center of gravity. Game asset for DotDuel — this is the RIGHT-SIDE player's character in the arena. Output as 256×384 PNG.
```

---

## 18. Arena Background (전투 배경)

**파일명**: `assets/arena-bg.png`
**비율**: 1024×512 (가로 2:1)

```
16-bit pixel art background illustration of an underground dungeon dueling arena, centered on a 1024×512 horizontal canvas. Style strongly inspired by Dicey Dungeons / Into the Breach — cozy cartoon pixel art with warm earth tones, NOT dark or gritty. Composition: a circular dirt arena floor in the lower center occupying about 60% of the lower half, surrounded on left and right by massive towering stalagmites and stalactites forming natural pillars that frame the scene like proscenium curtains. The center floor is packed dirt with scattered small pebbles and pixel-art rocks. Behind the arena, the cave recedes into darker depths suggesting an audience or void. Atmosphere is illuminated by a soft warm glow from the center floor, as if torches just out of frame are casting light. NO characters in this scene — this is a clean background that two duelist sprites will be composited on top of. Color palette: dark brown #3a2a1c (deep background), warm brown #8b5a2b (stalagmites, walls, dirt), cream #f5e9d4 (light highlights on stone), steel gray #a0a8b8 (rocks, mineral details on stalagmites), darker gray #5a606e (deep shadows in stalagmite crevices), warm orange #ff7a45 (subtle glow on the arena floor center, suggesting warm torchlight). Crisp pixel edges, NO anti-aliasing, NO gradients. Symmetrical composition (left and right stalagmites mirror each other). The arena floor has visible texture (small pebble pixels). Game asset for DotDuel — this is the main background used during all duels. Output as 1024×512 PNG.
```

---

## 19. Match Lobby / Matchmaking Splash

**파일명**: `assets/matchmaking-bg.png`
**비율**: 1024×512

```
16-bit pixel art illustration for the matchmaking lobby screen of DotDuel, centered on a 1024×512 horizontal canvas. Scene: the empty dueling arena (same underground dungeon as the main arena) with NO duelists yet — just the circular dirt floor and surrounding stalagmites — but with a soft pulsing warm orange glow in the center where the future opponent will appear. To the side of the arena, three small pixel-art silhouettes of waiting duelists (different animal warriors: a fox, a bear, a rabbit) are shown faint and translucent like ghosts or holograms, suggesting "searching for opponent". Below them, three small dot icons in cream color forming a "loading" pattern. Style inspired by Dicey Dungeons — cozy cartoon pixel art with warm earth tones. Color palette: dark brown #3a2a1c (deep background), warm brown #8b5a2b (stalagmites, walls, dirt), cream #f5e9d4 (silhouettes, loading dots, light highlights), steel gray #a0a8b8 (stone details), warm orange #ff7a45 (center pulse, suggesting the duel waiting to begin), gold #d4a017 (small accent on the loading dots). Crisp pixel edges, NO anti-aliasing, NO gradients. Symmetrical composition. Game asset for DotDuel — used during the "Finding opponent..." matchmaking screen. Output as 1024×512 PNG.
```

---

## 사용 안내

1. 위 19개 프롬프트 그대로 Nano Banana에 복붙
2. 생성된 PNG들을 `dotduel-prototype/assets/` 폴더에 명시된 파일명대로 저장
3. 카드 이미지들은 `assets/cards/` 하위 폴더에
4. 색상 코드는 모든 프롬프트에 동일하게 박혀 있어 자동으로 톤이 통일됨
5. 톤이 안 맞으면 "Style strongly inspired by Dicey Dungeons" 줄을 더 강조하거나 "cozy warm earth tones, not dark gritty" 추가

## 우선 생성 순서 (테스트용 권장)

| Order | 이미지 | 이유 |
|---|---|---|
| 1 | **#18 arena-bg** | 화면 배경 — 가장 빈번하게 노출, 전체 톤 결정 |
| 2 | **#16 duelist-fox** + **#17 duelist-bear** | 캐릭터 — 톤 일치 확인 |
| 3 | **#1 splash-hero** | 메인 화면 첫인상 |
| 4 | **#3 s_steel** | 카드 톤 샘플 (강철창 — 가장 기본) |
| 5 | 나머지 카드 11종 | 톤 OK면 일괄 생성 |
| 6 | **#19 matchmaking-bg** + **#14 victory** + **#15 defeat** | 부가 화면 |

## 색상 팔레트 요약 (v2.2 — Dicey Dungeons 따뜻한 톤)

| 색 | HEX | 용도 |
|---|---|---|
| Dark Brown | `#3a2a1c` | 메인 배경 (아레나, 패널 등) — 새로운 기본 배경 |
| Dark Navy | `#0a0c12` | 카드 배경 + Dot Pad screen 색과 일치 |
| Cream | `#f5e9d4` | 캐릭터 하이라이트·텍스트 |
| Steel Gray | `#a0a8b8` | 무기·금속·창 카테고리 시그너처 |
| Darker Gray | `#5a606e` | 그림자 |
| Blood Red | `#c0392b` | 공격·위험·여우 망토 |
| Gold | `#d4a017` | 방패 카테고리 시그너처 + 곰 트림 + 희귀 |
| Purple | `#8e44ad` | 특수 카드 카테고리 시그너처 (v2.2 신규) |
| Warm Orange | `#ff7a45` | 시그너처 액센트 + 아레나 펄스 |
| Warm Brown | `#8b5a2b` | 나무·가죽·동굴 벽 |
| Green | `#4caf50` | 치료 (응급치료 카드 전용) |
| Cyan-White | `#b0e0ff` | 번개 (번개창 전용) |
