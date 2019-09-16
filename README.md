# Set up your experiment using `cellpy_cookie_standard`

The main reason for this repository is to let you easily create
a structure for performing a proper `cellpy` session.

The following template is suitable when processing a set of files
using the batch utility.


## Content

```bash

cellpy_project/
└── experiment_001
    ├── batch_file.json
    ├── data
    │   ├── external
    │   ├── interim
    │   ├── processed
    │   └── raw
    ├── out
    │   └── note.md
    ├── notebook: 01_processing.ipynb
    ├── notebook: 02_further_processing.ipynb
    ├── notebook: 03_further_processing.ipynb
    └── notebook: 04_further_processing.ipynb

```

## Notes
