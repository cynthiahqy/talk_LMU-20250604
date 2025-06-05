# Slides for LMU-NYU-Workshop “Making Data Work: Tools for Better Statistical Practice” on June 5-6, 2025, in Munich, Germany.

## Abstract

<!-- TODO: add abstract -->

> Social science research often involves harmonising data from multiple sources. For example, analysts often must resolve differences between country-specific occupation classification standards to compare labour statistics from multiple countries. Harmonised datasets involve both domain expertise and technical data-wrangling skills. Unfortunately, details of the harmonisation logic are often lost in the idiosyncrasies of bespoke data preparation scripts and ad-hoc documentation, making it difficult for others to validate or reuse harmonisation efforts. The {xmap} package addresses these challenges with a new framework and tools for data harmonisation using 'crossmap' tables. The crossmap framework unifies and simplifies the specification, implementation, validation, and documentation of recoding, aggregating and splitting operations. Crossmaps extend existing crosswalk/look-up table approaches to support one-to-many and many-to-many relationships between alternative classification standards, in addition to one-to-one and many-to-one recoding. The package also provides built-in safeguards to avoid data leakage and graph-based methods for standardised documentation.

## Objectives

The main goals for this talk are:

- how crossmaps encode mappings between classification standards
- how to specify crossmaps using the `xmap` object class, and validate mappings between statistical classifications
- how to apply an `xmap` to raw data and produce harmonised data

We will also touch upon:

- how crossmaps can be used to extract mappings from existing data harmonisation scripts