# Kilo Client Python v1
> Version: V00.02.00

Python client library for calling Kilo AI from Python applications. Provides functions to run Kilo with messages, start Kilo servers, and check server availability.

Uses subprocess to execute `npx kilo run/serve` commands with configurable parameters. Parses JSON event streams from stdout and extracts text content for easy consumption.

Built with Python 3.9+ using standard library only (subprocess, urllib, json).

## Content Info

conventions: requirements have `### Test` chapters per `reuses/conventions/30_conv_testing_requirements.md`, versioning per `reuses/conventions/10_conv_versions.md`, and README follows `reuses/conventions/40_conv_readme_content.md`.

## Structure

```
v1/
├── src/
│   └── kilo_client.py    # Main client implementation
├── requi/                 # Requirements documents
│   ├── 010_requirements.md
│   ├── 020_kilo_run.md
│   ├── 030_kilo_serve.md
│   ├── 040_cli.md
│   ├── 050_kilo_is_running.md
│   └── 990_comparison.md
└── README.md
```

---

## Change History

| Version | Date | Author | Reason |
|---------|------|--------|--------|
| V00.02.00 | 2026-06-05 | ai(cline) | Add kilo_is_running function |
| V00.01.00 | 2026-06-05 | ai(cline) | Initial README for v1 |