# Cloud Godot Project

Minimal Godot starter project prepared for cloud build and validation.

## What is included

- A runnable `Main` scene and script.
- A Linux export preset for smoke builds.
- A GitHub Actions workflow for headless import checks and export artifact generation.

## Local run

1. Open this folder in Godot 4.x.
2. Run the `Main` scene.

## Cloud workflow

Push to `main` or open a pull request to run CI. The workflow will:

1. Import project assets in headless mode.
2. Export a Linux build.
3. Upload the exported binary as a build artifact.
