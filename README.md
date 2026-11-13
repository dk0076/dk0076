# Andrew King

Statistics and Data Science at Cal Poly San Luis Obispo. I build the analytics
tools Cal Poly Women's Volleyball uses on match day, in R, Shiny and plain
JavaScript.

Most of what I work on starts the same way: a coach asks a question that the
box score cannot answer, and the data needed to answer it is sitting in a
VolleyStation or DataVolley file that nothing else reads.

### What I work on

- **[cal-poly-scout-app](https://github.com/dk0076/cal-poly-scout-app)** —
  live scouting app in R and Shiny. Parses `.vsm` and `.dvw` match files into
  attack, serve, reception, setter and rotation breakdowns for both teams, and
  serves them from a coding laptop to bench tablets over the venue router.
  Ships as a Windows executable so the staff launches it with one double-click.
- **[ncaa-volleyball-analytics-2](https://github.com/dk0076/ncaa-volleyball-analytics-2)** —
  serve quality modeling over 87,219 NCAA serves, three chained XGBoost
  classifiers into one receiver-adjusted server rating, stored in DuckDB.
- **[dvw-vsm-montage](https://github.com/dk0076/dvw-vsm-montage)** — cuts video
  clip reels in the browser straight from coded match files, no render queue.

### How I work

Any statistic I ship is checked against VolleyStation's own output for the same
file before a coach sees it. Agreeing to three decimal places is the bar;
looking about right is not.
### Tools

R (Shiny, data.table, Quarto) · SQL (DuckDB) · Python · JavaScript · Git

Some work here is AI assisted. The design decisions, the stat definitions and
the validation against VolleyStation are mine.
