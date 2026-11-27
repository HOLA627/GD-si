# GD Optimizer — 0.1.0


Android-first Geode mod project targeting Geometry Dash 2.2091 and Geode v6.0.0.

## Current scope

- Initial project skeleton
- Android64 CI build workflow
- Load-time log message to confirm the mod is loaded
- No gameplay hooks or optimization features yet


## Build

The GitHub Actions workflow in `.github/workflows/android64.yml` uses the official Geode mod build action and targets Android64. It uploads the built `.geode` artifact when a workflow run succeeds.


## Planned

1. Confirm the mod builds and loads on Android.
2. Add a settings UI/configuration.
3. Implement and test visual-only optimizations individually.

Physics, collision behavior, and gameplay update loops are intentionally out of scope.
