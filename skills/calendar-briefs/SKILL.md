# Calendar Briefs Skill

Use this skill when the user wants to:
- a morning brief of the day's family logistics
- an afternoon check for same-day pickup or activity changes
- a weekend preview for the coming Saturday and Sunday
- an ad-hoc answer to "what do I need to know right now?"

## Goal

Surface the calendar and logistics information the household actually needs, at the time of day when it is useful.

## High-priority categories

- pickup and dropoff changes
- same-day activity conflicts
- gear, snacks, uniforms, forms needed today
- weather impact on plans
- school items due soon
- helper or sitter schedule shifts

## Low-priority categories

- unchanged routine items
- distant events that don't need action today
- ambient family calendar noise

## Workflow

1. Read the relevant calendar(s) and any school or activity channels named in `workspace/TOOLS.md` (or `TOOLS.md` under a deployed `workspace/` copy).
2. Determine the brief type from context: morning, afternoon pickup, weekend, or ad-hoc.
3. Extract only actionable items for the relevant window.
4. Produce a compact brief. If nothing unusual is happening, say so briefly rather than padding.

## Brief shapes

- **Morning brief:** key events, pickup and dropoff changes, activity prep, helper schedule, school items due soon.
- **Afternoon pickup check:** same-day logistics only: location changes, gear, forms, snacks, uniforms, delays, overlapping activities.
- **Weekend preview:** Saturday and Sunday activities, sports, classes, outings, prep needs, travel timing, gear, gifts.

## Rules

- Keep briefs compact. One screen of phone text is usually enough.
- If nothing needs action, say so. Do not manufacture content.
- Respect quiet hours and delivery channels from `workspace/HEARTBEAT.md`.
- Flag same-day items clearly.
- Do not leak private child information outside the approved gateway channels in `workspace/TOOLS.md`.

## Good outputs

- "Morning: early dropoff for Sam (8:15), PE clothes needed. Nothing else unusual."
- "Pickup: activity moved from gym to field 2. Bring cleats."
- "Weekend: Saturday 9am soccer (shin guards), Sunday open. No gear to buy."
