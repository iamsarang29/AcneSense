# Personal Acne Pattern Finder

A personal project to explore whether changes in acne severity tend to coincide with recorded diet, sleep, and skincare patterns over time.

## Scope

- Personal pattern discovery from one person's longitudinal records.
- Record three daily face views, meal and snack photos, skincare products used, and sleep and wake times.
- Convert images into reviewable, dated observations before analysis.
- Report possible recurring associations with the observations, time window, and uncertainty visible.
- Use dermatology references to explain the state of evidence, not to declare an individual's trigger.

This project is not intended to diagnose acne, recommend medicines, or claim that an association proves causation.

## Current status

This repository currently contains planning materials only. No data collection app or model has been built.

## Design

See [the high-level architecture map](acne-patterns-architecture.svg).

## Reference sources

See [docs/sources.md](docs/sources.md) for the initial curated source list and notes on how reference retrieval should be used.

## Privacy

Do not commit face photos, meal photos, personal health logs, product-use history, credentials, or other sensitive personal data. Keep any future raw data in private, access-controlled storage outside Git. `.gitignore` includes common local data paths as a precaution, but it is not a substitute for checking changes before committing.

## License

No license has been selected. Until one is added, others should not assume they have permission to reuse this repository's original material. Third-party sources remain subject to their own copyright and license terms.
