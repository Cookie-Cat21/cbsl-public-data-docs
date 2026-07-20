# CBSL Public Data

> Unofficial live-probed API documentation.
> **Not affiliated** with the upstream operator. Data may change without notice.

**Tier:** A · **Category:** macro · **Status:** ready

FX/gold scrapes, plrates OPR, eResearch IDs, payments bulletin PDFs.

Pattern siblings: [cse-api-docs](https://github.com/Cookie-Cat21/cse-api-docs) · [ikman-api-docs](https://github.com/Cookie-Cat21/ikman-api-docs)

## Research

Research staged in [ArdenoStudio/lankawa](https://github.com/ArdenoStudio/lankawa) `api-docs/packages/cbsl-public-data-docs/`. Source docs:

- `docs/CBSL_RATES_API_DEEP_DIVE.md`
- `docs/CBSL_PAYMENTS_BULLETIN.md`

## Layout

```
catalog/endpoints.yaml
samples/
scripts/probe.py
scripts/build_site.py
docs/ETHICS.md
examples/
python/
site/
```

## Quick start

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python scripts/probe.py
python scripts/build_site.py
```

## Clients

- Python: [`python/`](./python/) — `cbsl-public-data-docs-unofficial` (`pip install -e .`)
- TypeScript: [`typescript/`](./typescript/) — `@cookie-cat21/cbsl-public-data-docs-client`
- JavaScript (ESM, no build): [`javascript/`](./javascript/) — `client.mjs`

## License

MIT for docs/harness. Upstream data remains subject to upstream terms.
