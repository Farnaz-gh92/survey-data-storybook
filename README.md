# NHANES visual storybook

This repository contains my Week 3 and Week 4 BIOS 640 practice work. I use a
cleaned NHANES dataset to explore sample composition, blood pressure patterns,
and several ways to present the same analysis for different readers.

## Repository guide

- `analysis/week3/` contains the Week 3 R Markdown report.
- `analysis/week4/` contains the interactive report, dashboard, and table report.
- `datasets/` contains `diet.csv` and a compressed copy of the cleaned NHANES
  data. Extract `cleaned_NHANES.zip` in that folder before knitting.
- `graphics/` contains figures created from the Week 3 analysis.
- `deliverables/` contains the rendered HTML and PDF documents.
- `citations/` contains the bibliography used in the table report.

## Week 4 work

- [Interactive data showcase source](analysis/week4/interactive_data_showcase.Rmd)
- [NHANES sample dashboard source](analysis/week4/sample_dashboard.Rmd)
- [Wave profile table source](analysis/week4/survey_summary_tables.Rmd)
- [Wave profile table report](deliverables/tables/farnaz_wave_profiles.pdf)

The two rendered HTML files are kept in the separate local Farnaz project
because the self-contained files are several megabytes each. They can be
recreated by knitting the two HTML source documents above.

The reports use project-relative paths through the `here` package. Open
`NHANES-Story-Farnaz.Rproj` before knitting any source file.

