# SER Stage 7.2 — Case Database Consolidation v0.72

Built from the verified SER Stage 7.1.3 repair baseline.

## Changes
- Consolidates demo cases and user-created local cases into one CASE LIST.
- Removes the separate user-facing SAVED navigation destination.
- Adds case search across Case ID, location, site, case type, subtype, classification, status, observation and source.
- Adds basic CASE TYPE, STATUS and CLASSIFICATION filters.
- Demo cases and user-created cases use the same list/rendering workflow.
- Existing local case editing, evidence, observations, timeline, analysis, notes, sound and date/time systems are retained.
- Keeps the legacy Saved section internally for compatibility; it is no longer exposed in the main navigation.

## Notes
This is a database/navigation consolidation release only. Stage 8 intelligence features are intentionally not included.
