# spatial-ui

> Experimental 3D spatial interfaces and head-tracked views for future XR devices.

**Status:** Planned — roadmap only. No implementation has been claimed.

## Goal

Place interactive panels in a virtual 3D space and explore view tracking.

## Available / suggested hardware

Mac/PC to start; optional external IMU and headset/display later.

## MVP (first demonstrable result)

1. Build a desktop 3D scene with movable camera and two floating panels.
2. Add ray picking to select a virtual panel with the mouse.
3. Document coordinate frames, camera transforms and interaction assumptions.

## Next milestones

- [ ] Read pose-lab orientation updates to rotate the virtual camera (3DoF).
- [ ] Experiment with stereoscopic projection and frame timing.
- [ ] Study OpenXR runtime/application architecture before attempting standalone headset integration.

## Skills to learn

- 3D scene graphs
- View and projection matrices
- Ray picking
- Stereo rendering, latency and XR tracking

## Connections to other repositories

- **graphics-lab:** reuse standalone rendering techniques.
- **pose-lab:** feeds initial 3DoF head orientation.
- **vision-pose:** add camera-relative positional anchors.
- **sim-engine:** one possible source of simulated world objects.

## Important scope note

A desktop 3DoF prototype is not a full tracked XR headset; display optics, tracking, latency and runtime integration require additional stages.

## Definition of done for MVP

- [ ] A reproducible demo or data output is committed.
- [ ] README explains how to run it.
- [ ] At least one validation result, plot, photo or screenshot is included.

## License

License to be selected before redistributing code.
