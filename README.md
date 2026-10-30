# Native Game Ports for iOS & Apple Silicon Mac

Community **native ARM64 game-port source and porting research for iPhone, iPad and macOS**. Projects use platform-service adaptation, static rewriting/recompilation, Metal graphics, native host integration, or selected-function recovery. Each repository records its own verified scope and remaining work.

| Game | Public source | Current scope |
| --- | --- | --- |
| Grand Theft Auto V / GTA 5 | [gta-v-native-ios](https://github.com/slavich33/gta-v-native-ios) | Experimental iOS/macOS native host; gameplay baseline observed, performance/artifacts/freezes remain open |
| Diablo II: Resurrected / D2R | [diablo-2-resurrected-native-ios](https://github.com/slavich33/diablo-2-resurrected-native-ios) | Native port fork; Reimagined API/TCP components verified, actual ladder gameplay and server characters pending |
| Zelda: Tears of the Kingdom & Breath of the Wild | [zelda-totk-botw-native-ios](https://github.com/slavich33/zelda-totk-botw-native-ios) | Native Mac/iPhone/iPad fork, build/install helpers, shader-seed and frame-pacing changes |
| Castlevania: Belmont’s Curse | [castlevania-belmonts-curse-native](https://github.com/slavich33/castlevania-belmonts-curse-native) | Paused native Mac loading-screen research; menu/gameplay and iPhone operation unverified |
| Songs of Conquest | [songs-of-conquest-native-ios-tools](https://github.com/slavich33/songs-of-conquest-native-ios-tools) | Unity/C# adaptation tools and compilation checkpoint; no verified iPhone gameplay |
| The Witcher 3: Wild Hunt | [witcher-3-native-research](https://github.com/slavich33/witcher-3-native-research) | Selected ARM64 function models and differential tooling; no complete engine or app |

## Shared framework

[nxnative](https://github.com/slavich33/nxnative) — Nintendo Switch NSO rewriting, Horizon HLE, NVN-to-Metal and native IPA build tooling. Game-specific work may additionally use MacNativeGames, D2R Mobile, Ryujinx shader tooling, Unity or Ghidra; retained notices and provenance are in each repository.

## Source and build boundaries

These repositories publish port/adaptation source, research models, tools and non-secret fixtures. Supply your own authorized game files and signing configuration. Game executables/assets, full recovered commercial game code, extracted shader dumps, caches, saves, accounts, credentials and signed apps are outside the public snapshots. A research repository is not evidence of a playable game.

## Contributing

Use the relevant repository’s status/build guide and issue tracker. Include the source revision, platform, exact reproduction steps and a redacted diagnostic summary. Avoid posting private game files, signing material or account/session data.

## По-русски

Исходники нативных портов и инструменты исследования игр для iPhone / iOS и Mac на Apple Silicon: GTA V, Diablo II Resurrected, Zelda TOTK / BOTW, Castlevania, Songs of Conquest и Ведьмак 3. Готовность различается: точный статус указан в таблице и README каждого проекта. Оригинальные игры, ключи и сохранения не распространяются.
