# falden-fixture-pack

This repository is where the falden-fixture-pack will be published. It is not published yet, so the pack cannot be downloaded, verified or graded today.

The pack will be a graded test corpus for tools that claim to tell you whether a merged code change was approved by someone independent of the person who wrote it. This repository exists before the pack so that links to it resolve now.

## License

When the pack is published here, `REUSE.toml` will name the license of each file. These are the terms it will carry, and `LICENSES/` holds their texts now. Falden, Inc. holds the copyright in what it licenses.

- MIT: the code, `bin/`, `adapters/`, `conformance/`, `build/`, `schema/` and the workflow in `.github/`.
- CC BY 4.0: the data and the docs, `cases/`, `register/`, `materialized/`, `docs/`, every page here (`*.md`), `pack.json`, `MANIFEST.sha256` and `CHANGELOG.lock.json`.
- Quoted, not licensed: the recorded responses under `captures/`, what GitHub served, published as evidence. Falden, Inc. does not license them.
- CC BY 4.0: what Falden's own tooling writes among the captures, where a capture holds it: `captures/data/manifest.json`, `captures/data/snapshots/SNAPSHOTS.txt`, `captures/data/snapshots/ids.env`, `captures/data/acquisitions/*.json` and `captures/data/includes/*/manifest.json`. Values these records copy from GitHub's answers, its header values, URLs and a failed read's error message, are GitHub's; Falden, Inc. licenses the records, not those values.

This README is CC BY 4.0.
