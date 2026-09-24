# SER Stage 7.2.1 — Case Database Housekeeping

Built from the known-good SER Stage 7.2 case database.

## Housekeeping
- Removed the obsolete SAVED LOCAL CASES view; CASE LIST is the single case database doorway.
- Kept demo, local and future imported cases on the same case structure.
- Added structured location parsing behind the single visible LOCATION field.
- Location entry is stored as display text plus CITY / REGION / COUNTRY / COUNTRY CODE when the entry is sufficiently structured.
- Existing local cases are automatically normalised on load.
- Case search also searches the structured location fields.
- Preserved existing custom dropdowns, sounds, date/time formatting, evidence, observations, timeline, analysis, notes and case editing.

## Location entry example
`Portsmouth, New Hampshire, United States`

becomes searchable internally as:
- CITY: Portsmouth
- REGION: New Hampshire
- COUNTRY: United States
- COUNTRY CODE: US

No separate Country field is added to the normal case form.
