# SQL Visual Course

An interactive, single-file SQL course by **ENG ADAM AJILI** (ENIS GI1).

**Live:** https://3jilou-ui.github.io/sql-course/

16 topics — SELECT, DISTINCT, ORDER BY, aliases, WHERE, IN/BETWEEN/LIKE, NULL + NVL,
string functions, aggregates, GROUP BY, HAVING, CASE, subqueries, set operations, JOIN
and DML (INSERT/UPDATE/DELETE with COMMIT and ROLLBACK).

Every sample table is editable: add or remove rows and columns and the result recomputes
instantly. Each keyword shows *how* it works row by row — the WHERE TRUE/FALSE/UNKNOWN
trace, GROUP BY bucket boxes, join origin badges, NULL padding on outer joins. Every topic
ends with a **SQL playground**: the query is pre-written, you rewrite it and the page runs
what you typed, reporting real Oracle `ORA-` error codes.

## Why this repo

`index.html` is the whole application: 107 KB of HTML, CSS and JavaScript with no build
step, no dependencies, no server and no account. Clone it and open the file — it works
offline, and it is phone-responsive.

## Layout

| Path | What it is |
| --- | --- |
| `index.html` | The course. Also what GitHub Pages serves at the URL above. |
| `.nojekyll` | Tells Pages to serve the file as-is instead of running Jekyll. |

## Versioning

`v1.0` is tagged. Frozen snapshots also live outside this repo, one folder per version,
so a release can never be overwritten by later work.

## Updating

Edit `index.html`, commit, push to `main`. Pages rebuilds within a minute; the URL never
changes.
