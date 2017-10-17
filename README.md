# COMPASS
This software is used for protein backbone resonance assignment from unassigned triple resonance peak lists.
Compared to most other software for the same purpose, COMPASS lets the user control the assignment process, enabling supreme accuracy.
COMPASS is well suited for the assignment of larger deuterated proteins. COMPASS is compiled for Windows, Linux and Mac OS X.

Note that COMPASS was originally released at: http://liu.se/forskning/foass/tidigare-foass/patrik-lundstrom/software?l=en#COMPASS Due to recent website changes we have migrated our software to GitHub. This repository will be used for future changes to COMPASS.

Read our paper describing COMPASS here: <a href="http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004022">Markus Niklasson, Alexandra Ahlner, Cecilia Andresen, Joseph A. Marsh and Patrik Lundström (2015) Fast and Accurate Resonance Assignment of Small-to-Large Proteins by Combining Automated and Manual Approaches. PLOS Comp. Biol. 11(1): e1004022. doi:10.1371/journal.pcbi.1004022</a>

Compilation instructions:

The current build was compiled with Qt 5.7.0 for Windows, Mac and Linux.
We cannot guarantee that a different version of Qt can be used to compile COMPASS without minor modifications to the source code.
Download Qt and open the "compass.pro" project file.
Run qmake and then build.
