# Phase 1 — Driving and Karachi Street Foundation

## Current design target

A landscape browser game with a real 3D scene, not a top-down or 2D approximation. The player car uses GDevelop PhysicsCar3D. The third-person chase camera now uses the camera tuning values from GDevelop's official 3D driving starter (closer follow distance, more forward look-ahead and faster rotation response).

## Included scene

A compact 3-by-3 street-junction grid. Asphalt road tiles and junction meshes form connected streets. Sidewalk strips, mixed low-rise/commercial building meshes, trees, street lamps and parked vehicles provide depth and scale. Ground collision is provided by a static 3D physics body.

The player model has been converted to a local white/green taxi livery, with door-side bands and a small roof TAXI sign. It is still based on the supplied sedan mesh, not a manufacturer-exact Corolla or Mehran.

## Important visual-fidelity gap

The current scene is a functional foundation candidate, not a photoreal or geographically faithful Karachi district. It still needs:
- surveyed Saddar and Clifton road/building geometry from OpenStreetMap, with attribution and ODbL compliance;
- higher-detail, properly licensed vehicle and environment models;
- locally recognisable shopfronts, balconies, signboards, road markings and street furniture;
- human pedestrians and moving Karachi traffic.

Do not describe the existing 3-by-3 grid or low-poly meshes as a completed real-world Karachi map.

## Validation checklist in GDevelop

- [ ] Project opens without missing-resource warnings.
- [ ] Taxi rests on the ground without falling through it.
- [ ] W/A/S/D and arrow keys accelerate, steer and reverse/brake.
- [ ] Space triggers the handbrake.
- [ ] Camera remains behind the taxi and follows its heading smoothly.
- [ ] Mobile steering and speed joysticks both work.
- [ ] Taxi collides with buildings and parked cars.
- [ ] Check frame rate and asset loading on a mid-range Android phone.

This checklist has **not yet been runtime-verified**. Behaviour configuration in the project file is not proof of successful gameplay.

## Next milestone

After the driving/camera pass is verified: replace the compact test grid with a more geographically faithful Saddar/Clifton street network, then add passenger pickup/drop-off, route guidance, fare calculation, the 85/15 driver/platform split, wallet and career progression.
