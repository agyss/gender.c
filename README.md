# gender.c
This is a fork from gender.c, written by Jörg MICHAEL (astro.joerg_googlemail.com) in the years 2007 and 2008. The <a href="readme_g.txt">original README</a> is linked here.

## Purpose
The original purpose of the program was to find the right addressation for a person based on their first names. The provided data and structure are really valuable and may provide solid ground for further firstname-based projects.

## Todos:
* Compilation not tested, program is provided AS IS from (<a href="https://web.archive.org/web/2020*/ftp://ftp.heise.de/pub/ct/listings/0717-182.zip">webarchiv</a>)
* Data was carefully collected back in 2008 (see original README), but should be updated
* Not all countries from the world are covered
* Currently no support for more modern (Python, Node, ...) environments
* <a href="nam_dict.txt">Data</a> should be converted in more modern format (JSON?)


## History of the program

|date|description|
|-----|----|
2007-05-23:  |The first version of this program is submitted for publication in a German computer magazine (c't).
2007-08-06:  | Version 1.0: <br> is published in c't.
2007-09-07:  | Version 1.1: <br> gender.c:   A simple caching mechanism has been implemented and some minor bugs have been corrected.  nam_dict.txt: 50+ names (most of them from Czech Republic and Slovakia) have been added and a few errors have been corrected.
2007-11-15:  | Version 1.1.1: <br> A few names have been added or reclassified.
2008-11-30: | <p>Version 1.2: <br>gender.c :<br> - The function "find_similar_name" (plus "standardize_arabic_name") has been added (see documentation in this file). <br> - New functions to support unicode and utf-8 have been added (see documentation in this file). <br> - The function "internal_search" has been improved and some minor bugs have been corrected. <br> - gen_ext.h:  The macro "GENDER_COMPARE_EXACT" has been deleted and the new default is "COMPARE_EXPANDED_UMLAUTS".<br> - nam_dict.txt: - 3200+ names (most of them being from Asia, and Germany/East Frisia) have been added and a number of errors have been corrected (e.g. "Rigmor" reclassified to: female). <br> - Frequency values for many countries have been improved. "ex-U.S.S.R. (Asian)" has been split into: <br>a) Armenia, <br> b) Azerbaijan, <br> c) Georgia <br> d) Kazakhstan/Uzbekistan,etc.