## The preliminary benchmark and alignment results for the manuscripts
1. The 
2. We did not give a comprehensive benchmarking for these pipelines using simulated dataset. Instead, we used the NGS data for Caenorhabditis species from various sequencing platforms with various read characteristics including Roche 454, Illumina and ION torrent (Table S1). Take the *C. japonica* reads (from Roche 454) as an example, NOVOPlasty and ARC just failed in the very beginning by failed to handle reads with different read length. And MITObim failed as generating only small contigs (or a contig with many “N”). 
In addition, the annotation steps were not incorporated into these local packages. Consequently, further third party webserver, for example, Dogma and MITOS, is required to generate annotation for mtDNA. Therefore, we re-designed the mitovar pipeline to handle our specific purpose. 
3. 