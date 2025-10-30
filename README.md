# agile-5g-docsync

Tiny helper to **compare two srsRAN/Open5GS-style YAML configs** and auto-append a
human-friendly entry to `docs/changelog.md`.

This is inspired by the need in agile 5G projects to reduce **documentation fragmentation**
and to capture **parameter changes per sprint** (PLMN ID, bands, gains, IPs).

## Install
```bash
pip install -r requirements.txt
```

## Run
```bash
python -m src.docsync     --old configs/gnb_v1.yaml     --new configs/gnb_v2.yaml     --out docs/changelog.md     --sprint "Sprint 3"
```
Dr. Ibrahem Almansour
