---
layout: post
title:  "Project Introduction"
date:   2014-05-07 13:07:19
categories: jekyll update
---

<h1>PLUTo: Phyloinformatic Literature Unlocking Tools. Software for making published phyloinformatic data discoverable, open, and reusable</h1>

While there is near perfect archiving of, and excellent repositories for molecular sequence data (NCBI), data archiving for sequence alignments, morphological matrices, phylogenetic trees and other metadata is poor; only between 4 to 16% of what is published is publicly archived for future re-use. Much of this unarchived data remains locked down into PDFs, and are currently not machine-readable. This is hugely detrimental to many biological disciplines. In this project, we will develop and perfect tools (PLUTo) enabling researchers to unlock phyloinformatic data from published PDFs. These will generate Newick/NeXML tree files (with branch lengths and support metrics) by interpreting SVG and other graphics, and parsing the text/legends for other data. We will use AMI2 extraction technology, based on PDFBox, JUMBO and AMI-code. This is presently in prototype.

We will use the extracted data to address key questions in phyloinformatics and systematics:

* Which clades are the foci of phylogenetic research and what types of data are being used? 
* Importantly, how does this research effort relate to the diversity of clades? 
* Are some groups disproportionately under-sampled? 
* Is the quality of phylogenetic data variable across higher taxa?