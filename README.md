# Project Info

This project is built progressively.

At certain points the track reaches a stable musical idea.  
These commits are marked as **BASE N** (e.g. `BASE 1`, `BASE 2`, etc.).

Each **BASE** represents a usable starting point for a track.

If you want to hear the current state of the song without opening Ableton:
* Check `/Exports/track1_BASE_1.wav`. 

This is the **Reference Render** for the current BASE. If you open the project and a plugin is missing or sounding "off," refer to this file to see how it should actually sound.

### How to Fork or Collaborate:
1. **Find a BASE:** Browse the Git tags (`BASE-1`, `BASE-2`, etc.) to jump to a specific BASE version.
2. **Branch Out:** Create a new branch from that BASE.
3. **Evolve:** Take the track in your own direction. Add a new segment, swap the leads, or create an entirely different drop!

---

## DAW
* Ableton Live 12 Suite – Version 12.3.2 (Build: 2025-12-15_bba1e05a87)

---

## Plugins
| Plugin | Version |
| --- | --- |
| Serum 2 | 2.0.23 |
| DS Tantra 2 | 2.02 [x64 VST3] |
| FabFilter Pro-Q 3 | 3.26 (64-bit) |
| FabFilter Saturn 2 | 2.11 (64-bit) |
| Denise Audio Bass XXL | 1.0 |
| LFOTool | 1.762 |
| FX23 PsyScope_PRO | 1.3.10 |
| Cardinal | 26.02 |
| JC-303 | 0.12.3 |

> **Note:** Cardinal is being explored as a possible open-souce alternative to DS Tantra 2.

---

## Git Workflow

This repository uses **Git** together with **Git LFS** for handling large files.

## First Time Setup

Clone the repository and download LFS files:

```bash
git clone <repo-url>
cd <repo-folder>
git lfs pull 
```
