# Kozzy Racing 🏁

**Live dashboard: [stats.kozzy.cloud](https://stats.kozzy.cloud)**

Race telemetry for 1:8 off-road buggy racing at **Omer Ring** (Israeli league):
results, animated lap charts, race replays, driver stats, season champions,
and track records, built from official
[LiveRC](https://israelileague.liverc.com) timing data.

## What you'll find

- **Overview**: track records, league standings, participation and pace trends
- **Events**: every race event since 2017, with weather, class results, race
  replays, lap-by-lap charts, and consistency scores
- **Drivers**: per-driver history, personal bests, podium record, and form
- **Track stories**: photo finishes, charges through the field, iron-man
  attendance streaks, and the champions wall

Only official league rounds count toward rankings and records; one-off events
(cups, invitationals) are shown but clearly marked.

## About this repository

This repo hosts the **built static site** for GitHub Pages. It is republished
automatically: a scheduled pipeline checks LiveRC four times a day and
redeploys whenever a new Omer Ring event is timed. The dashboard source lives
in a private repository.

Results data belongs to the drivers and timing systems that produced it;
this dashboard just makes it fun to look at.
