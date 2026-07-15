# steel-string-guitar-opus-48

Steel-string acoustic guitar multisamples — 59 zones covering E2-C6 with medium (MV) and high (HV) velocity layers. Sourced from freepats.zenvoid.org FSS-SteelStringGuitar release 2020-05-21 (originally FlameStudios Seagull Steel String, GPL-3.0 with composition exception).

## About

This repo holds **48 kbps Opus previews** for fast streaming in the web DAW.
Opus at 48k delivers near-CD quality at ~35% the size of MP3 128k.

- **Library**: Steel-String Acoustic Guitar (FSS)
- **Files**: 59 Opus previews (originally WAV, 44.1 kHz 16-bit mono)
- **Bitrate**: 48 kbps VBR
- **Container**: Ogg Opus (.opus)
- **License**: GPL-3.0-with-special-exception
- **Source**: https://freepats.zenvoid.org/Guitar/steel-acoustic-guitar.html
- **Source download**: https://freepats.zenvoid.org/Guitar/FSS-SteelStringGuitar/FSS-SteelStringGuitar-SFZ-20200521.tar.xz
- **Branch**: `main`

## URL pattern

```
https://raw.githubusercontent.com/zulfikarbarbora-outl/steel-string-guitar-opus-48/main/samples/<filename>.opus
```

## SFZ metadata

The original SFZ file is preserved at [`FSS-SteelStringGuitar-20200521.sfz`](./FSS-SteelStringGuitar-20200521.sfz).
The SLDF v3 manifest at `sldf/steel-string-guitar.sldf.v3.json` was built by parsing this SFZ.

## Attribution

- Original samples: FlameStudios (Gary Campion) — Seagull Steel String Acoustic Guitar
- Repackaged by: Roberto (freepats.zenvoid.org) — release 2020-05-21
- License: GPL-3.0 with special composition exception (see [`gpl.txt`](./gpl.txt) and [`readme.txt`](./readme.txt))

## Verification

```bash
python3 verify.py
```

## Index

See [`index.json`](./index.json) for the full file catalog.
