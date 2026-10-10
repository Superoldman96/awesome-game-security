---
title: kernel-loader
kind: entity
topics: [mobile-security, game-hacking, reverse-engineering]
sources:
  - wiki/sources/descriptions/bmjubairdadu__kernel-loader.md
  - wiki/sources/README-categories.md
updated: 2026-10-10
confidence: medium
---

# kernel-loader

**Kernel Loader** (bmjubairdadu) is a rooted **Android** application (Kotlin, Jetpack Compose) that detects the running kernel and loads a matching prebuilt **`.ko`** module from an over-the-air driver database or embedded fallbacks. It uses **libsu** to run `insmod`, verification, and optional boot-time reload scripts under **Magisk**, **KernelSU**, or **APatch**, including **vermagic** patching and `insmod -f` with **SELinux** handling. Bundled **RT** and **QX** drivers expose a misc device with IOCTLs for cross-process physical memory read/write, module-base lookup, batch reads, and stealth unload, backed by a shared C engine spanning Linux **4.9–6.6**. The app adds SafetyGuard checks, signature/anti-tamper protections, in-app updates, and automated build-request reports when no exact driver exists. (source: wiki/sources/descriptions/bmjubairdadu__kernel-loader.md)

Targets arm64 developers and researchers who need reliable kernel-level memory access for game modding, cheat tooling, and mobile RE—adjacent to integrated driver stacks such as [[integrated-kernel-module]] and vermagic utilities such as [[vermagic]].

## Links

- Repo: https://github.com/bmjubairdadu/kernel-loader (Cheat / Android Kernel Driver development)

## Related

[[integrated-kernel-module]] · [[vermagic]] · [[kernelsu]] · [[magisk]] · [[android-kernel-hacking-toolkit]] · [[overviews/mobile-security]] · [[overviews/game-hacking]] · [[mobile-anti-cheat]]
