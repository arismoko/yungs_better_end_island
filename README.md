# YUNG's Better End Island for Sunrise

The structure templates of YUNG's redesigned End island arena, for placing in the End.

A port of [YUNG's Better End Island](https://github.com/YUNG-GANG/YUNGs-Better-End-Island) by YUNGNICKYOUNG and Acarii to [Sunrise](https://playsunrise.net) (Minecraft Java 26.3). It is a content mod: the original's structures, templates, loot tables and strings, upgraded to 26.3, with no code. The 26.3 carry is by AdLf0208 ([AdLf0208/yungs_better_end_island](https://github.com/AdLf0208/yungs_better_end_island)); this fork moves it to Sunrise.

## What it adds

- The 41 structure templates of the redesigned End arena (the central tower, the pillars and their cages), placeable with `/place template betterendisland:<name>`.
- The dragon-immune block tag for the arena's blocks, and the mod's strings.

## Differences from the original

- The End is not rebuilt on its own: the original replaces the spawn platform, the pillars, the exit portal and the gateways through Java code, and this port carries only the templates.

## Building

With the Sunrise mod tool (`cargo sunrise-mod`, from the Sunrise SDK):

```sh
cargo sunrise-mod check
cargo sunrise-mod build    # target/sunrise-mod/betterendisland.smod
```

This version is made for the Sunrise Dev build `dev-2026-11-22-7cfdf81`.

## Licence and credits

YUNG's Better End Island is by YUNGNICKYOUNG and Acarii (https://github.com/YUNG-GANG/YUNGs-Better-End-Island). Its structures, templates, loot tables and strings are theirs and are used here under the **GNU LGPL v3.0 only**, the original's licence; `LICENSE` holds the text.

Carried to Minecraft 26.3 by AdLf0208 ([AdLf0208/yungs_better_end_island](https://github.com/AdLf0208/yungs_better_end_island)), and ported to Sunrise by arismoko. This port is distributed under the same licence.
