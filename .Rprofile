# source("renv/activate.R")

.First <- function() {
  dir.create(paste0(getwd(), "/data_raw"), showWarnings = F)
  dir.create(paste0(getwd(), "/data_processed"), showWarnings = F)
  dir.create(paste0(getwd(), "/output"), showWarnings = F)
  dir.create(paste0(getwd(), "/scripts"), showWarnings = F)
  
  if (!("renv" %in% list.files())) {
    renv::init()
  } else {
    source("renv/activate.R")
  }
  
  cat("\nWelcome to your R-Project:", basename(getwd()), "\n")
}
