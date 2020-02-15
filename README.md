# apex-quicklook
Repository for the APEX quick look script

The GILDAS/CLASS (https://www.iram.fr/IRAMFR/GILDAS/) macros displayes the spectra and calibration (Trec) for a given scan.

Note that to make it work on your own computer you need to create a few class symbols, or alternatively add an @ before calling the macros (and the minor edits inside the macros).

## Example run at APEX for SEPIA660
```bash
LAS> ql 81026 81025
```

![Example quick look plot](ql_81026.png "ql_81026.png")
