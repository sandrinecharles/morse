# MORSE: MOdelling tools for Reproduction and Survival data in Ecotoxicology

Companion R package for MOSAIC website

### Compilation (for command-line users)

- Build from sources (creates vignette and archive)
  `R CMD build mosaic-r`
- Test
  `FIXME`
- Generate documentation
  - under the R interpreter: `roxygen2::roxygenise(".")`
  - for a PDF pversion: `R CMD Rd2pdf morse`
- Check the package
  `R CMD check --as-cran morse_X.X.X.tar.gz`

### Compilation (with RStudio)

- Build from sources: `Build & Reload`
- Test: `Build > More > Test package` (Ctrl + Shift + T)
- Generate the documentation: `Build & Reload or Build > More > Document` (Ctrl + Shift + D)
- Check the package:
  - in `Build > More > Configure Build Tools`, add `--as-cran` in `Check Package -- R CMD check additional` options 
  - `Build > Check` (Ctrl + Shift + E)

