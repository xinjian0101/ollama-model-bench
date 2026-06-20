# Contributing to Ollama Model Bench

Read `README.md`, `ABOUT.md`, and `ROADMAP.md` before contributing.

Benchmark changes must be reproducible, clearly defined, and comparable across documented environments.

## Contribution areas

- Benchmark case and result schemas.
- Timing and throughput measurements.
- Resource-observation adapters.
- Warm-up, repetition, and aggregation rules.
- Report generation, fixtures, tests, and documentation.

Use an Issue before changing benchmark methodology, scoring, result formats, or compatibility rules.

Pull requests should include the hypothesis, environment, model version, test case, repetition count, measurement method, expected result, known sources of variance, and documentation updates.

Use clear commit prefixes such as `feat:`, `fix:`, `docs:`, `test:`, `refactor:`, and `chore:`.

Contributors are responsible for correctness, licensing, and review. Do not present results as universal when they depend on specific hardware, settings, or model versions.