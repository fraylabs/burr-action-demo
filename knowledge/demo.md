# Demo geometry

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
