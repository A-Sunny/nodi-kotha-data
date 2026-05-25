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
        .....

