# StructCI — Flag-Driven, YAML-Gated LLM Control

**Author:** Makoto Suzuki (mlabo / MakotoYoutuber)  
**Status:** Private proof-of-authorship (non-public)  
**First commit (local prep):** 2025-08-11 04:58:55 UTC+09:00

## What this is
A control methodology for LLMs where **flag names encode logic** and a **YAML-based CI** enforces behavior via mode gates and templates.
StructCI treats conversation as a **compiled pipeline**:

- **Modes:** `plan_mode → write_mode → compile_mode`
- **Gates:** syntax/wording/mode gates that fail the build on violation
- **Templates:** ID-mapped WP/Swell blocks & code blocks (template dictionary)
- **EEAT injection:** repeatable stance + evidence discipline baked into the pipeline
- **Determinism-first:** structure > style, with optional “character modules” layered on top

## Why it’s novel (to my knowledge, JST)
- Uses **flag *names*** (not just values) as a logic surface to drive behavior
- Treats LLM output as **build artifacts** (WRITTEN → COMPILED), enabling reproducibility
- Enforces **“compile-only” HTML emission** on trigger (`WPコピペ`) to prevent drift
- Separates **human-facing warmth** from **machine-facing structure**, then recombines

> If you know a prior public implementation that specifically uses **flag-name logic + YAML gates for LLM behavior** with a compile trigger, please cite it.

## Intent
- This repo serves as a **timestamped proof** that the above design existed by the First commit date.
- Publication level: **TBD**. Distribution is not permitted at this time.

## Contact
- X: https://x.com/MakotoYoutuber
- Site: https://mlabo.org/
- Email: mako.sz0001@gmail.com
