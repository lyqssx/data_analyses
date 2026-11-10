# Rhythm usage data dashboard

App Program initiation analysis with model multi-select, official/customized/scene breakdowns, formulas and source field definitions.

- Snapshot: 2026-10-05 through 2026-11-03 (Asia/Shanghai).
- Counts use deduplicated App initiation events, not completed pumping tasks.
- Firmware reference panels are excluded from the official-use share.
- Static aggregate snapshot; no live credentials or runtime data connection.

Open `index.html` or serve this directory as a static site.

## Per-program breakdown

Official and scene programs are expanded per model with UUID-deduplicated start counts, model share, observed names and Program IDs. The model checkboxes, category toggles and search control the table and CSV export.

Actual runtime is unavailable in the audited comparable-model App sources and is displayed as missing. Card-reported configured durations are shown separately as references; they are not substituted for actual use duration.

## Record quality and AIR1 milk actions

`record-quality/index.html` contains a 2026-11-10 re-query of the 2026-10-07–2026-11-05 window: per-user/day timestamp spread, interval CV, concentration signals, five-minute clustering sensitivity, anonymous relative-time examples, and AIR1 record-card Save frequency.

AIR1 Save counts are UUID-deduplicated. These events describe adding or saving milk records; without original/final automatic milk values and a linked record ID, they do not establish correction of automatically measured milk. User-day counts are not distinct users across the full period. The older daily-milk snapshot remains available separately.
