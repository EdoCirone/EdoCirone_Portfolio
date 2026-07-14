# Edoardo Cirone — Unity Developer (UI/Gameplay/QA)

Rome, Italy — P.IVA available  
Commercial release: **Erase That!** (Android/iOS, later WebGL)

## Highlights
- Unity: UI implementation (uGUI/TMP), UI logic, basic animations/tweening
- Gameplay implementation and iteration (prototype → demo)
- Shaders/VFX in Unity (animated shaders; project-specific)
- Manual QA: feature testing, regression, build verification, structured bug reporting
- Team collaboration and project coordination (PM responsibilities across multiple projects)

---

## Projects

### Doomotica (Solo project) — Unity demo (PC)
- **Build:** https://edoardocirone.itch.io/doomotica-demo
- **Repo:** https://github.com/EdoCirone/Doomotica_Puzzle
- **Video:** https://www.youtube.com/watch?v=8J2VWyn0-yQ

**What I did**
- Full project ownership: gameplay, UI, implementation, integration, bugfixing
- UI end-to-end (menu + in-game): logic and interactions
- Production: build preparation and iteration

**Gameplay**
Point-and-click puzzle. Click objects to trigger actions and solve the correct sequence to clear the level.

**Controls**
- Mouse click (interact)

**Tutorial**
- Level 1 includes on-screen tutorial prompts

---

### Inventory System (Solo project) — Unity demo (technical showcase)

**Repo:** https://github.com/EdoCirone/TestEdoCirone

**What I did**
Full inventory system: fixed-slot capacity, drag-and-drop, item pickup/drop in world
Item effects via ScriptableObject (Heal, Damage, Speed, Strength) — adding a new effect requires no changes to existing systems
Event-driven HUD (health/stats) and UI panels (inventory full, health full, player death), decoupled via a central panel manager
Event-based audio system (UI sounds and gameplay sounds on separate channels)
Animated inventory open/close, cascading slot reveal

**Gameplay** 
Pick up items in the world, manage a fixed-slot inventory, use items with different effects on the player, drag/swap/drop items freely.
Controls

Left click (pick up item / use item in slot)
Drag (move/swap slots, drop outside inventory to release item into world)
I (open/close inventory)

---
### Neon Wavebound (Team project) — Unity demo (PC)
- **Build:** https://reru96.itch.io/neon-wavebound
- **Repo:** https://github.com/reru96/WavesProject

**My contributions**
- Implemented gameplay (development + design iteration)
- Built animated shaders/VFX used in-game
- Added UI text animations (layout handled by another team member)

**Gameplay**
Control wave parameters; color/frequency changes affect interactions with enemies.

**Controls**
- WASD (move/adjust)
- Space (parry) — details in “How to Play” on the main menu

---

### ParasiteProject (Team project) — WIP / Alpha build
- **Repo:** https://github.com/EdoCirone/ParasiteProject
- **Build:** alpha available on request

**My contributions**
- UI end-to-end: layout + logic (main menu + HUD + flows)
- Level design: tilemap + lighting setup
- Game design contribution + project coordination

**Gameplay**
Vampire-survivor-like with a possession twist: you can’t heal, you survive by possessing enemy corpses.

**Controls**
- WASD (move)
- Mouse (aim)
- Auto-shoot
- Space (possession) — alpha build

---

### Erase That! (Commercial release) — Android/iOS (later WebGL)
- **Public page:** https://www.crazygames.com/it/game/eraze-that

**My role**
- Game design, project management and QA support
- Hands-on QA: feature verification, regression checks, release readiness validation

**Gameplay**
Endless runner where you draw the path for the character and erase enemies (touch on mobile, mouse on web).

**Controls**
- Web: Mouse (draw/erase)
- Mobile: Touch
