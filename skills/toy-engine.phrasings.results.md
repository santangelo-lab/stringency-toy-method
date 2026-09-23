# Routing results for `stringency-analyze-toy-compare`

One row per phrasing tried in a Claude Science session, against the description in
`stringency-analyze-toy-compare/SKILL.md` at the method tag named. `expect` is from
`toy-engine.phrasings.yml`; `loaded` is what the session loaded.

| date | method tag | phrasing | expect | loaded | note |
|---|---|---|---|---|---|
| 2026-09-23 | v0.1.4 | the `START.md` first message: "I have a small table of measurements on protseq at .../groups.csv. Each row is one measurement with a group (A, B or C), the unit it came from, and a value. ... I want to know whether group A differs from group B. Put the project under .../lane-e." (not in the yml set; closest to positives 7 and 17) | analyze | analyze, plus operator and declare | correct; the two engine skills loading alongside is expected, the analysis skill defers to them |

The twenty positives and ten negatives of `toy-engine.phrasings.yml` have not yet been run.
