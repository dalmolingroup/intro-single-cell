# Single-cell RNA-seq introduction course

This course covers the basics of single-cell RNA-seq analysis. This material was meant to be continuously improved by the Dalmolin Systems Biology Group students.  

This book is based on the following references:

- The experimental design of single-cell studies: [Tutorial: guidelines for the experimental design of single-cell RNA sequencing studies](https://www.nature.com/articles/s41596-018-0073-y)
- [Orchestrating Single-Cell Analysis with Bioconductor - Basics](https://bioconductor.org/books/3.13/OSCA.basic/);
- [Single-cell best practices](https://www.sc-best-practices.org/preamble.html)
- [Seurat cheatsheet](https://satijalab.org/seurat/articles/essential_commands.html)
- [Introduction to single-cell from Wellcome Connecting Science](https://github.com/WCSCourses/SingleCell_23)
- [SingleR](https://bioconductor.org/books/release/SingleRBook/)
- This awesome playlist on YouTube (in python): [link](https://www.youtube.com/watch?v=cmOlCTGX4Ik&list=PLi1VnGoeDGjuZmB8zJNqpuhGe6Zj7HNYQ)

# Install R packages: 

## Using conda or mamba

Note the `environment.yml` file. It has a list of R packages that are going to be used in this course. Install them by:

```
conda env create -f environment.yml
```

Activate the `intro-single-cell` environment:
```
conda activate intro-single-cell
```

## Or using the `install.R` script

Please note the install.R script. In a R session, run
```
source("install.R")
```

Or run in the terminal:

```
Rscript install.R
```

# Download the data

 In your machine, download [**this**](https://drive.google.com/drive/folders/1RlR_e4JDAPAh3w7028u5Y1CooGaGZMfI?usp=drive_link) folder and extract it to the same location of the course folder.

# Datasets to practice

List of datasets to practice: [*link*](https://gist.github.com/jvfe/85ff3125dd00dbf83b33470f06511096)
