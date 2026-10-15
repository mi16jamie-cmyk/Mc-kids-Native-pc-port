### Running the game
- Runs as a single Windows program, `MC Kids.exe`, with its own "MC" icon. It needs no extra files apart from your ROM.
- Settings are saved in `mckids.cfg` and save states in the `saves` folder.

### Screen
- Screen shapes: 4:3 (original), 16:9, 16:10 and 21:9.
- Upscaling: Off, Scale2x, Scale3x, Scale4x and Scale6x.
- Sharp-pixels option and fullscreen.
- **TV effect:** Off, Scanlines, or CRT (a slightly curved screen with darker corners, soft scanlines, a fine colour-stripe mask and a little glow).
- **Colours:** Bright (the default), Warm (closer to a real NES on a TV) or Soft (gentler colours).
- **Flicker:** "removed" shows every sprite on a line, so nothing flickers when lots of characters line up. "original" keeps the NES's limit of 8 sprites per line. The game plays exactly the same either way.
- **Extras:** switches the little scene touches on or off (see below).

### Widescreen
Everything beyond the original 256-pixel-wide picture is new in the port.
- **Platform levels:** built from the game's own level map, so the extra width shows real level that you can see further into. Enemies in the side areas are already active and don't pop in.
- **Rooms (title, clubhouse):** extended from each room's own map.
  - Grimace's room gets smooth, bumpy clouds, bushes and grass.
- **Player select:**
  - New clouds.
  - The stars are scattered at random instead of sitting in a line.
- **World maps:** extended with their own ground, trees, paths, rivers and cliffs.
  - Half-cut trees are removed.
  - The fence round the house on map 1 is finished.
  - Map 2 gets clouds and islands.
  - The cliffs on map 3 continue in the same staggered pattern.
  - The odd small islands on map 6 are removed.
  - The pit on map 7 continues.
- **Opening plane:** the Virgin plane tail glides smoothly across the whole width.
- **Night camp scene:** the treeline continues, with stars, a third house, extra lit windows, more trees and a campfire.
  - The big tree on the right is a normal width, with its full branch and natural canopy.
  - An owl sits on the branch with bright, blinking eyes.
  - The moon is a bright full moon with a soft glow, and a small shooting star crosses the sky now and then.
- **Inside the tent:**
  - The tent edges continue naturally.
  - The two boys have pupils in their eyes.
- **Storybook:**
  - The book sits in the middle of the screen with both pages shown.
  - The blank left page has a framed picture of the Hamburglar (the game's own sprite) peeking from behind a bush.
  - Two hands hold the book, with blue sleeves.
- **Level complete:** after the high five, both boys walk off across the full width of the screen.
- **Rocket ship room:** the clouds at the sides have round bumps of different sizes instead of straight rows.
- **Ending (Ronald thanks you):** the sun's beams carry on at their own angles to the edges of the screen, the fence posts continue, and the clouds at the edges are whole clouds.
- **Clubhouse rooms:** the little arches, stars and moons in the sky are scattered at random in the side areas instead of sitting in a straight row.
- **Characters walking in:** someone arriving from off the picture, like Ronald at his house, comes in from the very edge of the wide screen instead of popping up partway across.
- **Get Ready, Game Over, Bonus Game and credits screens:** their background colour carries on across the full width.
- **End credits:** the game's red X-box "stars" are replaced with twinkling stars that carry on across the full width.
- **Other screens:** any other screen gets a soft, darkened fill instead of black bars.

### Extras (can be switched off in the menu)
- Stars in the night levels twinkle and now and then flash.
- Lava gently shimmers.
- Small clouds drift slowly across the world maps.

### Look
- **Skin colours:**
  - The boy with the afro (Mack) is a natural brown.
  - The boy in the cap (Mick) is a natural light skin tone.
  - These replace the original green and yellow, and apply in the levels, on player select, in the tent, on the storybook hands, on the Get Ready portraits and on the level complete screen.
- **Golden arches:** the arches you collect are golden yellow with a deep gold side.

### Sound
- **Stereo:** the two lead voices are panned left and right, while the bass, drums and samples stay in the middle. The menu has a Stereo / Mono switch.
- **Volume:** separate Music and Effects volume as well as overall volume.

### Controls and extras
- **Keyboard and controllers:** keyboard plus Xbox and other controllers. Every controller button can be changed in Controller setup.
- **Save states:** 9 slots, with quick save and load on F5 and F9.
- **Fast-forward:** hold Tab or the right trigger.
- **Rewind:** hold R or LB (left shoulder) to rewind up to about 30 seconds, then carry on from there.
- **Cheats menu:** infinite lives, infinite health, 99 arches and a level select.

### Fixes made during Version 1
- **Screen changes:** no distortion when moving between screens or just before a level starts.
- **Moving characters and the screen edges:** characters and objects no longer get stretched or leave ghost images as they move between the middle and the wide sides. This covers:
  - the frog jumping past the tree
  - the boy walking off the player select screen
  - the boys walking off after the high five
  - the plane tail
- **Copyright screen:** no stray face or hand in the middle of the copyright screen.
- **Opening plane:** the tail now glides in smoothly from the far right edge, instead of popping up partway across.
- **Menu:** the pause menu fits on the screen with all the new options.
- **Storybook:** no green smear on the hand.

---

## Part 2: How the port differs from the NES original

| | NES original | This port |
|---|---|---|
| Game rules and levels | — | Unchanged: the original program runs as it is |
| Screen width | 256 pixels (4:3) | Up to 21:9, with real level or matching scenery in the extra space |
| Picture | NES resolution | Optional Scale2x–6x smoothing, scanlines or CRT look, three colour styles, fullscreen |
| Sprite flicker | Flickers when more than 8 sprites share a line | Can be removed in the menu |
| End credits stars | Red X boxes | Twinkling stars |
| Night levels, lava, world maps | Still | Twinkling stars, shimmering lava, drifting clouds (switchable) |
| Edge of the screen in levels | Enemies appear right at the edge | Enemies are already active in the wider view (two bytes of the game's object window are adjusted) |
| Mack's skin | Olive green | Natural brown |
| Mick's skin | Bright yellow | Natural light skin |
| Collectable arches | Pale cream with a dark red side | Golden yellow with a deep gold side |
| Night camp moon | Grey cratered moon | Bright full moon with a glow |
| Night camp sky | — | Occasional small shooting star |
| Night camp extras | — | Third house, extra windows, campfire, owl with blinking eyes, full-width tree |
| Tent scene | Boys have solid black eyes | Eyes have pupils |
| Storybook | Right-hand page and one olive-green hand | Whole book centred, two hands with blue sleeves, and the left page has a framed picture of the Hamburglar behind a bush |
| Sound | Mono | Stereo (switchable), separate music and effects volume |
| Saving | Not possible | 9 save-state slots plus quick save and load |
| Speed | Normal only | Hold to fast-forward or rewind |
| Cheats | None | Infinite lives and health, 99 arches, level select |
| Controls | NES pad | Keyboard or any modern controller, all buttons remappable |

Everything the port adds is drawn or played by the PC program around the original game. None of it changes the cartridge's own code, apart from the two bytes that let enemies come alive in the wider view.
