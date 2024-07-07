Penn Parsed Corpora of Historical English (PPCHE) - 2024 release
================================================================

Contents
========

The ppche-2024 repository is part of an overarching project to make
available parsed texts of historical English for linguistic research.
It was developed at the University of Pennsylvania and consists of
running texts and text samples of British English prose from the
earliest Middle English documents (1100 CE) to the First World War (1914
CE).  The texts cover the following traditionally recognized periods of
English:

* the Penn-Helsinki Parsed Corpus of Middle English, second edition (PPCME2)
* the Penn-Helsinki Parsed Corpus of Early Modern English (PPCEME)
* the Penn Parsed Corpus of Modern British English, second edition (PPCMBE2)

The corpora are primarily intended for the use of students and scholars
of the history of English, especially the historical syntax of the
language.  They have also been used by computational linguists for
domain adaptation.

The present release differs from the previous 2016 release in that
annotation errors and inconsistencies have been corrected.  In addition,
the annotation guidelines
(<https://github.com/beatrice57/annotation-guidelines-for-ppche>) have
been streamlined to minimize differences across the three time periods
and inconsistencies across related syntactic phenomena.

All of the texts come in three forms: plain text, part-of-speech tagged
text, and syntactically annotated (parsed) text.  In addition, the
PPCEME and PPCMBE2 come in lemmatized form (best regarded as a beta
release), based on information from the Oxford English Dictionary (OED).
Each text also has an associated file with philological information.

Each of the three subcorpora has its own directory and should be cited
individually as follows:

* Kroch, Anthony, and Ann Taylor.  2000-.  The Penn-Helsinki Parsed
  Corpus of Middle English (PPCME2), second edition, release 5.

* Kroch, Anthony, Beatrice Santorini, and Lauren Delfs.  2004-.  The
  Penn-Helsinki Parsed Corpus of Early Modern English (PPCEME), second
  edition, release 4.

* Kroch, Anthony, Beatrice Santorini, and Ariel Diertani.  2016-.
  The Penn-Helsinki Parsed Corpus of Modern British English (PPCMBE2),
  second edition, release 2.

The directory for each subcorpus in turn has two directories: data and
docs.  The data directory contains three or four subdirectories with the
plain and annotated text files (text, pos-tagged, parsed, lemmatized).
The docs directory contains a general description of each subcorpus and
a philological_info_files directory with philological information for
each text.

All data is encoded in UTF-8.  The data files are presented as plain
text, and all philological information as html.  The parsed files
(including the lemmatized files) are in Penn Treebank format.

License
=======

The files in this repository are distributed under Creative
Commons License Attribution-NonCommercial-ShareAlike 4.0 International
CC BY-NC-SA 4.0 (<https://creativecommons.org/licenses/by-nc-sa/4.0>).

Contact
========

Beatrice Santorini (beatrice DOT santorini AT gmail DOT com)

Users are strongly encouraged to report errors.

Acknowledgments
===============

We are grateful to the following institutions and individuals for their
support and assistance.

* The users of the PPCHE for their years of financial support.

* Beth Randall for writing the CorpusSearch program, without which the
  corpus would not be useable for research, and for adding the corpus
  revision functions that support corpus construction.

* The users of the PPCHE who reported errors to us, notably Hezekiah
  Bacovcin, Alastair Butler, Aaron Ecay, Tom McFadden, Robert Truswell,
  and Joel Wallenberg, thereby allowing us to improve the quality of the
  corpora over time.

PPCME2
======

* The National Science Foundation for NSF Grants BNS 89-19701 and SBR
  95-11368.

* The University of Pennsylvania Research Foundation for supplementary
  support.

* Our colleagues at the University of Helsinki, especially Prof. Matti
  Rissanen, the project's emeritus director, for his permission to use
  the Middle English part of the Helsinki Corpus of English and for his
  enthusiasm toward our project, though it was far from his own
  interests; also Dr. Merya Kytö.

* Mike Collins, now at Columbia University, for permission to use his
  Penn dissertation parser and for adapting it to our needs.

* Rhona Alcorn and Robert Truswell for their help in parsing a few
  recalcitrant passages.

PPCEME
======

* The National Endowment for the Humanities for NEH Grant PA 23382-99.

* The National Science Foundation for NSF Grant BCS 99-05488.

* Our colleagues at the University of Helsinki: Prof. Terttu Nevalainen,
  director of the Helsinki Corpus project, and Prof. Matti Rissanen, the
  project's emeritus director, for permission to use the Early Modern
  English part of the Helsinki Corpus of English; Prof. Nevalainen and
  Dr. Helena Raumolin-Brunberg for help with sample selection and for
  comments on our documentation of the samples; and Dr. Merya Kytö for
  information concerning the source of various Helsinki Corpus samples.

* Ann Taylor for help in understanding the PPCME2 annotation guidelines
  and adapting them to modern English.

* Amy Forsyth, the administrative coordinator of the Department of
  Linguistics at the University of Pennsylvania, and Glynis Platt of the
  University Library at the University of Manchester for their help in
  obtaining an elusive text.

* The staff in the Rare Book Collection of Van Pelt Library at the
  University of Pennsyvania, especially John Pollack.

PPCMBE2
=======

* The National Science Foundation for NSF grants BCS 05-08731 and BCS
  11-47499.

* Dan Bikel for allowing us to use his Penn dissertation parser for our
  work.

* Seth Kulick for his help with training the Bikel parser and adapting
  it to our needs.

* Blaise Information Systems for quick and accurate data entry.

* The staff in the Rare Book Collection of Van Pelt Library at the
  University of Pennsyvania, especially John Pollack.

Annotation guidelines
=====================

As mentioned above, the annotation guidelines
(<https://github.com/beatrice57/annotation-guidelines-for-ppche>) differ
slightly from those for earlier releases.

Searching the corpora
=====================

The parsed files in the repository can be searched with CorpusSearch 2,
a Java program developed by Anthony Kroch and Beth Randall for
searching, revising, and coding parsed corpora.  The program can be
downloaded at <https://sourceforge.net/projects/corpussearch> or from
<https://github.com/beatrice57/CorpusSearch>.

<p> The original users guide site is no longer being maintained.  Please
refer instead to the corrected and revised live version
(<https://github.com/beatrice57/CorpusSearch>).
