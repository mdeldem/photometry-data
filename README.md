# photometry-data

## Overview

This repository contains my **personal CCD photometric observations** of astronomical objects.

All measurements have been acquired during my own observing sessions using CCD cameras. The purpose of this repository is to archive these observations, preserve their history using Git, and make them available for future analysis.

<<<<<<< HEAD
## Repository organization

The repository is organized by object category.

```text
photometry-data/
└── objects/
    ├── variable_stars/
    │   ├── Object_1/
    │   ├── Object_2/
    │   └── ...
    └── asteroids/
        ├── Object_1/
        ├── Object_2/
        └── ...
```

Each observed object has its own directory containing:
=======
## Repository structure

```text
photometry-data/
│
└── objects/
    ├── NSV_11142/
    ├── RR_Lyr/
    ├── SS_Cnc/
    └── ...
```

Each directory under `objects/` corresponds to a single astronomical object.

Each object directory contains:
>>>>>>> c7351945a9efddf6a5aee558e85bfcc38f1cc1a8

* a `README.md` describing the object and its main astrophysical characteristics;
* one or more photometric measurement files.

## Data

This repository contains **only photometric measurements**.

It does **not** include:

* raw CCD images (FITS);
* calibration frames (bias, dark, flat);
* image processing scripts;
* photometric reduction software.

## Purpose

The objectives of this repository are:

* archive my personal CCD photometric observations;
* preserve the complete history of observations using Git;
* organize measurements by astronomical object;
* facilitate future scientific analyses.

## License

Unless otherwise specified, all photometric observations contained in this repository were acquired by me and remain my personal work.
