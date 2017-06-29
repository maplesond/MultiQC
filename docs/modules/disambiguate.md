---
Name: ngs-disambiguate
URL: https://github.com/AstraZeneca-NGS/disambiguate
Description: >
    Disambiguation algorithm for reads aligned to two species (e.g. human and
    mouse genomes) from Tophat, Hisat2, STAR or BWA mem.
---

Disambiguation algorithm for reads aligned to two species (e.g. human and mouse
genomes) from Tophat, Hisat2, STAR or BWA mem. Both a Python and C++
implementation are offered. The Python implementation has a dependency on the
Pysam module. The C++ implementation depends on the availability of zlib and
the Bamtools C++ API. For STAR alignments it is highly recommended to include
the NM tag in the output when performing alignment (in fact this is a
requirement for the C++ version).

The multiqc module for Disambiguate parses the summary files generated by
Disambiguate.