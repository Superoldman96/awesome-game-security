---
title: NullCS
kind: entity
topics: [anti-cheat, game-hacking]
sources:
  - wiki/sources/descriptions/gjones01__NullCS.md
  - wiki/sources/README-categories.md
updated: 2026-10-11
confidence: medium
---

# NullCS

**NullCS** (gjones01/NullCS) is a **research system** that analyzes **Counter-Strike 2** local demo (`.dem`) replays and **ranks players** by how strongly tick-level behavior warrants **human review**, with **supporting evidence tables**—explicitly **not** automated bans or a replacement for production anti-cheat. Listed under README **Anti Cheat / Analysis Framework**. (source: wiki/sources/descriptions/gjones01__NullCS.md)

## Demo parsing and features

Parses offline `.dem` files through **demoparser2** and **awpy** into **per-engagement windows**, then extracts short sequences of **aim, mouse, visibility, and timing** signals at tick granularity for downstream models. (source: wiki/sources/descriptions/gjones01__NullCS.md)

## ML stack

A **convolutional neural network** scores short engagement sequences (aim/mouse/visibility/timing), then **XGBoost** aggregates roughly **450 per-player features** into **lobby-level rankings** with benchmarked review signals. Training, feature engineering, and inference are primarily **Python**. (source: wiki/sources/descriptions/gjones01__NullCS.md)

## UI and workflows

A **Next.js** web UI and **FastAPI-style** worker support upload and **on-machine desktop analysis**—transparent demo screening for analysts, tournament admins, and game-security researchers without mandating cloud replay ingestion. (source: wiki/sources/descriptions/gjones01__NullCS.md)

## Positioning

Complements offline CS2 review benches such as [[cs2-overwatch]] (layered rules, visibility geometry, ML + optional LLM narration), [[yaacs-anticheat]] (demo pitch/yaw telemetry research), and explainable scoring tools such as [[cs2-tracker]] with a **CNN + gradient-boosted tick-feature ranking** emphasis and human-in-the-loop enforcement boundaries. (source: wiki/sources/descriptions/gjones01__NullCS.md)

## Peers

[[cs2-overwatch]] · [[yaacs-anticheat]] · [[cs2-tracker]] · [[cs2guard]] · [[detector-operations]]

## Links

- Repo: https://github.com/gjones01/NullCS [Offline CS2 demo (.dem) pipeline that extracts tick-level aim/visibility features and ranks players with evidence tables for human review—not automated bans]

## Related

[[ai-aimbot-detection]] · [[input-provenance]] · [[overviews/anti-cheat]]
