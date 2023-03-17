# https://stackoverflow.com/questions/42256291/make-execution-stop-on-error-in-rstudio-interactive-r-session

customError <- function()
{

  # cat("|----------- Pausing for error -----------|")
  cat("\n|----------- error -----------|\n")
  stop()
}

# Set the 'error' option to execute our pause function:
options(error = customError)