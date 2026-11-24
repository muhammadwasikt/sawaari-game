# Sawaari — Karachi Taxi Driving Simulator

A native **GDevelop 5.6** project. This repository contains the first vertical slice: 3D driving physics, a third-person chase camera, keyboard and touch controls, and a compact Karachi-inspired 3D street district.

## Open the project
1. Download or clone this repository.
2. Open GDevelop and choose **Open a project**.
3. Select `Sawaari.json`.
4. Keep the `assets/` folder beside the project file; do not move or rename it.
5. Preview the `Game Scene`.

## Controls
- **W / A / S / D** — accelerate, steer, reverse/brake.
- **Arrow keys** — alternate driving controls.
- **Space** — handbrake.
- **Touch devices** — left steering joystick and right speed joystick.

## Phase 1 included
- GDevelop PhysicsCar3D behaviour on the player sedan.
- Third-person camera with smoothed rotation and a forward look offset.
- Desktop keyboard and mobile multitouch input.
- 3D asphalt road tiles, junctions, sidewalks, building meshes, trees, street lamps and parked traffic.
- Directional/hemisphere lighting and a skybox.

## Important scope note
This is the **first driving/environment foundation**, not the finished taxi career game. The current road grid is a Karachi-inspired test district, not yet a surveyed 1:1 OpenStreetMap recreation of Saddar or Clifton. Supplied models are game-ready stylised 3D assets, not photoreal AAA scans or licensed exact Corolla/Mehran models.

Taxi pickup/drop-off missions, fare split, progression, garage, full vehicle roster, pedestrian simulation, dynamic traffic and the full Saddar/Clifton map are deliberately deferred until the driving and camera are stable.

## Asset notes
- Driving base and touch control art: GDevelop official `starting-3d-driving` example.
- Road, building, tree and parked vehicle meshes: GDevelop official `3d-car-coin-hunt` example assets.
- Check upstream asset pages and their current terms before commercial redistribution.
