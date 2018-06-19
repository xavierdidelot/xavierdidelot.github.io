## SimMLST: Simulation of MLST data under a neutral model

### Important notice

SimMLST is no longer actively maintained as it has been superseeded by [SimBac](https://github.com/tbrown91/SimBac) which was described in the paper by [Brown et al (2016)](http://mgen.microbiologyresearch.org/content/journal/mgen/10.1099/mgen.0.000044). 

---
### Introduction

Multi-locus sequence typing (<a href="http://en.wikipedia.org/wiki/MLST">MLST</a>) is a widely used method of characterization of bacterial isolates. It has been applied to over 50,000 isolates in over 50 different species and its results are freely available from the <a href="http://pubmlst.org/">pubMLST</a> website. This is the homepage of SimMLST, a coalescent method to jointly simulate MLST data and the clonal genealogy that gave rise to the sample. Such simulations are useful to make interpretations about real datasets.

---
### Getting help

Click here to download the <a href="http://www.stats.ox.ac.uk/~didelot/files/simmlst-userguide.pdf">SimMLST user guide in PDF format</a>.

SimMLST is described in <a href="http://bioinformatics.oxfordjournals.org/cgi/content/abstract/btp145">Didelot, Lawson and Falush (2009)</a> which is the appropriate citation for this program.

A technical description of the algorithm implemented in SimMLST is available <a href="http://www.stats.ox.ac.uk/~didelot/files/simmlst-tech.pdf">here</a>. 

If you have a question or a problem that is not discussed in the user guide, please <a href="contact.htm">get in touch</a>. 

---
### Download

SimMLST was implemented in C++ and Qt4 for the graphical user interface.
It is distributed under the terms of the <a href="http://www.gnu.org/licenses/gpl.html">GNU General Public License</a>.

* <a href="http://www.stats.ox.ac.uk/~didelot/files/simmlst.zip">Click here</a> to download the SimMLST version 1.0 executable for Windows.
* <a href="http://www.stats.ox.ac.uk/~didelot/files/simmlst32.zip">Click here</a> to download the SimMLST version 1.0 executable for Linux 32 bits.
* <a href="http://www.stats.ox.ac.uk/~didelot/files/simmlst64.zip">Click here</a> to download the SimMLST version 1.0 executable for Linux 64 bits.
* <a href="http://www.stats.ox.ac.uk/~didelot/files/simmlstsrc.zip">Click here</a> to download the C++ source code for version 1.0. Compile using `qmake;make&`
