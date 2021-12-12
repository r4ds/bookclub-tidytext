# R4DS Text Mining with R Book Club

Welcome to the R4DS Text Mining with R Book Club!

We are working together to read [_Text Mining with R_](https://www.tidytextmining.com/) by Julia Silge and David Robinson (O'reilly Media, Inc, copyright 2017, 9781491981658).
Join the #book_club-tidytext channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.github.io/bookclub-tidytext/).

## Meeting Schedule

If you would like to present, please add your name next to a chapter using the [GitHub Web Editor](https://youtu.be/d41oc2OMAuI)!

*Cohort 1: (finished!) - Wednesdays, 4:00pm EST/EDT*

<details>
  <summary> Past Meetings </summary>
  
- 2021-09-22: Introduction - Shamsuddeen
- 2021-09-30: Chapter 1: The tidy text format - Kim
- 2021-10-06: Chapter 2: Sentiment analysis with tidy data - Shamsuddeen
- 2021-10-13: Chapter 3: Analyzing word and document frequency - Pavitra
- 2021-11-10: Chapter 4: Relationships between words - Justin D.
- 2021-10-27: Chapter 5: Converting to and from non-tidy formats - Pavitra
- 2021-11-17: Chapter 6: Topic modeling - Justin D.
- 2021-12-01: Chapter 7: Case study: comparing Twitter archives - Shamsuddeen
- 2021-12-08: Chapters 8-9: Case studies - Layla & Justin D.
</details>

<hr>


## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI)
2. Fork this repository.
3. Create a New Project in RStudio using your fork.
4. Install dependencies for this book with `devtools::install_dev_deps()` (technically optional but it's nice to be able to rebuild the full book).
5. Create a New Branch in your fork for your work.
6. Edit the appropriate chapter file, if necessary. Use `##` to indicate new slides (new sections).
7. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
8. Commit your changes.
9. Push your changes to your branch.
10. Open a Pull Request (PR) to let us know that your slides are ready.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.github.io/bookclub-tidytext/).
