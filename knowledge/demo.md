# Demo geometry

The manual `Burr incomplete geometry proof` workflow checks Jubilee's camera
calibration tool. It is expected to fail on unresolved geometry, with
**INCOMPLETE** and pair reasons in the summary. Its unmodified source and
CC-BY-4.0 attribution are in `licenses/Jubilee-CC-BY-4.0.md`.

The repository carries two real corpus assemblies: Voron's Manta mount and
openAMR's cover assembly, with their upstream source and licenses. Manta is a
complete pass. The larger cover illustrates real interference and unresolved
small geometric features; checking only PR changes keeps it out of unrelated
clean PRs.

The intentional regression uses Burr's MIT-licensed box fixture. The baseline
has separated solids; the failing PR replaces it with overlapping solids. This
gives a reproducible positive-volume interference rather than relying on an
inconclusive coincident curved trim. The clean PR changes only the Voron part
names and retains separated geometry. Both PRs use the default changed-file
selection, released binaries, and GitHub Actions bot comments.
