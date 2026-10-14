# Command Line Interface — CIRCULAR_ECONOMY_TOOLS

**Upstream:** https://github.com/nicedoc/circular-economy-tools

## Anticloud CLI

```bash
# Install
pip install anticloud-circular-economy-tools

# Run offline with PAX inference
anticloud-circular-economy-tools --offline --pax-local

# Run with AIOSS logging
anticloud-circular-economy-tools --aioss-log ./ledger.jsonl

# Single binary (after build)
./circular_economy_tools --config config.yaml
```

## Options

| Flag | Description |
| --- | --- |
| `--offline` | Disable all network calls |
| `--pax-local` | Use local PAX inference at 127.0.0.1:11434 |
| `--aioss-log PATH` | Write AIOSS audit chain to PATH |
| `--encrypt` | Enable AES-256 at rest for output files |
| `--gpu` | Force GPU inference |
| `--cpu` | Force CPU inference |
| `--config PATH` | Load configuration from YAML file |
