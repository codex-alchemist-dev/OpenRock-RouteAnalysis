# OpenRock-RouteAnalysis

Escape-route detection and blocker assignment, reusing Terrain's bounded flood-fill - a room's exits and a target's flee routes are literally the same computation, re-centered.

Part of the [OpenRock](https://github.com/codex-alchemist-dev/OpenRock) Minecraft Bedrock mod-packaging ecosystem - a Codex Alchemist project, under Fireball Everything. Consumed as a real git submodule at `libs/route-analysis` in the main OpenRock repo, and directly `npm require`/`import`-able (real top-level CommonJS exports, esbuild-CJS/ESM-interop-compatible) by any mod's own build-time kernel registration or real in-game script.

## License

MPL-2.0. See [LICENSE](LICENSE).
