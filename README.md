# OpenPSM Benchmark: An Open Evaluation Dataset for AI in Process Safety Management

**Version:** 0.1 | **License:** CC BY-SA 4.0

## Overview

OpenPSM Benchmark is the first open-source evaluation dataset for assessing AI system performance on industrial Process Safety Management (PSM) tasks.

This dataset contains **50 expert-authored scenarios** covering five core PSM task categories:

1. **RAGAGEP Gap Identification** (15 scenarios)
2. **PHA Question Answering** (10 scenarios)
3. **Standards Cross-Reference** (10 scenarios)
4. **Compliance Risk Scoring** (10 scenarios)
5. **OSHA Citation Prediction** (5 scenarios)

## Quick Start

```bash
python evaluate.py --predictions predictions.json --benchmark benchmark_v0.1.json
```

## Authors

Timothy Porritt, Porritt Inc. (Salt Lake City, UT)

## Citation

```bibtex
@dataset{openpsm2026,
  title={OpenPSM Benchmark: An Open Evaluation Dataset for AI in Process Safety Management},
  author={Porritt, Timothy and Porritt, Inc.},
  version={0.1},
  year={2026},
  license={CC BY-SA 4.0},
  url={https://github.com/freakp69/openpsm-benchmark}
}
```

Full documentation and detailed README available in the repository.

---
**Version 0.1 Release Date:** April 5, 2026
