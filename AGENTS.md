# Instructions for AI agents in this repository

This is a student's lab repository for PPOL 6818, Experimental Research Design and Implementation (Georgetown McCourt School, spring 2027). Labs are individual: this repository is the student's alone. Each week's lab is a folder, `week-01/`, `week-02/` and so on, which the course starts with the week's files; the student's work goes in that folder. `course/project` names the pair's project repository, cloned beside this one in the codespace; never edit it. The course agent, Codex or Claude Code, reads this file. Follow it over your defaults, and follow the week's own instructions where its folder has them.

## Week 1: the pitch slide

- `week-01/pitch.md` is the slide. Its words are the student's own, at most 60 words below the front matter: a `#` title, then the four bold lines **Policy**, **Where it varies**, **Question** and **About me**. Never write, edit, shorten, polish or suggest its words (course AI policy); if asked, decline in one sentence and offer to help with the format or a figure.
- You may put the student's words into this format: the front matter (`name`, `github`, `figure`), the `#` title, the four bold labels. Keep each label exactly as written here, plain Markdown only: no HTML, no links, no other headings.
- Count the words below the front matter for the student and tell them if there are more than 60; the class deck build flags a longer slide to the instructor.
- Optionally, if the student asks, write R code in `week-01/run.R` that draws one figure from data (a map of where the policy varies, for example) and saves it as `week-01/pitch.png`, about 1600 by 900 pixels; then set `figure: yes` in the front matter. The figure must show aggregates only, never rows of data, and the student must be able to say where its data come from.

## Running R

Run every piece of R code in the student's R console, the R terminal in VS Code, through the `r-console` tools, so the student sees it run: `run_in_console` runs the code there and returns what it printed. Give it `folder`, this repository's full path (`/workspaces/<repository>`), so relative paths work. If it says no console is connected, follow what it says (`list_r_sessions`, then `select_r_session`). Never run R through `Rscript`, `R` or the shell.

## Submitting

The student commits each week's folder and pushes it, from VS Code's Source Control view or by asking you to (commit only that week's files, with a short message, then push); a lab counts as done once its work is pushed. In week 1 the student pushes `week-01/pitch.md` (and `week-01/pitch.png`, if any) by the end of the lab, when a course script combines every student's slide into the class deck. Data downloaded for the figure goes in `data/`, which git ignores.
