# Tasks

### Task 1: Instructions

  * Load in the `tidyverse` package.
  * Read in `datasets/yearly_deaths_by_clinic.csv` using `read_csv` and assign it to the variable `yearly`.
  * Print out `yearly`.

### Task 2: Instructions

* Use `mutate` to add the column `proportion_deaths` to `yearly` calculated as the proportion of `deaths` per number of `births`.
* Print out `yearly`.

### Task 3: Instructions

* Use `ggplot` to make a line plot of `proportion_deaths` by `year` with one line per clinic.
* The lines should have different `color`s.

### Task 4: Instructions

* Read in `datasets/monthly_deaths.csv` and assign it to the variable `monthly`.
* Add the column `proportion_deaths` to `monthly` calculated as the proportion of `deaths` per number of `births`.
* Print out the first rows in `monthly` using the `head()` function.

### Task 5: Instructions

* Make a line plot of `proportion_deaths` by `date` for the `monthly` data frame using `ggplot`.
* Use the `labs` function to give the x-axis and y-axis *any* prettier labels.

### Task 6: Instructions

* Add a `TRUE`/`FALSE` column to `monthly` called `handwashing_started` which is `TRUE` for `date`s where obligatory handwashing was enforced.
* Make a line plot of `proportion_deaths` by `date` for the `monthly` data frame using `ggplot`. Make the color of the line depend on `handwashing_started`.
* Use the `labs` function to give the x-axis and y-axis *any* prettier labels.

### Task 7: Instructions

* Use `group_by` and `summarise` to calculate the `mean` proportion of deaths before and after handwashing was enforced.
* Put the resulting table into `monthly_summary`.

### Task 8: Instructions

Use the `t.test` function to calculate a 95% confidence interval around how much dirty hands increases `proportion_deaths`.

### Task 9: Instructions


Given the data Semmelweis collected, is it `TRUE` or `FALSE` that doctors should wash their hands?
