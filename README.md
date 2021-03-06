Hw09-aleurcelay
================

Hello\! :raising\_hand:

This is the repository of my Homework 9: Automating Data-analysis
Pipelines for the [STAT547](http://stat545.com) course. Instructions for
this assignment can be found
[here](http://stat545.com/Classroom/assignments/hw09/hw09.html)

For this assignment, I modified Jenny Brian’s original [make
activity](https://github.com/STAT545-UBC/make-activity) by adding new
files to the pipeline.

## New/modified files

  - :star2:[Makefile](Makefile): I modified the Makefile to add the new
    files to the pipeline that generate the new plot, the new report,
    the modified README, and to create subdirectories to store the
    images (plots), the data outputs (csv files) and the source data
    (words.txt file). You can test it by downloading this repo as a ZIP
    and then running `make clean` and `make all`.
  - [letteres\_freq.R](./R/letters_freq.R) outputs a tsv file containing
    the frequencies of letters in the `words.txt` file.
  - [report\_letter\_freq.rmd](report_letter_freq.Rmd) which outputs the
    [report\_letter\_freq PDF](report_letter_freq.pdf).
  - [README.rmd](README.rmd) which generates the README.md file with the
    Frequency of letters plot:

![Frequency of letters](./images/letters_freq.png)
