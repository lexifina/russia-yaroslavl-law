<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Yaroslavl Oblast only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-27 06:06 UTC, Yaroslavl Oblast: Official Internet Portal of Legal Information (region76): 9 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Yaroslavl Oblast: Official Internet Portal of Legal Information (region76)](http://publication.pravo.gov.ru/documents/block/region76) | `zakony-<year>/` | daily | 2026-11-27 06:06 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 06:05](checks/2026-11.md#ru-pravo-yaroslavl-20261127t060540z) | pravo-yaroslavl | 9 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-26 06:13](checks/2026-11.md#ru-pravo-yaroslavl-20261126t061303z) | pravo-yaroslavl | 9 | 4 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-yaroslavl-law/compare/913e17aa8537...2a8344c14e3d) |
| [2026-11-25 06:55](checks/2026-11.md#ru-pravo-yaroslavl-20261125t065559z) | pravo-yaroslavl | 9 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 15:04](checks/2026-11.md#ru-pravo-yaroslavl-20261124t150437z) | pravo-yaroslavl | 9 | 2 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-yaroslavl-law/compare/5e9bef818e3c...add7bb118887) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
