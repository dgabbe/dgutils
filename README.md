
<!-- README.md is generated from README.Rmd. Please edit that file -->
### dgutils

My utility functions package, complete with documentation. There are aliases for these bash commands: `cd`, `pwd`, and `env`.

The `note` function to record comments in the history file. Handy to record some thoughts immediately after the execution of some code. Here's an example from my first time using [directlabels](http://directlabels.r-forge.r-project.org/):

``` r
note("Plot labels have wrong color - try explicit aes() for geom_dl")
```

added this to the history file:

    <<<<< Notes to myself >>>>>
    12-May-2016 (Thu) 08:07 @ /Users/examples
    Plot labels have wrong color - try explicit aes() for geom_dl
    <<<<< Notes to myself >>>>>

`theme_dg` gathers up the standard changes I make to ggplot's `theme_bw`.

Install with this R code:

``` r
install.packages("devtools")
devtools::install_github("dgabbe/dgutils")
```

If you like how the bash prompt displays your current working directory, try my [wdprompt](https://github.com/dgabbe/wdprompt) package to emulate this behavior.
