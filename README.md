# M23: The Last Patrol

A mobile-first, fictionalized 2D story-game prototype inspired by events in eastern Congo and the public legacy of Colonel Mamadou Ndala.

Creator and public support contact: KAMATE KATENDE TIMOTHEE — kamatekatende@gmail.com

## Run locally

Use any static web server from this directory. For example:

```powershell
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy on Render

This repository includes `render.yaml` for a Render Static Site. Connect the repository in Render and create a Blueprint; no build command or server is required.

## Current prototype

- Three geographically linked missions from Goma to Beni
- Keyboard controls: WASD/arrows, Enter or Space; touch controls: OK/Enter button
- Mamadou is visibly identified and accompanied by a multi-soldier squad
- Enemy fire, health damage, ranged response, regrouping, and a scripted Ngadi ambush
- Squad-protection system: sustained hits remove soldiers, while Mamadou can regroup before the final trap
- True mission failure: after the entire squad is lost, continued fire can kill Mamadou and forces a mission retry
- Adaptive danger music that accelerates and intensifies during firefights and low-team situations
- Directional aiming: Mamadou, his squad, and his weapon turn with the movement arrows; firing follows his facing direction
- Mission-specific terrain and restrictions: Goma lava fields, Rutshuru forest checkpoints, and the narrow Ngadi forest road
- Progressive difficulty through tougher enemies, faster fire, larger detection ranges, and gated security lines
- English/French language selection covering menus, objectives, missions, radio dialogue, instructions, failure outcomes, and historical ending
- Bilingual player feedback form with optional device diagnostics, email delivery, and a copy-to-clipboard fallback
- Safe save-and-exit flow for browsers and installed PWAs, with complete audio shutdown
- Reduced animation work while paused to improve mobile battery use and performance
- Mobile aim assistance, mission-entry protection, and adaptive tactical support after casualties or retries
- Pause/resume plus manual and automatic local checkpoint saves
- Continue-from-save restores health, score, position, direction, objectives, squad, enemies, and mission progress
- Save-and-quit and campaign completion shut audio down immediately; hiding the app suspends audio and opens pause
- Localized synthesized radio announcements describe alternate mission-failure consequences for Goma, Rutshuru, or Beni
- Mobile virtual joystick appears wherever the left thumb touches; drag direction controls movement and weapon aim
- Right-side screen tap or floating OK button fires/interacts, with supported-device haptic feedback
- Touch controls overlay the battlefield to maximize the Android/iPhone play area, respect safe areas, and prevent page scrolling
- Portrait phones receive a landscape-rotation prompt only when live gameplay begins
- Fullscreen request on Begin/Continue and installable standalone PWA mode to remove browser address/tab chrome
- Android install prompt plus iPhone Add-to-Home-Screen guidance
- Offline app shell and game-asset caching with network-first updates
- AudioContext-level suspension on maps, dialogue, pause, settings, and app hiding; complete shutdown on menu exit and ending
- Score rewards for rescues, medicine, missions, and hostile positions; penalties for casualties
- Original procedural soundtrack plus separate music, gun-sound, and effects volume controls
- Learning map with Goma, Rutshuru, Kanyabayonga, Lubero, Butembo, Beni, Lake Kivu, Lake Edward, Nyiragongo, and Virunga
- Responsive landscape layout
- Installable web-app manifest
- Non-graphic, scripted historical ending

## Historical and editorial policy

This is a fictionalized educational drama, not a documentary. Dialogue and mission details are invented. Claims about responsibility for contested events must not be stated as settled fact without reliable sourcing and editorial review.

The final sequence follows the UN-reported date and location: 2 January 2014, near Ngadi north of Beni. The UN report described the assailants as unidentified.
