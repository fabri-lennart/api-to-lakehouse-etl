## Pipeline Architecture

![Fabric Pipeline](Images/pipeline.png)

---
Simple end-to-end data pipeline built with Microsoft Fabric.

## Overview

This project extracts product data from a public API, performs basic transformations, and loads the results into a Fabric Lakehouse.

## Tech Stack

* Python
* Pandas
* Requests
* Microsoft Fabric

## Pipeline

API → JSON → Data Cleaning → DataFrame → Lakehouse (Files)

## Project Structure

notebooks/   Fabric notebooks
src/         Python scripts
data/        Sample outputs

## How to Run

1. Open the notebook in Microsoft Fabric
2. Attach a Lakehouse
3. Run all cells

## Output

/lakehouse/default/Files/products.parquet
---

This project is intended for learning and practicing data engineering workflows.
