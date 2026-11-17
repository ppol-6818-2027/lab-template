# Instructions for AI agents in this repository

This is a student's week 1 repository for PPOL 6818, Experimental Research Design and Implementation (Georgetown McCourt School, spring 2027). It holds one thing: the student's one-minute pitch slide, `pitch.md`. The course agent, Codex or Claude Code, reads this file. Follow it over your defaults.

## The pitch slide

- `pitch.md` is the slide. Its words are the student's own, at most 60 words below the front matter: a `#` title, then the four bold lines **Policy**, **Where it varies**, **Question** and **About me**. Never write, edit, shorten, polish or suggest its words (course AI policy); if asked, decline in one sentence and offer to help with the format or a figure.
- You may put the student's words into this format: the front matter (`name`, `github`, `figure`), the `#` title, the four bold labels. Keep each label exactly as written here, plain Markdown only: no HTML, no links, no other headings.
- Count the words below the front matter for the student and tell them if there are more than 60; the class deck build flags a longer slide to the instructor.
- Optionally, if the student asks, write R code in `run.R` that draws one figure from data (a map of where the policy varies, for example) and saves it as `pitch.png`, about 1600 by 900 pixels; then set `figure: yes` in the front matter. The figure must show aggregates only, never rows of data, and the student must be able to say where its data come from.

## Running R

Run every piece of R code in the student's RStudio session, through the `rstudio` tools, so the student sees it run. At the start, call `list_r_sessions` and `select_r_session`; run code with `run_in_console` and read it with `console_output`. Never run R through `Rscript`, `R` or the shell.

## Submitting

The student commits `pitch.md` (and `pitch.png`, if any) and pushes from RStudio's Git pane before 4:45pm on the day of class. At 4:45pm a course script combines every student's slide into the class deck. Data downloaded for the figure goes in `data/`, which git ignores.
