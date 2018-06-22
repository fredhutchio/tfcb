Class 1/10 Jupyter, Markdown, Github and version-control (Jesse) Sep 27
==============================================================================

-   Brief introduction:
    -   Course format
        -   This course will introduce students to a selective and
            opinionated set of workflows
        -   Students shouldn't expect to become an expert in any
            specific topic by the end of the course
        -   The goal is to introduce good practices that students should
            continue applying throughout their graduate school and
            beyond
        -   Students will learn a bit of both `R` and `python` -- `R`
            for standard data analysis tasks, `python` for writing more
            complex workflows and to get familiar with typical
            programming features. At the end of the class, we recommend
            adopting one of them depending on analysis needs
    -   Syllabus overview
    -   Homework
        -   Everyone forks a common repository that contain the
            assignments as `assignments/assignment_1.ipynb`
        -   Homework submission will be a pull request by the deadline
        -   Everyone submits their homeworks as
            `assignment_submissions/assignment_1/lastname_firstname.ipynb`
        -   Solutions will be provided at
            `assignment_solutions/assignment_1_solution.ipynb`
    -   Grading
    -   Final project
-   Introduction to Jupyter Notebook environment
    -   How do we set up Jupyter notebooks?
        -   As a Jupyterhub.
            -   This will be easiest if we can ask `scicomp` to set up a
                `jupyterhub` for the course and give us install
                permissions for packages
            -   For example, the current <http://jupyterhub.fhcrc.org>
                does not have `R` kernel and we will have to install it
            -   Every student will need access to `rhino`
        -   As a common python virtual environment in `rhino` that
            everyone can activate, and then `ssh` tunnel from their
            computer
            -   The common virtual environment will obviate the
                necessity for installing packages by each student
            -   This will require introduction to `ssh`, and also
                ensuring that everyone has `ssh`
            -   This is a good compromise between `jupyterhub` and full
                blown self-installation
-   Introduction to Markdown
-   Introduction to Version Control and Github

Class 2/10 Reading data, plotting data, and tidy data (Rasi) Oct 2
==================================================================

-   Use `R` in Jupyter notebook environment
-   Use a cell density and fluorescence plate reader time course
    measurement as an example
-   `read_tsv()`, `write_tsv()`
-   Introduce `tidyverse` packages
    -   Need to show `inner_join` functionality for plotting below
-   Concept of piping: `%>%`
-   `ggplot2()`
    -   aesthetics
    -   geoms
    -   faceting
-   Brief stylistic conventions for `R`
-   Tidy data as applied to biological analysis
    -   Create a `sample_annotations.tsv` file for each experiment
    -   One line per sample
    -   One column per experimental variable (includes both technical
        variables eg. well number, plate number as well as biological
        variables eg. genotype, induction)

Class 3/10 Project organization and introduction to command line (Trevor) Oct 4
===============================================================================

-   Basic Unix commands:
    -   `cd`
    -   `mkdir`
    -   `rm`
    -   `mv`
    -   `ls`
    -   `hist`
    -   Introduce standard Unix conventions for eg. `-h` for help, `-`
        as an option specifier, `*` for wildcard
-   Separating data and code in projects
-   How to document your command-line work in `markdown` files using
    `git-flavored markdown`
-   How to name folders, files, annotations for machine-friendly
    workflows
-   Introduction to `vim`
-   `wget` / `curl`

Class 4/10 Data munging (Rasi) Oct 9
====================================

-   Use `R` Jupyter environment
-   Use flow cytometry data as example
-   Introduce `dplyr`
    -   `select`
    -   `filter`
    -   `arrange`
    -   `group_by`
    -   `summarize`

Homework ideas
--------------

-   `at`, `if`, `all` variations

Class 5/10 Genomic data analysis using Bioconductor (Rasi) Oct 16
=================================================================

-   Continue using `R` Jupyter environment
-   Use RNA Seq differential gene expression as example
-   Introduce `GenomicAlignments`, `GenomicRanges`, `DESeq2`
    -   Use a simplified version of the `DESeq2` vignette:
        <http://bioconductor.org/packages/devel/bioc/vignettes/DESeq2/inst/doc/DESeq2.html>
    -   Might be useful to have `plyranges` to keep a `tidyverse`-like
        workflow

Class 6/10 Advanced command line (Phil) Oct 11
==============================================

-   Customizing command-line using `.bashrc` and `.bash_profile`
    -   `alias`
    -   `PATH`
    -   custom variables
-   Run batch jobs in a cluster using `slurm`
-   Installing programs from source, `make`
-   Symbolic links using `ln`. For eg. link executables to `~/bin` from
    source-installed packages
-   All the above tasks can be used to illustrate shell scripting

Class 7/10 Writing multi-functional programs using Python (Phil) Oct 18
=======================================================================

-   data types: `integer`, `float`, `string`
-   lists
-   variables and constants
-   `for`, `while` loops
-   `functions`
-   code documentation
-   code formatting
-   debugging using `ipdb` and `pdb`

Class 8/10 Using Python for biological analyses (Jesse) Oct 23
==============================================================

-   String analysis and regular expressions
-   File I/O
-   Matplotlib
-   Biopython
-   Importing python modules

Class 9/10 Advanced Python (Trevor) Oct 25
==========================================

-   dictionaries
-   iterators / list comprehension
-   classes
-   Installing packages inside virtual environments

Class 10/10 Scipy-Numpy-Matplotlib (Phil) Oct 30
================================================

-   scipy, clustering, linear modeling
-   numpy
-   scikit-learn
