---
layout: page
title: Data Prep
description: Theories, algorithms, and systems
img: assets/img/prep.jpg
importance: 1
category: dataprep
related_publications: DBLP:journals/pacmmod/Chen0FYCL023, DBLP:journals/pvldb/PengS0LKNC022, DBLP:journals/vldb/HaoTLFW21, DBLP:journals/pvldb/QahtanTOCS20, DBLP:conf/edbt/Thirumuruganathan20, DBLP:conf/sigmod/MuslehO0D20, DBLP:conf/kdd/QahtanEFO018
---

Modern organizations are faced with a massive number of heterogeneous data sets. It's not uncommon for a large enterprise to report having 10,000 or more structured databases, not to mention millions of spreadsheets, text documents, and emails. Typically these databases are not organized according to a common schema or representation.  As a result, data scientists in large organizations spend 90% or more of the time just trying to find the data they need and transform it into a common representation that allows them to perform the desired analysis.

Data prep includes a number of key problems, including: 

- Data discovery. Given some input request, this component crawls an organization’s data and returns those objects relevant to the request, employing a new graph-based approach for discovery and efficient data set indexing techniques.

	- Data stitching. Putting relevant data together for user consumption (i.e., data stitching). This requires investigating several issues on how graph-based and query-driving data stitching can be accomplished.

	- Data cleaning. We are investigating new data cleaning approaches along several directions: composition including an interactive dashboard and record expansion for outlier detection.

	- Data transformations. Data often needs to be transformed in order to use a uniform representation. We have developed a new program-synthesis-based transformation engine.

	- Entity consolidation. Our efforts in this area have focused on scaling entity resolution to very large data sets and using program synthesis to discover entity resolution rules.

	- Human-in-the-loop processing. We are working on new techniques to use human effort more effectively throughout the data integration and cleaning process, prioritizing attention on that part of the pipeline where human time can be most effective.

