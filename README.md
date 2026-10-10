# College of San Mateo Athletic Center — Pool Relay embed preview

A replica of the [CSM Athletic Center Aquatics pages](https://comfit.smccd.edu/aquatics/) with the lane availability
PDF, the Masters schedule and a paper pool notice replaced by live [Pool Relay](https://www.poolrelay.com) calendars.
Pages are generated: edit `src/<page>.html` and run `python3 build.py`.

| Page | Replaces | Calendar (public token) |
|---|---|---|
| `index.html` | `/aquatics/` | Lane by lane — `gvUr6I1OQGUIk2UtCtcRbE` · Lap Swim week — `WaFSqUVBW2gQpy3ePTq8YL` · Masters week — `UZhdsQ6PG1FQFNfqnd4g2r` |
| `pool-schedule.html` | The Fall lane availability PDF | Both pools, week — `HwsRvPrDRIG35A0tKDcNuN` · lane by lane |
| `bulldogs-swim-school.html` | `/aquatics/bulldogs-swim-school/` | Swim School week — `qlSFalluTlPpu7XVhBJwpY` |
| `bulldog-swim-club.html` | `/aquatics/bulldog-swim-club/` | Bulldog Swim Club week — `0qZMK1UwYNopjAjBXJMM1h` |

## Sources, read 2026-10-10

- **Fall lane availability sheet** (`9.11Lane-Availability-Sheet-Fall-Sem.pdf`, effective 2026-09-11): lap lanes per
  hour in both pools, plus the Masters, Aqua Fitness and Aqua Party schedule on page 2 (unchanged from June).
  Changes from the June sheet: weekday 2–4 PM Olympic lap lanes 10 (Fri 8) → 2; Mon/Wed 10 AM 9 → 3; Fri 10 AM
  20 → 14; Instructional Pool Mon/Wed/Fri 10 AM 6 → closed; Tue/Thu 7 PM 19 → 20.
- **Water polo notice** (`water-polo-notice.jpg`), posted only on paper at the entrance: Olympic Pool impacted
  Wednesdays 9/23 and 10/7 1–5 PM, 9/30 and 10/28 1–6:15 PM. Booked as Collegiate Water Polo on all 20 lanes,
  since the notice doesn't say which lanes stay open.
- Bulldog Swim Club and Swim School schedules, imported in July (no newer versions on the site).

Estimates: which lanes a program uses where the sources give only counts, and one Bulldog block for groups that
practice at the same time.

Not the official College of San Mateo website. Each page says so in a ribbon across the top.
