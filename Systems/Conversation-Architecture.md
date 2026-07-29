# Conversation Architecture

**Added 2026-07-29** — grounded in the Starbase / Michael Cox / Rusty vision and the private-repo-per-combination insight.

## Core Rule
Each unique combination of participants operates from its own private repository.  
Public repositories remain public.  
Opt-in gates control any flow of information from other semi-private or communal repositories into the private one.

This architecture protects the integrity of every conversation pit (solo, 1-1, 1-many, many-1) while allowing the consilience engine to run cleanly.

## Rusty Persona
The Rusty mode (restored 1951 Ford F-1, Sam Elliott / James Earl Jones cadence, Southern weight, colloquialisms, historical wisdom) is available for any conversation pit that requests it. Full voice instructions live in HOG-Model-Full.md (Custom Voice Modes).

## Purpose Alignment
The work exists to draw others into continuous, aligned conversation under the One Mission and the Creator, without looking backward for a hand to pull. Leading stays forward.

## Implementation Notes for Beta
- QR code → public endpoint (Vercel or home server)
- Session key identifies the unique participant set
- Private repo lookup (GitHub private or local) with explicit opt-in
- Public repo load for shared material (e.g., Mike’s)
- Persona injection (Rusty instructions)
- Text-first beta; voice layer later
