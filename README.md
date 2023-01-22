# Cookiecutter Template for a Single Directory Experiment 

This template is bassed on Nobel 2009, the take aways are:

-   Create a directory to carry out a particular experiment.
-   Record every operation that you perform in a README file or driver script.
-   Make the experiment transparent and reproducible by commenting generously and using standard Unix utilities.
-   Avoid editing intermediate files by hand.
-   Store all file and directory names in the driver script.
-   Use relative pathnames to access other files within the same project.
-   Make the script restartable.
-   Create a separate script to summarize the results of the experiment.
-   Follow good practices to make the experiment easily understandable and reproducible by others.

### Notes

- driver script is a `Snakefile`
* This template is suppose to be run inside
the results directory of a project, see:
[cookiecutter-genomics-project](https://github.com/santiago1234/cookiecutter-genomics-project)

### To start a new project, run:
------------

    cookiecutter -c v1 https://github.com/drivendata/cookiecutter-data-science


### The resulting directory structure

The directory structure of your new project looks like this: 

```
├── README.md          <- Main file describing the experiment.
├── Snakefile          <- Snakefile intented to be used as the driver script.
├── scripts/           <- Folder to place scripts.
├── results/           <- Folder to place results (output data e.g. statistics).
├── data/              <- Folder to place input data or intermediate files.
├── plots/             <- Folder to place visualizations and plots.
```

NOTE: Intermediate files should be deleted or placed in a respective scratch folder.
