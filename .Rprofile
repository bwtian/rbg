options(noaakey = "oHswkGjodeAteNDVzdoTqgagICPvWZgh")
.First <- function() {
    cat("Current R.version is:", as.character(getRversion()), "\n")
    cat("Current R.repos is:", getOption("repos"), "\n")
    cat("Current R.Library is:", .libPaths(), "\n")
    cat("Current R.Workdir is:", getwd(), "\n")
    cat("\nSuccessfully loaded .Rprofile at:", date(), "\n")
    if (file.exists(".RData")) load(file=".RData")
}
        options(prompt="R:> ", digits=4, show.signif.stars=FALSE)  ## R Prompt
        ## WARNING!!! This makes your code less portable/reproducible.
        options(stringsAsFactors=FALSE)
        # Paper size
        options(papersize="a4")
        options(max.print = 20000)
        options(help_type="html")
        Sys.setenv(R_HISTSIZE='100000')
        # General options
        options(digits=15)
        options("width"=80)                # wide display with multiple monitors
        options(tab.width = 8)
        options("digits.secs" = 3)          # show sub-second time stamps