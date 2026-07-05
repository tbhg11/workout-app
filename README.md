# Workout App

A single-file gym workout builder. Runs entirely in the browser — no build step, no dependencies.

**Live app:** https://hedwig-workout.netlify.app

## Features

- 9 muscle group buckets (Chest, Back, Shoulders, Biceps, Triceps, Forearms, Legs, Abs, Core)
- 7 equipment filters (Bodyweight, Dumbbells, Barbell, Kettlebell, Cable/Machine, Resistance Bands, Other)
- 750 exercises baked into the HTML — works offline once loaded
- Two modes: Reps (sets x reps with per-set tracking) and Timed (work/rest intervals with auto-advance)
- Timed mode extras: auto-scroll, 5-4-3-2-1 beeps + voice, spoken exercise names at each transition, "Workout Complete" summary, screen wake lock
- Swap button on every card, progress bar, total time estimate

## Editing

Edit `index.html` — it's one self-contained file. Open in a browser to test.

## Data source

Exercise data from [free-exercise-db](https://github.com/yuhonas/free-exercise-db) (MIT), trimmed and re-bucketed.
