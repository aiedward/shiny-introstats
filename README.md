# Shiny Apps for STAT 2, 20, 21

This is a collcetion of Shiny apps for introductory statistics courses based on the classic textbook __Statistics__ by David Freedman, Robert Pisani, and Roger Purves (2007). Fourth Edition. Norton & Company.

I originally developed these apps for the course [Stat 2](http://gastonsanchez.com/stat2) "Introduction to Statistics" (at UC Berkeley). The main motivation behind the apps is to have teaching materials (in the form of interactive graphics) that I can use during lecture.

The apps are not specifically intended for Stat 2 only. They can be used for any of the introductory Statistics courses at UC Berkeley: STAT 2, STAT 20, and STAT 21. And pretty much in any statistics introductory course in general.


## Running the apps

The easiest way to run an app is with the `runGitHub()` from `"shiny"` package. For instance, to run the app contained in the [regression-galton](/regression-galton) folder, run the following code in R:

```R
library(shiny)

# Run an app from a subdirectory in the repo
runGitHub("shiny-introstats", "gastonstat", subdir = "regression-galton")
```

Another way to run the apps is by [cloning](http://stackoverflow.com/questions/651038/how-do-you-clone-a-git-repository-into-a-specific-folder) the git repository, then use `runApp()`:

```R
# First clone the repository with git. If you have cloned it into
# ~/regression-galton, first go to that directory, then use runApp().
setwd("~/regression-galton")
runApp()
```


## Author Contact

- Gaston Sanchez: [gastonsanchez.com](http://gastonsanchez.com)
- Email: `gaston.stat at gmail.com`
