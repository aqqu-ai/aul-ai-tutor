# aul-ai-tutor

Autonomous offline AI tutor device for AI literacy in remote classrooms (local-first).

## What it is
A local-only classroom device that runs an on-device LLM and delivers guided lessons without requiring internet connectivity.

## Key capabilities
- Offline-first learning mode (no internet required)
- Local LLM runtime (on-device inference)
- Lesson engine + classroom safety controls
- Reproducible “golden image” builds for consistent deployments

## Repository layout (initial)
- `image/` – golden image build scripts and artifacts
- `device/` – device services, configs, provisioning
- `runtime/` – local LLM runtime wrappers / tooling
- `curriculum/` – lesson packs and content (non-sensitive)
- `tools/` – utilities (build, flash, validate)
- `docs/` – architecture notes and operational guides

## Quick start (placeholder)
1) Build image: `tools/build-image.sh`
2) Provision device: `tools/provision.sh`
3) Run tutor mode: `device/start.sh`

## Roadmap
- [ ] Golden image v1 (reproducible build)
- [ ] Tutor mode MVP (lesson packs + safety)
- [ ] Fleet provisioning (offline updates, diagnostics)
- [ ] Hardware profiles and benchmarks

## License
See `LICENSE`.
