Note from ModelDB administrator:
The files you need to run (and examine the code of) the model are 1) newtmaze.ccm and 2) catacomb-2.034.zip, both of which are available from links below. You will likely need java from sun in order to run the model.
To start the model under linux if you have multiple java's installed you can execute a command like:

/usr/java/jre1.5.0_06/bin/java -jar /home/morse/nrnmodels/newtmaze/catacomb-2.034/ccmb.jar /home/morse/nrnmodels/newtmaze/newtmaze.ccm

or simpler if you use relative paths.

20170601:

The original source of catacomb web sites are not available at the moment so catacomb is being made available through this copy provided by Robert Cannon:

[http://senselab.med.yale.edu/ModelDB/Data/64242/catacomb.tgz](http://senselab.med.yale.edu/ModelDB/Data/64242/catacomb.tgz)
In addition you will need newtmaze.ccm from here: [http://senselab.med.yale.edu/ModelDB/Data/64242/newtmaze.ccm](http://senselab.med.yale.edu/ModelDB/Data/64242/newtmaze.ccm)

The links in the below have been turned off because they (askja.bu.edu site and others) no longer exist however the documentation is still relevant:

# askja.bu.edu: Computational Neurophysiology at the Boston University Center for Memory & Brain

|  | Supported by NIDA DA16454 as part of the NSF/NIH collaborative research in Computational Neuroscience Program, and by MH60013 and MH61492 and NSF SBE 0354378. |
|---|---|

---

| [BROWSE model files](http://askja.bu.edu/data/models/) | **UPLOAD model files** | [Catacomb bug tracker](http://axiope.anc.ed.ac.uk/catacomb/mantis/) | search site |
|---|---|---|---|
| (http://askja.bu.edu/data/models/) | ([http://askja.bu.edu/rak/upload.html](http://askja.bu.edu/rak/upload.html)) | (http://axiope.anc.ed.ac.uk/catacomb/mantis/) | (http://askja.bu.edu/search.html) |

---

### A model of the role of hippocampus in spatial navigation

|  |   |  |
|---|---|---|
| This model addresses the potential role of the hippocampus in goal directed spatial navigation, the role of theta rhythm oscillations in reversal learning, and the role of entorhinal cortex as a buffer for novel information. The model can encode a spatial environment and guide movement of a virtual rat to find a food reward within this environment. The structure of the model is constrained by the overall anatomical connectivity of the hippocampus, and the spread of activity is constrained by the relative size of place fields in entorhinal cortex and regions CA3 and CA1 of the hippocampus. The model has a simple form of theta phase precession. The model avoids interference from prior retrieval during encoding by implementing separate phases of encoding and retrieval on each cycle of the theta rhythm. The model uses sustained spiking activity in entorhinal cortical neurons to allow slow transitions in sensory input from the environment to cause synaptic modification dependent upon a very brief temporal window of spike timing dependent synaptic plasticity.
  ![weblink_to_askja_bu_edu_files/newtmaze](weblink_to_askja_bu_edu_files/newtmaze)
  Prof. Michael E. Hasselmo
  Department of Psychology
  Center for Memory and Brain,
  Program in Neuroscience and
  Center for BioDynamics
  64 Cummington St.
  Boston, MA 02215
  Tel: (617) 353-1397

  E-mail: hasselmo@bu.edu

  Overview of research projects:
  [http://people.bu.edu/hasselmo/](http://people.bu.edu/hasselmo/) laboratory web page.

  Articles available as PDF files:
  [http://people.bu.edu/hasselmo/publications.html](http://people.bu.edu/hasselmo/publications.html) publications page. |  | **Spatial navigation in a T-maze**: This integrate-and-fire model created with Catacomb relates hippocampal physiological data with the possible functional role of the hippocampus for behavior in a spatial navigation task.
To test this model:
(1) Download the Catacomb script ([http://askja.bu.edu/rak/newtmaze.ccm](http://askja.bu.edu/rak/newtmaze.ccm)) newtmaze.ccm.
*(Press the right hand mouse button on the link. A "Save As" window will pop up. At the bottom of the window, make sure to save as "All files", not as "HTML document".)*
(2) Make sure you have Catacomb version 2.034, which the newtmaze model is designed to work with: ([http://askja.bu.edu/mike/catacomb-2.034.zip](http://askja.bu.edu/mike/catacomb-2.034.zip)) catacomb-2.034.zip.
Some simple exercises with the newtmaze model are shown ([http://askja.bu.edu/mike/exploring-T-maze.html](http://askja.bu.edu/mike/exploring-T-maze.html)) here.

**Obtaining and running Catacomb**: The most recent stable release of Catacomb may be obtained at: ([http://askja.bu.edu/catacomb/index.html](http://askja.bu.edu/catacomb/index.html)) http://askja.bu.edu/catacomb/.
*(The most recent version will not work with the newtmaze model. As indicated above, that model is designed to work with version 2.034 of Catacomb.)*

To run the Catacomb environment, you need a suitable implementation of **JAVA** for your computer and operating system. While Catacomb may run with the Java provided as a standard installation on your platform, the best way to insure that Catacomb will run correctly is to install Java from one of these two sources:
(1) The official Java site at [http://www.java.com/](http://www.java.com/).
A box displayed at this site offers automated and manual download of java software. If you follow the link to the automated download, a page will appear that immediately attempts an automated installation of the correct Java for your platform.
If the automated install does not work, or if you wish to manually select a different platform, such as Linux, Macintosh or Solaris, use the "Manual Download" link at the front page of [http://www.java.com/](http://www.java.com/).
*(If your operating system is Windows95, the FAQ link at the official Java site indicates how to install Java properly.)*
(2) The Java developers download page at [http://java.sun.com/j2se/1.4/download.html](http://java.sun.com/j2se/1.4/download.html).
Scroll down the page to the section labeled "Download J2SE v 1.4.2_03".
There, download from the column labeled "JRE". Software for all operating systems is provided.

**Project Guidelines for PS530 students**: The following guidelines may be useful for those who would like to learn about Catacomb and the details of the hippocampal simulation.

- Downloading and Running guidelines for the Catacomb tutorials: [Exercise1.pdf](http://askja.bu.edu/rak/catacomb-examples/Exercise1.pdf).
  The software page for PS530, [PS530: Neural models of Memory Function](http://askja.bu.edu/mike/index.html).
- PS530 Students Guidelines for a Final Project using Catacomb: [CatacombFinalProjectGuidelines2003b.pdf](http://askja.bu.edu/rak/catacomb-examples/CatacombFinalProjectGuidelines2003b.pdf)
  (or the same document in MS Word [CatacombFinalProjectGuidelines2003b.doc](http://askja.bu.edu/rak/catacomb-examples/CatacombFinalProjectGuidelines2003b.doc) format).
- Assignment 1: [PS530catacombEx1for2003fPDF.pdf](http://askja.bu.edu/rak/catacomb-examples/PS530catacombEx1for2003fPDF.pdf)
  (or the same document in MS Word [PS530catacombEx1for2003f.doc](http://askja.bu.edu/rak/catacomb-examples/PS530catacombEx1for2003f.doc) format).
- Assignment 2: [PS530catacombEx2for2003b.pdf](http://askja.bu.edu/rak/catacomb-examples/PS530catacombEx2for2003b.pdf)
  (or the same document in MS Word [PS530catacombEx2for2003b.doc](http://askja.bu.edu/rak/catacomb-examples/PS530catacombEx2for2003b.doc) format).

(You will need a PDF reader, such as the free [Acrobat Reader](http://www.adobe.com/products/acrobat/) to open the PDF files above.) |

---

### Catacomb

Information about the Catacomb simulation environment is available at [http://askja.bu.edu/catacomb/index.html](http://askja.bu.edu/catacomb/) (a mirror of compneuro.org).

A Catacomb wizard tool that accelerates the construction of standard experiments is in the early stages of development at:
[http://askja.bu.edu/catacomb-wizard/](http://askja.bu.edu/catacomb-wizard/).

---

### The Virtual Rat

A log of ongoing projects and Catacomb simulations collected under the general heading "The Virtual Rat" is maintained at [http://askja.bu.edu/rak/virtual-rat.html](http://askja.bu.edu/rak/virtual-rat.html). The project research described there currently involves models of prefrontal cortical areas and hippocampus in the rat.

---

( http://askja.bu.edu/ ) askja.bu.edu - (http://rak.minduploading.org/) Randal A. Koene

---

2025-06-02: Standardized to Markdown.