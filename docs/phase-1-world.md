# Phase 1 — Driving and Karachi Street Foundation

## Design target
A landscape browser game with a real 3D scene, not a top-down or 2D approximation. The player car uses GDevelop PhysicsCar3D. The camera follows from behind, rotates with the vehicle heading and looks slightly ahead.

## Included scene
A compact 3-by-3 street-junction grid. Asphalt road tiles and junction meshes form connected streets. Sidewalk strips, mixed low-rise/commercial building meshes, trees, street lamps and parked vehicles provide depth and scale. Ground collision is provided by a static 3D physics body.

## Validation checklist in GDevelop
- [ ] Project opens without missing-resource warnings.
- [ ] Vehicle rests on the ground without falling through it.
- [ ] W/A/S/D and arrow keys accelerate, steer and reverse/brake.
- [ ] Space triggers the handbrake.
- [ ] Camera remains behind the car and follows its heading smoothly.
- [ ] Mobile steering and speed joysticks both work.
- [ ] Vehicle collides with buildings and parked cars.
- [ ] Check frame rate and asset loading on a mid-range Android phone.

## Next milestone
After the driving/camera pass is stable: replace the compact test grid with a more geographically faithful Saddar/Clifton street network, then add passenger pickup/drop-off, route guidance, fare calculation, the 85/15 driver/platform split, wallet and career progression.
