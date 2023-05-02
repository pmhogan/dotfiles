# Set {devtools} and {usethis} to load with each R session
if (interactive()) {
  suppressMessages(require(devtools))
  suppressMessages(require(usethis))
}

options(
  # Useful {usethis} defaults for package development
  usethis.description = list(
    `Authors@R` = 'person("First", "Last", email = "email", role = c("aut", "cre"))',
    License = "XXX + file LICENSE",
    Version = "0.0.0.9000"
  ),
  usethis.full_name = "First Last",
  usethis.protocol = "https",
  # If using VS code
  # vsc.rstudioapi = TRUE,
  # Helpful warnings when developing packages
  warnPartialMatchArgs = TRUE,
  warnPartialMatchDollar = TRUE,
  warnPartialMatchAttr = TRUE
)
