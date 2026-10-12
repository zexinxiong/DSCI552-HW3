# DSCI 552 Homework 3

This repository contains the completed Homework 3 notebook for DSCI 552.

## Structure

```text
DSCI552-HW3/
├── data/
│   └── AReM/
│       ├── bending1/
│       ├── bending2/
│       ├── cycling/
│       ├── lying/
│       ├── sitting/
│       ├── standing/
│       └── walking/
├── notebook/
│   └── Xiong_Zexin_HW3.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## Run locally

Use Python 3.10 or newer.

```bash
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r requirements.txt
jupyter lab notebook/Xiong_Zexin_HW3.ipynb
```

The notebook uses paths relative to the repository root and locates the data in
`data/AReM`. Before submission, run all cells from a clean kernel and confirm
that every cell completes without an exception.

## Data

The AReM data set contains 88 recordings from seven activities. The original
files are retained unchanged. The notebook documents and handles minor source
format inconsistencies while loading the data.

