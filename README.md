# Airsoft Physics Simulator

A small game project built primarily to **study and practice C#** (and game scripting in general).  
The goal of this repository is educational: read the code, experiment with it, and learn by changing things.

> Status: Work in progress / learning project

---

## Why this project exists

- Study **C# syntax, structure, and OOP**
- Practice **gameplay programming patterns**
- Explore **physics-style simulation** ideas (airsoft / projectile behavior)
- Learn by reading real scripts instead of only tutorials

---

## How to use this repo (recommended learning flow)

1. Open the project in your engine/editor (depending on what this repo uses).
2. Start by reading:
   - the entry scene / main bootstrap script
   - player controller scripts
   - weapon + projectile scripts
3. Run the game, then change **one variable at a time** (speed, gravity, fire rate, spread, drag, etc.).
4. Commit your experiments and compare results.

---

## Game mechanics (high-level)

This repository contains mechanics related to an airsoft-style simulator, such as:

- **Player control**
  - Movement and camera/aim control (typical FPS-style setup)

- **Weapon system**
  - Shooting / triggering
  - Fire rate / cooldown logic
  - Reloading (if implemented)
  - Ammo / magazine handling (if implemented)

- **Projectile / BB behavior**
  - Projectile spawning from a muzzle point
  - Travel through space using physics rules (velocity, gravity, drag, etc.)
  - Collision / hit detection (raycast or rigidbody collision depending on implementation)

- **Targets / damage / hit feedback** (if implemented)
  - Detecting hits on objects/targets
  - Applying damage or counting hits
  - Basic VFX/SFX feedback hooks

- **UI & debugging tools** (if implemented)
  - HUD elements (ammo, crosshair, etc.)
  - Debug readouts for physics values

> Note: This section will be updated to exactly match the real implemented mechanics after reviewing the scripts.

---

## Contributing

This is mainly a learning repository, but improvements are welcome:
- bug fixes
- clearer naming
- comments explaining “why”
- small features that improve the learning value (debug UI, test scenes, etc.)
