# daily_logger

A Matrix-styled daily logger for one person. Log anything every day, track how many times a week you do things, get reminders, and see it all as charts. Everything syncs through your own Firebase, with no sign-in.

## Weekly tracking ("how many times this week")
- Give any section a **weekly target**, e.g. Gym 4×/week or Called home 5×/week, under **Edit section → Weekly target**.
- **Count** sections (e.g. "Ate outside", "Coffee") have a **＋1** button. Their weekly total counts every time; other sections count the days you logged them.
- The **Week** page shows a grid of every section × Mon–Sun. Click a cell to log, see totals vs target with "x to go" or "can't make it", streaks of weeks you hit the target, and a times-per-week chart for the last 12 weeks.
- The Today page has a **this week** card with dots for each day.

## Reminders
- **Reminders** page: a time, then every day, weekdays, weekends, chosen days, or once.
- Link a reminder to a section and it can **skip itself if you already logged it today**.
- When it fires you get a sound, an in-app alert (Log now / Snooze 10m / Dismiss), and a system notification once you turn them on.
- **Tasks** with a due date *and time* remind you too.
- **The catch:** a web page can only alert you while it's open, so keep it as a pinned tab or installed app. On your phone, for alerts even when it's closed, tap **＋ Google Calendar** on a reminder (or download all as `.ics`). System notifications need the GitHub Pages version; browsers block them for files opened from disk, but in-app alerts still work there.

## Terminal (Ctrl + K or `:`)
```
money 250 food canteen        sleep 7:30 yesterday      home 6:45pm
gym                           ate 2                     mood 4
todo lab record tomorrow !high          done lab
remind log expenses at 9pm daily        remind gym at 6pm mon,wed,fri
focus 50        countdown PPS exam @2026-12-04        go week
```

## Everything else
- **Sections:** number, duration (`7:30`, `45m`, `2h`), time of day, rating, yes/no, count, journal. Plus categories, quick-add buttons, daily goals, monthly budgets, archive.
- **Charts per section:** daily (7-day average and trend line), weekly, monthly, by weekday, distribution, running total, categories, 12-month heatmap, records.
- **Calendar** to fill in or fix past days, **Insights** (consistency, weekday patterns, "does X affect Y?"), **Focus** timer that logs study time, a **stopwatch** on duration sections, **countdowns**.
- **To-do:** due date and time, priority, lists, repeating tasks, **checklists (subtasks)**, notes.
- Search, backup and restore (JSON), CSV export, themes (Matrix, Cyber, Amber, Red), digital rain, keyboard shortcuts (`1`–`7` pages, `W` week, `R` reminders, `/` search, `N` new section).
