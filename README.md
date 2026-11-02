# geoskill-watershed-delineation

> Automated watershed delineation from DEM. Computes D8 flow direction, flow accumulation, delineates watersheds from outlet points, extracts stream networks, and generates statistics. Use when the user wants to delineate a watershed, compute flow accumulation, extract streams, or analyze hydrological characteristics from a DEM.

See [SKILL.md](SKILL.md) for full usage, inputs and outputs.

## Quick start

```bash
python scripts/watershed_delineation.py --dem dem.tif
python scripts/watershed_delineation.py --dem dem.tif --outlet-row 50 --outlet-col 60
python scripts/watershed_delineation.py --dem dem.tif --stream-threshold 50
python scripts/watershed_delineation.py --synthetic --output-dir ./out
```

## License

MIT
