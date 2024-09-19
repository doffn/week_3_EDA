# Telecom Network Data Analysis

## Overview

This Python script analyzes telecommunication network data to provide user-level insights. It processes a dataset containing various metrics about network usage and aggregates this information on a per-user basis.

## Features

- Aggregates data per user (identified by MSISDN/Number)
- Calculates key metrics:
  - Number of xDR sessions per user
  - Total duration of sessions
  - Total download volume
  - Total upload volume
  - Total data volume (download + upload)

## Prerequisites

- Python 3.x
- Pandas library

## Notebooks

The notebook can be found inside the notebook directory.

## Dataset

The script expects a DataFrame (`df`) with the following key columns:

- 'MSISDN/Number': Unique identifier for each user
- 'Dur. (ms)': Duration of each session in milliseconds
- 'Total DL (Bytes)': Download volume in bytes
- 'Total UL (Bytes)': Upload volume in bytes

Other columns present in the dataset include various network performance metrics, device information, and application-specific usage data.


