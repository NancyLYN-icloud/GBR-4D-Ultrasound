# Minimal Demo

Run the only repository entrypoint:

```bash
python scripts/run_demo.py
```

The script writes one output file:

- `demo/outputs/demo_summary.json`

The demo is synthetic on purpose. It is designed to verify that:

- nonlinear phase canonicalization runs,
- weighted phase sets are constructed,
- the GBR model can optimize against sparse phase observations,
- the repository is executable after cloning.