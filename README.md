
# TransVar []()

TransVar is a multi-way annotator for genetic elements and genetic variations. It operates on genomic coordinates (e.g., `chr3:g.178936091G>A`) and transcript-dependent cDNA as well as protein coordinates (e.g., `PIK3CA:p.E545K` or `PIK3CA:c.1633G>A`, or `NM_006218.2:p.E545K`, or `NP_006266.2:p.G240Afs*50`). It is particularly designed with the functionality of resolving ambiguous mutation annotations arising from differential transcript usage. TransVar keeps awareness of the underlying unknown transcript structure (exon boundary, reference amino acid/base) while performing reverse annotation (via fuzzy matching from protein level to cDNA level).

User Guide is available at the [wiki](https://github.com/zwdzwd/transvar/wiki/Home).

This is a continued TransVar implementation from what was hosted at [https://bitbucket.org/wanding/transvar](https://bitbucket.org/wanding/transvar).
