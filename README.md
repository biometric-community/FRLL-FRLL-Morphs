# FRLL / FRLL-Morphs

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FFRLL--FRLL--Morphs-181717?logo=github)](https://github.com/biometric-community/FRLL-FRLL-Morphs)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://www.idiap.ch/en/scientific-research/data)

**FRLL / FRLL-Morphs** — tbiom catalog packaging for `frll` (face-morph; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/FRLL-FRLL-Morphs
- **Upstream source**: https://www.idiap.ch/en/scientific-research/data
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `frll` |
| Category | `face-morph` |
| Access | `register` |
| Upstream homepage | https://www.idiap.ch/en/scientific-research/data |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Face Research Lab London morphs / related morph sets; check Idiap & paper pages.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/FRLL-FRLL-Morphs.git
cd FRLL-FRLL-Morphs
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_frll.sh
```

Place licensed archives under `projects/datasets/frll/` (gitignored).

## Dataset structure

```text
FRLL-FRLL-Morphs/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://www.idiap.ch/en/scientific-research/data
- Packaging: https://github.com/biometric-community/FRLL-FRLL-Morphs/issues
