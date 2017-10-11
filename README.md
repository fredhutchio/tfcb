# Tools for computational biology

Erick note to self: once we decide this is a go, let's book a room!

Length: 10 weeks * 2 sessions * 80 minutes

## Prerequisites:

Either do some online Python (criterion: write python that finds the most common word in a text file?) or take 559


## Course structure
* students read overnight
* instructor takes questions
* individual exercises (as notebooks? repositories?)
* go over answers


## Assignments

* https://classroom.github.com/
* Automated grading with Travis?
* One quiz per week?


## *Week 1* Intro; minimal Git[Hub] (Erick)

* Intro to online resources
* Organization of data (in directories and in tabular format)
* Notebooks
* Git 101 to be able to submit assignments (commit, push); web interface
* GitHub (commenting on commits, various views)
* Markdown
* [Organizing your spreadsheet](http://dx.doi.org/10.7287/peerj.preprints.3183v1)


## *Week 2* Python, Pandas (Jesse)

* Pandas
* Intro to tidy data; data reshaping
* Basic plots with Matplotlib & Seaborn
* Sidney suggests Python cheat sheets https://drive.google.com/drive/u/0/folders/0ByIrJAE4KMTtaGhRcXkxNHhmY2M


## *Week 3* Python (Jesse)

* Read in various file types (Biopython; htseq)
* Which types of data structures are appropriate for what tasks?
* collections module (http://alexmarandon.com/articles/python_collections_tips/)
* Regex (https://regex101.com/; https://pythex.org/)
* PDB debugger
* pep8


## *Week 4* Project organization and shell (Trevor)

* Sidney suggests http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424
* terminal emulators
* In the beginning was the command line
* CodeAcademy command line
* Data vs code
* How to name your files (excellent slide deck: https://speakerdeck.com/jennybc/how-to-name-files)
* git (branching, merging, pulling, conflict resolution, .gitignore), pull requests (GitHub)
* GitKraken?


## *Week 5* Shell (Erick)

* environment variables, e.g. PATH, LD_LIBRARY_PATH; export and which
* .rc files (.bash_profile for mac people)
* what is SSH? Setting up your keys; ssh config (ProxyCommand); ssh forwarding
* remote access, file transfer, and tmux (saving session)
* Pretty much the whole cozy shell course
* getting things set up with Conda (wget to download to grid[b])
* vim!
* diffing and diffing with an editor (ok, vimdiff)


## *Week 6* Python (Phil)

* How to organize a script that accomplishes a task
* OOP; classes
* Running external commands
* Python 2 vs 3


## *Week 7* Python (Trevor)

* pylint
* ipdb (and general debugging -- try/except/assert, check your types, etc.)
* Mutability; Thread pools
* kwargs
* decorators
* Command line interface-- argparse
* Making a package
* Writing documentation for your package (Sphinx/whatever)


## *Week 8* Shell (Erick)

* Cluster interface
* hacking sequence data at the command line? seqmagick for the small stuff, and ??? for the big stuff?
* Shell scripting; history
* Make
* Installation from source: Configure → Make → Make install. Introduction to Make?
* Organization of projects again; scripts should never include absolute paths! (This includes an intro to /usr/bin/env); $(date -I), rename
* parallel / xargs


## *Week 9* R (Rasi)

* Tidyverse (taught using flow cytometry data)
   * Concept of tidy data and annotations
   * Read/write CSV
   * Dplyr verbs - Select, mutate, filter, group_by, summarize, join, spread/gather; pipes[d]
   * GGplot - geoms, faceting


## *Week 10* R + genome annotation (Rasi)

* Bioconductor (taught using RNA seq data)
   * Biostrings - Fasta IO, sequence manipulation, motif counts
   * GenomicAlignments, GenomicFeatures - working with illumina data and genomic annotations
   * AnnotationDbi - Retrieve standardized annotations

