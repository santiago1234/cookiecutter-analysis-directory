---
title: {{cookiecutter.keyword_description}}
author: {{cookiecutter.author}}
date: {% now 'local', '%y/%m/%d' %}
---

## Overview

The goal of this analysis is to {{cookiecutter.goal}}.

## Data

A quick description of the data needed to run this analysis.

- `data set 1` TODO: describe
- `data set 2` TODO: describe

NOTE: Temporal data or intermediate files
should be writen to a corresponding scratch directory
or removed after analysis is complete.

## Results

### Results data

* `data 1`, This data set contains (summary stats etc.)
* `data 2`

### Plots

* `plots/plot1` This plot is ..
* `plots/plot2` This plot is ..

## Conlusions

* Conlusion 1
* Conlusion 2


## Next Steps & Ideas for Future Work

* Next I will do ...


## Reproducibility

To replicate this analysis run:

```bash
snakemake -j1 Snakefile
```

