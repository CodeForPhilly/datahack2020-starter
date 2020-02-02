Opioid Data Hackathon starter scripts
========================================

This repository contains code to help you get started at the Opioid Data Hackathon.

Its goal is to help you follow some data analysis best practices:

* Keeping sensitive passwords off github
* Keeping sensitive data off github

Getting started with R
-----------------------

First, make a copy of this github repository to your laptop.
Make sure to navigate to your copy in Rstudio.

Next, create a new file named `.Renviron`, with the following information.
The easiest way to do this in Rstudio is with the `usethis` package.

```R
# if you don't have the usethis package, uncomment and run the line below
# install.packages("usethis")

library(usethis)
edit_r_environ()
```

From there, Rstudio will open the `.Renviron` file for you to edit.
Enter the following into the file.

```bash
DATAHACK_DB_PASS=<PUT PASSWORD HERE>
DATAHACK_DB_USER=<PUT USER NAME HERE>
DATAHACK_DB_HOST=<PUT HOST HERE>
DATAHACK_DB_PORT=<PUT PORT HERE>
```

During the hackathon we will give you the information to fill in everything starting with `<PUT ...`.


Getting started with Python
---------------------------

First, make a copy of this github repository to your laptop.

Next, navigate to this repository's folder on your laptop, create a new file named `.env`.
Enter the following into it.

```bash
DATAHACK_DB_PASS=<PUT PASSWORD HERE>
DATAHACK_DB_USER=<PUT USER NAME HERE>
DATAHACK_DB_HOST=<PUT HOST HERE>
DATAHACK_DB_PORT=<PUT PORT HERE>
```

During the hackathon we will give you the information to fill in everything starting with `<PUT ...`.


