# tutorials281
Learnr tutorials for UNC's Poli 281 Class

## Installation and Running Tutorials
Running these tutorials locally requires installing and loading the `learnr` package, with the following lines of code.

```{r}
install.packages("learnr")
library(learnr)
```

To then manually install the most recent version of the `tutorials281` package, you must first ensure you have the latest version of `devtools` installed:

```{r}
install.packages("devtools")
library(devtools)
```
Then, run the following code:

```{r}
devtools::install_github("lucy-martin/tutorials281")
library(tutorials281)
```
You can then run individual tutorials on your local machine by running the following line of code:

```{r}
learnr::run_tutorial("TUTORIAL_NAME", package = "tutorials281")
```
Where TUTORIAL_NAME corresponds to the name of each subfolder within the `inst` directory. They are as follows:

* week1_tutorial
* week2_tutorial
* week3_tutorial
* week4_tutorial
* week5_tutorial
* week6_tutorial
* week7_tutorial

