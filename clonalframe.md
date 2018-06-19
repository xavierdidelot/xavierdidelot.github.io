## ClonalFrame: inference of bacterial microevolution using multilocus sequence data

### Important notice

This webpage is about the original ClonalFrame released in 2007 and designed mostly to work on MLST data or small numbers of genomes. In 2015 a new separate software was released called ClonalFrameML which is designed to run on large whole genomes datasets. For more information about ClonalFrameML, see the separate <a href="https://github.com/xavierdidelot/ClonalFrameML">ClonalFrameML website</a>.

---

### Introduction

This is the homepage of ClonalFrame, a computer package for the inference of bacterial microevolution using multilocus sequence data. 

In a nutshell, ClonalFrame identifies the clonal relationships between the members of a sample, while also estimating the chromosomal position of homologous recombination events that have disrupted the clonal inheritance. 

ClonalFrame can be applied to any kind of sequence data, from a single fragment of DNA to whole genomes. It is well suited for the analysis of <a href="http://pubmlst.org/">MLST data</a>, where 7 gene fragments have been sequenced, but becomes progressively more powerful as the sequenced regions increase in length and number up to <a href="http://www.genomesonline.org/">whole genomes</a>. However, it requires the sequences to be aligned. If you have genomic data that is not aligned, we recommend using <a href="http://gel.ahabs.wisc.edu/mauve/">Mauve</a> which produces alignment of whole bacterial genomes in exactly the format required for analysis with ClonalFrame. 

The methods used in ClonalFrame are presented in the paper "Inference of bacterial microevolution using multilocus sequence data" by <a href="http://www.genetics.org/cgi/content/abstract/175/3/1251">Didelot and Falush (2007)</a>, which is the appropriate citation for this program. 

---
### Getting help

Click here to download the <a href="http://www.stats.ox.ac.uk/~didelot/files/clonalframe-userguide.pdf">ClonalFrame user guide in PDF format</a>. It is also included in each downloadable package.

The paper describing the methods is also available: <a href="http://www.genetics.org/cgi/content/abstract/175/3/1251">Didelot and Falush (2007)</a> 

If you have a question or a problem that is not discussed in the user guide, please <a href="contact.htm">get in touch</a>. 

---
### Download

#### Version 1.2 (current release): 

* Starting with this version, ClonalFrame is distributed under the terms of <a href="http://www.gnu.org/licenses/gpl.html">GNU General Public License</a>.
* <a href="http://www.stats.ox.ac.uk/~didelot/files/ClonalFrame-1.2.tar.gz">Click here</a> to download the source code of ClonalFrame. Installation is done either via the qmake utility using the command "qmake;make" or directly using the command `g++ -lgsl *.cpp -o ClonalFrame`
* <a href="http://www.stats.ox.ac.uk/~didelot/files/ClonalFrame-1.2-Mac.zip">Click here</a> to download a precompiled binary for Mac.
* <a href="http://www.stats.ox.ac.uk/~didelot/files/ClonalFrame-1.2-Lin.zip">Click here</a> to download a precompiled binary for Linux.
* For the GUI of ClonalFrame, please download the Windows version 1.1 below. Please note that this GUI is no longer supported and was originally designed to work for Windows XP. Some users have reported that it could be made to work for Windows 7/8 using the procedure described <a href="http://windows.microsoft.com/en-GB/windows7/products/features/windows-xp-mode">here</a>. The Windows GUI can also be used on a Mac via <a href=http://www.winehq.org/>Wine</a> or the <a href="http://winebottler.kronenberg.org/">WineBottler</a>. 

#### Version 1.1:

* <a href="http://www.stats.ox.ac.uk/~didelot/files/clonalframeinstaller.zip">Click here</a> to download ClonalFrame and GUI for Windows. 
* <a href="http://www.stats.ox.ac.uk/~didelot/files/clonalframelinuxgui.zip">Click here</a> to download ClonalFrame and GUI for Linux. 
* <a href="http://www.stats.ox.ac.uk/~didelot/files/clonalframewin.zip">Click here</a> to download ClonalFrame for Windows without the GUI. 
* <a href="http://www.stats.ox.ac.uk/~didelot/files/clonalframelinux.zip">Click here</a> to download ClonalFrame for Linux without the GUI. 
* <a href="http://www.stats.ox.ac.uk/~didelot/files/clonalframelinux64.zip">Click here</a> to download ClonalFrame for 64bit/Linux without the GUI.
* <a href="http://www.stats.ox.ac.uk/~didelot/files/clonalframemac.zip">Click here</a> to download ClonalFrame for Mac. 

#### Version 1.0:

* <a href="http://www.stats.ox.ac.uk/~didelot/files/clonalframeinstaller10.zip">Click here</a> to download ClonalFrame and GUI version 1.0 for Windows.

---
### xmfa2struct

xmfa2struct is a program written in C which converts files in eXtended Multi-Fasta format (XMFA, the input format of ClonalFrame) into the input file format of <a href="http://pritch.bsd.uchicago.edu/structure.html">Structure</a>.

* <a href="http://www.stats.ox.ac.uk/~didelot/files/xmfa2struct.c">Click here</a> to download the source code of xmfa2struct
* <a href="http://www.stats.ox.ac.uk/~didelot/files/xmfa2struct.zip">Click here</a> to download a Windows executable
* <a href="http://www.stats.ox.ac.uk/~didelot/files/xmfa2struct.pdf">Click here</a> to download the xmfa2struct readme file in PDF format
