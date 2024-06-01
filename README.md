# Nouveau Corpus d'Amsterdam

## The corpus

The original corpus (CA): The _Amsterdam Corpus of Old French Literary Texts_ was compiled at the beginning of the 1980s by a group of scholars directed by Anthonij Dees and resulted in the Atlas des formes linguistiques des textes littéraires de l'ancien français (1987). The electronic version of the texts was provided by Piet van Reenen (Free University of Amsterdam). It contains about 200 different texts, written between the beginning of the 11th and the end of the 14th century, some of them in several versions, which adds to a total of almost 300 text samples with more than three million words (tokens).

These forms had been manually annotated by Dees' team with a set of 225 numeric tags encoding part of speech and other morphological categories (e.g. "566" for verb, futur tense, 3rd person, plural). Some of the texts are electronic versions of existing editions (e.g. the Miracles de Notre Dame de Chartres by Jean le Marchant, edited by P. Kunstmann, Chartres/Ottawa, 1973), others are transcriptions of manuscripts made especially for this corpus. The original texts were not lemmatized. They are nevertheless a precious resource which enabled us to extract a lexicon of more than 130.000 Old French inflected forms and to train the part of speech tagger.

"Le Nouveau Corpus d'Amsterdam" (NCA): The new version of the corpus edited (revised, lemmatized, XML-formatted) by Pierre Kunstmann and Achim Stein was presented at the Lauterbad Workshop in February 2006 (see Kunstmann/Stein 2007 below). The corpus, the lexical resources used for the annotation and the documentation are available free of charge for non-commercial, non-profit research purposes for registered users who have sent the signed license agreement (PDF form) by email or to this address: Prof. Dr. Achim Stein, Institut für Linguistik/Romanistik, Universität Stuttgart, Keplerstraße 17, 70174 Stuttgart, Germany.

Piet van Reenen also provided an edition of _Les chartes de l'Aube_ (see below). They are annotated in the same format as the CA.

### History

05.01.2023: v4 installed, with additional part-of-speech annotation and lemmas from the RNN tagger (Schmid 2019) trained on BFM Gold Standard data (by A. Lavrentev, 2022)

31.05.2018: v3 is also provided for TXM corpus software

19.03.2011: v3 installed, with updated bibliography

22.03.2010: v2 is also provided for TIGERSearch

2008: v2 for download, queries online (with TWIC and TWICweb)

2006: v1 for download

### Credits

- Please cite the corpus as indicated below:

  - Stein, Achim et al. (2006): Nouveau Corpus d'Amsterdam. Corpus informatique de textes littéraires d'ancien français (ca 1150-1350), établi par Anthonij Dees (Amsterdam 1987), remanié par Achim Stein, Pierre Kunstmann et Martin-D. Gleßgen. Stuttgart: Institut für Linguistik/Romanistik, version <version>.

- If you refer specifically to the bibliographical information, please cite:

  - Gleßgen, Martin-Dietrich; Vachon, Claire (2010): Répertoire bibliographique du Nouveau Corpus d'Amsterdam, établi par Anthonij Dees et Piet Van Reenen (Amsterdam 1987), revu et élargi par M.-D.G. et C.V.. Stuttgart: Institut für Linguistik/Romanistik.

### References

Stein (2010): Outils et méthodes pour l'annotation des textes médiévaux. (Slides of a talk given at the Sorbonne, Paris, March 2010). [PDF]

Stein, Achim (2003): Étiquetage morphologique et lemmatisation de textes d'ancien français.  – Kunstmann, Pierre et al. (ed.): Ancien et moyen français sur le Web: Enjeux méthodologiques et analyse du discours, Ottawa: Les Éditions David, 273-284. [PDF French / English] 

Gleßgen, Martin-Dietrich & Vachon, Claire (2011): "L'étude philologique et scriptologique du Nouveau Corpus d'Amsterdam" - Casanova, Emili / Calvo, Cesáreo (éds.): Actes du XXVI CILPR, Valencia 6-11 septembre 2010, Berlin: De Gruyter. [draft version: PDF]

Gleßgen, Martin-Dietrich & Gouvert, Xavier (2007): "La base textuelle du Nouveau Corpus d'Amsterdam: ancrage diasystématique et évaluation philologique" - Kunstmann, Pierre & Stein, Achim (ed.): Le Nouveau Corpus d'Amsterdam. Actes de l'atelier de Lauterbad, 23-26 février 2006, Stuttgart: Steiner, 51-84.

Kunstmann, Pierre & Stein, Achim (2007): "Le Nouveau Corpus d'Amsterdam" - Kunstmann, Pierre & Stein, Achim (ed.): Le Nouveau Corpus d'Amsterdam. Actes de l'atelier de Lauterbad, 23-26 février 2006, Stuttgart: Steiner, 9-27 (ISBN 978-3-515-08997-5). [Link](https://www.steiner-verlag.de/Le-Nouveau-Corpus-d-Amsterdam/9783515089975)


## Terms of use

By downloading the corpus, you accept the following license agreement:

1. The author of the original plain text files of the Corpus d'Amsterdam
(herafter "CA") is Anthonij Dees, Free University of Amsterdam. The
files were provided by Pieter van Reenen, Free University of
Amsterdam.

2. The "Nouveau Corpus d'Amsterdam" (hereafter "NCA") was revised,
lemmatized, and edited by Pierre Kunstmann (University of Ottawa) and
Achim Stein (University of Stuttgart).  This project was partly funded
by the Alexander von Humboldt-Stiftung and the Canadian Social
Sciences and Humanities Research Council (SSHRC/CRSH). Martin-Dietrich
Glessgen, Claire Vachon and Xavier Gouvert (University of Zurich) have 
revised and augmented the bibliographical
information that was provided with the CA.

3. Separate license conditions may apply to other software
contained in this distribution. Please read the corresponding license
files.

4. You may use the corpus data, personally or
in the organisation you are responsible for, free of charge and on the
following terms and conditions:

  a. You may not use any file or part of file of this distribution for
     non-scientific or commercial purposes.
  b. You may not modify the original CA data (plain text files).
  d. You may modify and redistribute the NCA text files (XML files)
     under the terms of the CC BY-NC-SA 4.0 license.

5. In no event will the authors or editors be liable to the user for
damages, including any lost profits or other special, incidental or
consequential damages arising out of the use or inability to use the
software or for any claim by any other party.


## Use of NCA version 3.0 (2011-) and version 4 (2023-)


### With TXM for local installation

This is the recommended way to use the corpus.  For the other options listed below, please contact the author.

Use the TXM corpus software developed at the ENS de Lyon: [LINK](https://txm.gitpages.huma-num.fr/textometrie/en/). It provides a well documented graphical search interface for the powerful CQP (Corpus Workbench) query processor. Among many other functions, it also allows you to easily create subcorpora by selecting individual texts according to the bibliographical information.

Download and install the TXM corpus software by following the instructions given on the Textométrie web site. TXM comes with a ‘normal’ installer for different systems (Windows, Mac, etc.).

For TXM versions (0.8 or later):

- Download the NCA v3 in TXM format. The file will download as NCA3.txm
- Download the NCA v4 in TXM format. The file will download as NCA4.txm

In TXM: Menu File - Load - a binary corpus (.txm)…

In the ‘Open file’ window: select the file NCA3.txm (the one you downloaded) and open it. TXM will need some time (about a minute, maybe longer) to load the corpus. (The blue progress bar in the window frame (bottom right) will change in colour, the console will display a first message after 10-20 seconds, so be patient!)

### With older TXM versions (until 0.7.9):

- Download the zipped archive NCA for TXM (about 350 MB). Do not unzip the archive!
- In TXM: Menu File - Load
- In the ‘Open file’ window: select the zipped archive file (the one you downloaded) and open it. (Note that in the file selection window you may have to switch from *.txm to *.zip extensions in order to be able to select the zip file).
- TXM will unpack and install the corpus. This may take a couple of minutes and requires about 3,5 GB space on your disk. TXM will put the corpus in the ‘corpora’ folder under the ‘TXM’ folder it created (by default) in your home folder. There (probably in corpora/nca3/txm/NCA3) you will also find (more or less) readable XML files for each text. You may re-use them, but use copies and don’t modify TXM’s subfolders.

If everything works fine in TXM, you can delete the downloaded file.

Note: if you use the IMS Corpus Workbench, you can use the TXM corpus directly with the command-line tool CQP (since TXM is built around the CQP query engine). The files indexed for CQP are in your TXM corpus folder .../corpora/NCA3/data/NCA3 and you only have to link them or set the path variables for CQP accordingly.


### With TIGERSearch for local installation (version 3 only)

TIGERSearch is not supported anymore by IMS Stuttgart. But it is still freely available and some people still seem to work on the sources. It is a great query software, provides a graphical user interface and runs on any system that provides Java or a Java runtime environment (Windows, Mac OS X, Linux and other Unix systems). On the downside, it may be more difficult to install on some systems, and since it was developed for syntactically annoted corpora, queries for corpora that are ‘only’ annotated at word level (part of speech, lemmas) are a bit less straightforward than in other programmes. If you don’t already know TIGERSearch I recommend to try TXM first.

The TIGER distribution is only available for version 3.  For version 4, I recommend using TXM

For TIGERSearch, follow these steps (you may need to adapt some of them to your specific system):

- Download TIGERSearch from the TIGERSearch home page (IMS, Stuttgart) (the link is at the bottom of the page)

- Unpack the archive and move the complete folder (as of 2018 ‘TIGERSearchTools’) somewhere on your disk.

- Some sample corpora are pre-installed in the subfolder ‘CorporaDir’.

- Use one of the batch files (Windows) / shell scripts (Mac) to start TIGERSearch

- Download the NCA for TIGERSearch (zip archive): nca3-for-tiger.zip (ca 41MB)

- Unpack the downloaded zip file: it contains a folder "NCA3"

- Move this folder into the "CorporaDir" folder (mentioned above).

You will find a quick start guide for using TIGERSearch with the NCA on my website, in the section Resources (or use this direct link). TIGERSearch includes a help function and a pdf manual (see help section III for a general description of the query language).

### With TIGERSearch and uncorrected automatic dependency annotation

This version was parsed with the [mate tools](https://code.google.com/archive/p/mate-tools/) joint transition-based parser using the LREC 2016 SRCMF-based grammar model (http://srcmf.org), which is available on my resources page.

Note that the dependency annotation contains many uncorrected errors, due to the precision of the parser and to the missing sentence markup in many of the texts.

- Download the NCA for TIGERSearch (zip archive): nca4-dep-for-tiger.zip (ca 46MB)

- Unpack the downloaded zip file as described above, for the NCA v3 (without dependency annotation)

You may of course use both versions of the NCA, parsed and unparsed, within the same TigerSearch installation.

### TWIC

TWIC (Tagged Words In Context) is a search tool for the XML-formatted NCA (and other XML-formatted text corpora). It is based on a Perl script (twic.pl). 

#### TWIC Online

Search the NCA using the TWIC web interface. This requires special permission for accessing our server.
Open [TWIC](http://julienas.philosophie.uni-stuttgart.de/twic/twic.html) in a new window.

#### TWIC local 

Download the NCA corpus with TWIC for local installation (not updated).
Download this ZIP Archive to install TWIC on your computer (Windows, Linux, Mac OS X). It includes the TWIC Perl programme, documentation for the different operating systems, and a sample corpus taken from the NCA. Open the ZIP Archive and read the included PDF document "TWIC installation".

Once TWIC is installed, you can replace the sample corpus by the entire NCA corpus (download nca3.xml.gz or nca4.xml.zip). You can install and search your own corpora: read the section about the configuration file. Even if you don’t intend to use TWIC, the XML file containing the complete corpus may be useful for other purposes.

Documentation and Bibliography for this version
Please follow the link for the online query above. On the query form, click on "corpus information window", where you will find links to the bibliography in various formats.

Please refer to this version as:

Stein, Achim et al. (ed.): Nouveau Corpus d'Amsterdam. Corpus informatique de textes littéraires d'ancien français (ca 1150-1350), établi par Anthonij Dees (Amsterdam 1987), remanié par Achim Stein, Pierre Kunstmann et Martin-D. Gleßgen, Stuttgart: Institut für Linguistik/Romanistik, version 3, 2011.

Changes in this version:

The bibliography has been revised considerably (by the Zurich group: Martin-D. Gleßgen and Claire Vachon).


## Les chartes de l'Aube

Printed version: Pieter van Reenen, avec le concours de Evert Wattel et Margôt van Mulken: Champagne 1270-1300, Chartes en langue française conservées aux Archives de l'Aube, Orléans: Paradigme 2006.

Electronic version, provided by Piet van Reenen with the permission of the publisher: Zip archive, 145k


## Previous NCA versions

Version 2.0 (2008, updated 2010) – Information provided for older versions is not updated; links may be obsolete.

1. TWIC Online Search for the NCA:

Open TWIC in a new window.

2. Download the NCA corpus with TWIC for local installation

Download this ZIP Archive to install TWIC on your computer (Windows, Linux, Mac OS X). It includes the TWIC Perl programme, documentation for the different operating systems, and a sample corpus taken from the NCA. Open the ZIP Archive and read the included PDF document "TWIC installation".

Once TWIC is installed, you can replace the sample corpus by the entire NCA corpus (download nca2.xml.gz , 2,5 MB). You can install and search your own corpora: read the section about the configuration file.

3. Download the NCA corpus with TIGERSearch for local installation

Note that TIGERSearch is probably easier to install than TWIC (since it does not require the installation of a web server). It provides a graphical user interface and is available for Windows, Mac OS X, Linux and Solaris. Please follow these steps:

Download TIGERSearch from the TIGERSearch Download page (IMS, Stuttgart)

Download one of the corpus files in TIGER-XML format:

The NCA corpus v2 for TIGER on Windows, Linux, Solaris: nca2-tiger-latin1.xml.gz (ca 60MB)

The NCA corpus v2 for TIGER on Mac OS X: nca2-tiger-macroman.xml.gz (ca 60MB)

I recommend the following complete package for Mac (updated version of TIGER, with the NCA v2 already installed): TIGERSearch-NCA-v2.dmg (Ca 80MB)

(Thanks to Cyprian-Virgil Gerstenberger for updating tiger.jar)

Follow the instructions in the document The NCA for TIGERSearch (PDF)

4. Documentation and Bibliography for this version

Browse the bibliography (HTML) (updated 1 may 2008)

Documentation files (directory)

Download all the documentation files (ZIP Archive, 1 MB)

Please refer to this version as:

Stein, Achim et al. (ed.): Nouveau Corpus d'Amsterdam. Corpus informatique de textes littéraires d'ancien français (ca 1150-1350), établi par Anthonij Dees (Amsterdam 1987), remanié par Achim Stein, Pierre Kunstmann et Martin-D. Gleßgen, Stuttgart: Institut für Linguistik/Romanistik, version 2, 2008.

Changes:

The Text La passion des jongleurs (id=jong) was updated: in version 1, the last word of each line was missing. (Thanks to Yves-Charles Morin for signalling this error).

The bibliography has been revised considerably (by the Zurich group: Martin-D. Gleßgen and his staff). The first entry of the bibliography (see links above) is a "comment entry" which briefly explains the meaning of the descriptors. These descriptors are values of the XML element "subcorpus" (using TWIC, you can therefore restrict your search to texts corresponding to these values, e.g. date ranges, regions, quality of the manuscript etc.).

Note that the bibliography is still work in progress. Updates will be published here.

Version 1.0 (2006)

Download the orginal distribution of the corpus:

The first version (1.0) of the corpus has been presented on a CD-Rom at the Lauterbad Workshop, February 2006. To reproduce it,

create a directory on your local disk drive, e.g. "nca"

download the files 00readme.txt, 00license.txt to "nca" (see below)

download the following zip archives to "nca"

twic.zip, 27MB, (new corpus, TWIC search tool)

sofa.zip, 10MB, (documentation, original corpus, frequency lists...)

perl.zip, 13MB, (Active State Perl for Windows, required if you use TWIC, also available at www.activestate.com)

xaira.zip, 382MB, (corpus formatted for Xaira, Xaira for Windows, not required if you use TWIC)

tagger.zip, 4MB, (TreeTagger, parameters for Old French)

unpack the archives (preserve the directory structure)

follow the Installation Guide in 00readme.txt

Quote this version as:

Stein, Achim et al. (ed.): Nouveau Corpus d'Amsterdam. Corpus informatique de textes littéraires d'ancien français (ca 1150-1350), établi par Anthonij Dees (Amsterdam 1987), remanié par Achim Stein, Pierre Kunstmann et Martin-D. Gleßgen, Stuttgart: Institut für Linguistik/Romanistik, 2006.
