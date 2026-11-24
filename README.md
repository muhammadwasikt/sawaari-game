# Sawaari — Karachi Taxi Driving Simulator

A native **GDevelop 5.6** project. The current milestone is the first driving foundation: 3D car physics, a third-person chase camera, keyboard and touch controls, and a compact Karachi-inspired test district.

## Open the project

1. Download or clone this repository.
2. Open GDevelop and choose **Open a project**.
3. Select `Sawaari.json`.
4. Keep the `assets/` folder beside the project file.
5. Preview the `Game Scene`.

## Controls

- **W / A / S / D** — accelerate, steer, reverse/brake.
- **Arrow keys** — alternate driving controls.
- **Space** — handbrake.
- **Touch devices** — left steering joystick and right speed joystick.

## Current Phase 1 work

- GDevelop PhysicsCar3D behaviour on the player car.
- Third-person chase camera tuned to the official GDevelop driving starter's baseline.
- Desktop keyboard and mobile multitouch input behaviours.
- A custom white/green Karachi-style taxi livery with door bands and a roof TAXI sign.
- 3D road tiles, junctions, sidewalks, building meshes, trees, street lamps and parked traffic.
- Directional/hemisphere lighting and a skybox.

## Visual-fidelity status — read before calling this finished

This is **not yet the full realistic game shown in the visual target references**. The current district is still a compact 3-by-3 test grid, not a surveyed 1:1 OpenStreetMap recreation of Saddar or Clifton. The building, road and parked-car assets are stylised/low-poly; the taxi is a livery conversion of the supplied sedan mesh, not an exact licensed Corolla or Mehran model. High-detail Karachi architecture, true street geometry, road markings/signage, pedestrians and moving traffic remain to be built.

## Validation status

The repository contains the native GDevelop project and all referenced local asset files. The driving, camera and mobile controls have **not yet been runtime-tested in GDevelop or on an Android browser in this environment**. Use the checklist in `docs/phase-1-world.md` before treating this milestone as verified.

Taxi pickup/drop-off missions, route guidance, fare calculation, the 85/15 driver/platform split, wallet and career progression are deliberately deferred until the driving and city environment are stable.
