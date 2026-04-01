# CCPI Geolocation Prototypes

**Prepared by:** Sharon Taylor | UX & Product Strategy  
**Date:** April 2026  
**Companion to:** CCPI Geolocation Requirements v2.0

## Files

| File | Description |
|------|-------------|
| `01_phone_prototype.html` | Mobile phone view (iPhone/Android) — Mark's "Projects Near Me" workflow |
| `02_tablet_prototype.html` | Tablet view (iPad/Android tablet) — Split-panel map + project list |

## How to Use

1. Open either HTML file in any modern browser (Chrome, Safari, Firefox, Edge)
2. Use the **step dots** at the top to walk through Mark's 4-step workflow
3. **Click/tap pins** on the map to select different projects
4. **Click the map background** to dismiss the project card

## CCPI Data Fields Represented

The prototypes show actual CCPI project data fields:
- **Project Name** — from CCPI project record
- **General Contractor** — GC assigned to the project
- **Estimated Value** — project value range
- **Stage** — Bidding, Active, Planning, Completed
- **Bid Date** — specific bid deadline date
- **Days Until Bid Close** — countdown for urgency
- **Match Score** — percentage match to user's trade profile
- **Trade Categories** — electrical, HVAC, plumbing, etc.
- **Address** — project street address
- **Document Count** — number of available project documents
- **Street View Preview** — Google Street View of project address
- **Distance** — miles from user's current GPS location

## Pin Color System (from Ingress/Pokémon GO)

| Color | Meaning | Condition |
|-------|---------|-----------|
| Red | Urgent bid | Bid closing within 7 days |
| Gold/Amber | High match | Match score ≥ 70% |
| Green | Active | Currently accepting subs |
| Blue | Planning | Early-stage opportunity |
| Gray | Inactive | Completed or low match |

## Key Layout Differences

**Phone:** Bottom-sheet card overlay (slides up over map)  
**Tablet:** Persistent split-panel (map left, project list/detail right)

## Prototype Phases

These are **Phase 1** prototypes covering:
- V1: Mobile Map Radar
- V2: Project Summary Card
- V3: Project Detail View

Future phases will add V4-V16 (notifications, route planning, territory views, admin tools).
