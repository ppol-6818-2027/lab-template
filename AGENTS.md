# Instructions for AI agents in this repository

This is a student's lab repository for PPOL 6818, Experimental Research Design and Implementation (Georgetown McCourt School, spring 2027). Labs are individual: this repository is the student's alone. Each week's lab is a folder, `week-01/`, `week-02/` and so on, which the course starts with the week's files; the student's work goes in that folder. `course/project` names the pair's project repository, cloned beside this one in the codespace; never edit it. The course agent, Codex or Claude Code, reads this file. Follow it over your defaults, and follow the week's own instructions where its folder has them.

## Running R

Run every piece of R code in the student's R console, the R terminal in VS Code, through the `r-console` tools, so the student sees it run: `run_in_console` runs the code there and returns what it printed. Give it `folder`, this repository's full path (`/workspaces/<repository>`), so relative paths work. If it says no console is connected, follow what it says (`list_r_sessions`, then `select_r_session`). Never run R through `Rscript`, `R` or the shell.

## Submitting

The student commits each week's folder and pushes it, from VS Code's Source Control view or by asking you to (commit only that week's files, with a short message, then push); a lab counts as done once its work is pushed. Data downloaded for a lab goes in `data/`, which git ignores.
