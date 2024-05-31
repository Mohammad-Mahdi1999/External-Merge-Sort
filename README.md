# External Merge Sort in Python

This repository contains a Python implementation of the external merge sort algorithm, which is particularly useful for sorting large datasets that do not fit into memory.

## Overview

The `external_merge_sort.py` script generates a large dataset of random 64-bit integers and sorts them using the external merge sort algorithm. This method is efficient for handling massive amounts of data by dividing it into manageable runs, sorting each run, and then merging them.

## Prerequisites

- Python 3
- NumPy
- Pandas

## Usage

To generate and sort the data, run the following command:

```bash
python external_merge_sort.py
