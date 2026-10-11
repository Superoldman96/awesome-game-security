---
title: MotorStorm MV Recomp
kind: entity
topics: [reverse-engineering, game-hacking, graphics-api]
sources:
  - wiki/sources/descriptions/robbe1912__motorstorm-mv-recomp.md
  - wiki/sources/README-categories.md
updated: 2026-10-11
confidence: medium
---

# MotorStorm MV Recomp

**motorstorm-mv-recomp** (robbe1912/motorstorm-mv-recomp) is a **work-in-progress** native recompilation effort for PlayStation 3 *MotorStorm: Monument Valley* that statically translates **PPU and SPU** guest code to run on Windows instead of emulating the Cell console. Listed under README **Cheat / RE Tools** as **source-only** tooling for authorized local reverse engineering—not a finished playable port or redistributable game build. (source: wiki/sources/descriptions/robbe1912__motorstorm-mv-recomp.md)

## Static translation pipeline

Uses **ps3recomp**-style ahead-of-time lifting rather than runtime JIT emulation: CMake build glue, Python analysis and lifting scripts, and a vendored **ps3recomp** runtime extended with high-level emulation for Cell system libraries. Retail binaries, keys, and generated lift output are kept **local** to the researcher’s environment. (source: wiki/sources/descriptions/robbe1912__motorstorm-mv-recomp.md)

## Host runtime and media

The extended runtime targets native Windows with **FFmpeg-backed** media paths and **D3D12** graphics integration alongside Cell library HLE stubs—typical of console-to-PC static port research where GPU and OS services are reimplemented on the host. (source: wiki/sources/descriptions/robbe1912__motorstorm-mv-recomp.md)

## Documented research areas

The repository documents investigation into **Havok** physics assets, **SPURS** job scheduling, **embedded SPU ELF** extraction, and **source-coverage auditing** for lift completeness—useful when labeling which guest subsystems are translated vs still stubbed. (source: wiki/sources/descriptions/robbe1912__motorstorm-mv-recomp.md)

## Stack and audience

Primary languages are **C++** (runner and runtime stubs) and **Python** (tooling and validation checks). Targets **preservationists** and reverse engineers studying PS3 executable structure, static translation pipelines, and console-to-native porting rather than shipping a production build. (source: wiki/sources/descriptions/robbe1912__motorstorm-mv-recomp.md)

## Positioning

Sits beside console static-recompilation research such as [[saturnkit]] (Saturn SH-2→C++), [[mcla-pc]] / [[dead-rising-2-case-zero-xenon-recomp]] (Xbox 360 XenonRecomp), and [[jsrf-recomp]] (OG Xbox XBE recomp) as a **PS3 Cell PPU/SPU translation** lane. Pair SPU-oriented IDA work via [[spu2c]] when analyzing Cell firmware or library code upstream of lift scripts. (source: wiki/sources/descriptions/robbe1912__motorstorm-mv-recomp.md)

## Links

- Repo: https://github.com/robbe1912/motorstorm-mv-recomp [Source-only PS3 MotorStorm Monument Valley static recompilation and translation tooling (ps3recomp-based) for authorized local RE and native Windows experiments]

## Related

[[saturnkit]] · [[spu2c]] · [[mcla-pc]] · [[jsrf-recomp]] · [[static-runtime-evidence]] · [[overviews/reverse-engineering]] · [[overviews/game-hacking]] · [[overviews/graphics-api]]
