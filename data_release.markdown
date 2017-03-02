---
layout: page
title: SQLShare Data Release for Research
group: "navigation"
id: "datarelease"
---
______________________________________________
## Database Research on SQLShare Corpus

In order to aid database research, we plan to periodically release the corpus of SQLShare queries and public datasets (for the consenting users only). If you plan on using this corpus, please cite the following works:

* SQLShare: Results from a Multi-Year SQL-as-a-Service Experiment, Shrainik Jain, Dominik Moritz, Daniel Halperin, Bill Howe, Ed Lazowska, In proceedings of the 2016 ACM SIGMOD International Conference on Management of Data. ([pdf](https://uwescience.github.io/sqlshare/pdfs/sqlshare_shrainik.pdf)) ([bibtex](https://www.dropbox.com/s/439z6x731o2pzz7/self-bibtex.bib?dl=0))
* Data Cleaning in the Wild: Reusable Curation Idioms from a Multi-Year SQL Workload: Shrainik Jain, Bill Howe, In proceedings of the 11th International Workshop on Quality in DataBases. ([draft](http://homes.cs.washington.edu/~shrainik/papers/QDB2016-datacleaning.pdf)) ([bibtex](http://homes.cs.washington.edu/~shrainik/citations/DCintheWild.bib))
* High Variety Cloud Databases: Shrainik Jain, Dominik Moritz, Bill Howe, In proceedings of the 2016 IEEE Cloud Data Management Workshop. ([pdf](https://uwescience.github.io/sqlshare/pdfs/ICDE16_research_5.pdf)) ([bibtex](https://www.dropbox.com/s/idj7x9olwdkyuk6/self-bibtex.bib?dl=0))
* SQLShare: Scientiﬁc Workﬂow via Relational View Sharing, Bill Howe, Francois Ribalet, Sagar Chitnis, E. Virginia Armbrust, Computing in Science & Engineering, Special Issue on Science Data Management, Vol. 15, No. 2, March 2013. (invited) ([pdf](http://escience.washington.edu/sites/default/files/howe_sqlshare_cise_2013.pdf)) ([bibtex](https://scholar.google.com/scholar.bib?q=info:RsndZHbi_f0J:scholar.google.com/&output=citation&scisig=AAGBfm0AAAAAVQE197ooBANeeqaSBdQ2UALv6JmDjf1x&scisf=4&hl=en))
* Database-as-a-Service for Long Tail Science, Bill Howe, Garret Cole, Emad Souroush, Paraschos Koutris, Alicia Key, Nodira Khoussainova, and Leilani Battle, SSDBM 2011 (short paper)  ([pdf](http://escience.washington.edu/sites/default/files/sqlshare_ssdbm2011.pdf)) ([bibtex](http://www.cs.washington.edu/homes/billhowe/bib/howe_ssdbm2011.bib))

Click the link below to download the zip file with all the necessary information.

####How to use this corpus:
* After you unzip the file, you will find: 
    * a folder 'data'
    * one file with all the queries
    * and another with script to create [views](https://msdn.microsoft.com/en-us/library/ms190174.aspx) necessary to run the queries in the corpus.
* The 'data' folder has sub-folders for each user who provided consent to share their datasets. 
* Create [schema](https://msdn.microsoft.com/en-us/library/ms189462.aspx) & user for each sub-folder in 'data'. (With the name same as the sub-folder name).
* Each file in a user's sub-folder corresponds to a table that needs to be created in the context of that user. (The name of the table should be the same as the name of file corresponding to it)
* Create all the views (datasets) as per the definitions in the 'view_script.txt'.
* For any further information contact [Shrainik Jain](mailto:shrainik@cs.washington.edu).


###[Data Release 1](https://s3-us-west-2.amazonaws.com/sqlsharedatarelease1/sqlshare_data_release1.zip)

Some of the queries might not work anymore because the users either didn't give us permissions to release the accompanying datasets or they deleted it.

###Acknowledgements
We would like to acknowledge the following data scientists/researchers/departments for giving us permission to share these datasets:

* Christopher Erdmann, Head Librarian, Harvard-Smithsonian Center for Astrophysics
* Roger Rush, Portland State University
* Lars Butzmann, Hasso Plattner Institute
* Arushi Prakash, Graduate Student, Chemical Engineering, University of Washington
* beamreach.org
* Rachael Tatman, Phd Student, NSF Graduate Research Fellow, Department of Linguistics, University of Washington
* Chris T. Berthiaume, Biological Oceanography, University of Washington
