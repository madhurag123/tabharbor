# Publication record

Copied into `madhurag123/tabharbor` on 2026-10-09 at the owner's request. Original source repositories and remotes were not changed. Existing commit authors, copyright notices, data provenance and third-party licenses are retained; a repository copy does not transfer authorship.

- Source: https://github.com/abhijith-abhii/tabharbor
- Source revision: `521a029aaaeb510e8772936ad740e39c83d8a424`
- Implementation status: implemented; recorded checks passed.
- Publication checks: Local automated checks passed on 2026-10-09. Scope: see the recorded check command and output below.
- This upload does not deploy cloud infrastructure or enable paid integrations.

## Evidence and limitations

Existing screenshots, sample outputs and test reports describe the original implementation and the dates recorded in those files. Links to original CI runs deliberately retain their original account because those runs happened there. They are not claims of new destination-account CI results. Follow the README for installation, dependencies, sample data and limitations. Any new CI results are available in this repository's Actions tab.

Development used substantial AI assistance. Present the work as a project you can run and explain, with its retained provenance, rather than employment experience or verified production adoption.

## Publication check record

```text
✔ groups only eligible domain tabs (0.891667ms)
✔ duplicates preserve first and pinned (0.08325ms)
✔ queries and fragments stay distinct (0.871417ms)
✔ workspace excludes unsupported urls and deduplicates (0.902167ms)
✔ name validation (0.141208ms)
✔ unsafe restore rejected (0.074708ms)
✔ data and file urls excluded (0.047917ms)
✔ empty session rejected (0.04875ms)
✔ popup domain grouping calls Chrome with unpinned tab IDs (3.192834ms)
✔ duplicate preview cannot close tabs until explicit confirmation action (1.134417ms)
✔ duplicate closure rechecks tabs that became pinned (1.509875ms)
✔ saved workspace is persisted and restored in a new window (1.591208ms)
✔ storage failure produces a visible error (0.693667ms)
✔ focus timer is scheduled and cancellation clears its state (11.472833ms)
✔ invalid timer cannot schedule an alarm (0.764875ms)
ℹ tests 15
ℹ suites 0
ℹ pass 15
ℹ fail 0
ℹ cancelled 0
ℹ skipped 0
ℹ todo 0
ℹ duration_ms 62.597375


```
