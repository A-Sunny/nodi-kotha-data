# Nodi-Kotha Data

This repository contains the public JSON-based river dataset powering the Nodi-Kotha Android application.

## About Nodi-Kotha

Nodi-Kotha is a lightweight bilingual digital river atlas of Bangladesh designed for Android devices. The project focuses on:

- Interactive river visualization
- Bangla and English support
- Offline-first architecture
- Low-end device optimization

## Repository Purpose

This repository acts as a static cloud API using GitHub Pages.

The Android application fetches river metadata and optimized geometry data directly from these JSON endpoints.

---

# Data Structure

## Master River List

```text
/api/list.json
    |-rivers
        |-padma.json
        |-meghna.json
        ..... ```

---

## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

This dataset and its static API endpoints are licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)** license. 

### What this means:
* **Attribution:** You must give appropriate credit to the **Nodi-Kotha** project if you use this data.
* **Non-Commercial:** You cannot use this dataset, or endpoints generated from it, for commercial applications or monetary gain.
* **Share-Alike:** If you modify, extend, or build upon this data, you must release your dataset under the exact same license terms.
