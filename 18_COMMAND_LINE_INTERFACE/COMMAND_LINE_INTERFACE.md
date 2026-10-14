# Command Line Interface — EMOJI_CHEAT_SHEET

**Upstream:** https://github.com/ikatyang/emoji-cheat-sheet

## Anticloud CLI

```bash
# Install
pip install anticloud-emoji-cheat-sheet

# Run offline with PAX inference
anticloud-emoji-cheat-sheet --offline --pax-local

# Run with AIOSS logging
anticloud-emoji-cheat-sheet --aioss-log ./ledger.jsonl

# Single binary (after build)
./emoji_cheat_sheet --config config.yaml
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
