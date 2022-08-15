# Regression and Other Stories - Data and code

Regression and Other Stories by [Andrew Gelman](http://www.stat.columbia.edu/~gelman/), [Jennifer Hill](https://steinhardt.nyu.edu/people/jennifer-hill), and [Aki Vehtari](https://users.aalto.fi/~ave/) (2020)

[Regression and Other Stories book home page](http://www.stat.columbia.edu/~gelman/regression/)

## Data as `rosdata` R package

For an easier use of data, there is an R package called `rosdata`. You can install it with a command

```
remotes::install_github("avehtari/ROS-Examples",subdir = "rpackage")
```

Then you can access data, for example, as

```
library(rosdata)
data(wells)
head(wells)
```

You can get the list of data sets with
```
?rosdata
```

## Index and notebooks in html

For easier viewing the index and the notebooks in html are available at [avehtari.github.io/ROS-Examples](https://avehtari.github.io/ROS-Examples/).

## `brms` version 

Repo [here](https://github.com/ASKurz/Working-through-Regression-and-other-stories).  