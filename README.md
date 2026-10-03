# Mini Data Analysis: Deliverable 1

This repository contains my first mini data analysis. It explores two data sets (the Great NYC Squirrel Census and Rolling Stone's "500 Greatest Albums of All Time") and then focuses on the Rolling Stone data to ask whether an album's release year is related to its Spotify popularity, and whether that differs by the artist's gender.

## Files in this repository

- `MiniDataAnalysis1.qmd`: the Quarto source file with all of my code and written answers.
- `MiniDataAnalysis1.md`: the rendered report (viewable directly on GitHub).
- `RollingStone500.csv`: the Rolling Stone albums data used for the analysis.
- `squirrel-data.csv`: the squirrel census data explored in Task 1.
- `mini-data-analysis.Rproj`: the RStudio project file.
- `.gitignore`: files that Git should ignore.
- `README.md`: this file.

## How to explore this repository

To read the results, open `MiniDataAnalysis1.md` on GitHub. To reproduce the report, clone the repository, open `mini-data-analysis.Rproj` in RStudio, install the packages used at the top of the `.qmd` (`tidyverse`, `moderndive`, `janitor` and `diversedata` from GitHub via `pak::pak("diverse-data-hub/diversedata")`), then open `MiniDataAnalysis1.qmd` and click Render. The two CSV files must stay in the same folder as the `.qmd`.

1. I missed the class where this assignment was explained, so I asked Claude
   to walk me through the steps: how the .qmd template works, what each task
   asked for, and how to set up a GitHub repository and commit and push from
   RStudio.
   
2. My first Git commit failed with "nothing added to commit". Claude explained
   that I had to tick the boxes under "Staged" first.