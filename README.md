# Browser Game Characters Filament

Filament 5 resource adapter for authorized character administration. Domain progression remains in the Characters core package.

<!-- module-presentation-guide:begin -->
## Presentation architecture and project hosts

- Capability/source key: `liberusoftware/module-browser-game-characters`.
- Actual Composer identity: `liberusoftware/module-browser-game-characters-filament`.
- [Filament capability plan](https://github.com/liberusoftware/documentation/blob/main/projects/browser-game/filament/characters.md) · [Filament standard](https://github.com/liberusoftware/documentation/blob/main/standards/FILAMENT.md) · [Module architecture](https://github.com/liberusoftware/documentation/blob/main/architecture/MODULES.md).

The application owns panel composition, routing, session integration and deployment. This module owns its focused presentation and delegates domain behavior to reviewed public owner contracts. Keep host App aliases, duplicate records and client-only authorization outside reusable package boundaries.

Documented consumer project families:

- [Browser Game](https://github.com/liberusoftware/project-browser-game-laravel-filament): Game worlds, players and community workflows.

Other web, mobile and desktop presentations are listed in the [project catalog](https://github.com/liberusoftware/documentation/blob/main/projects/REPOSITORIES.md). Those skeletons provide starting structures; links do not establish feature parity, compatible releases or completed device/API integrations. Independent presentation packages keep their own Composer, npm or pub metadata.
<!-- module-presentation-guide:end -->
