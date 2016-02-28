---
layout: page
title: SQLShare Data Release for Research
group: "navigation"
id: "datarelease"
---
______________________________________________
## Database Research on SQLShare Corpus

In order to aid database research, we plan to periodically release the corpus of SQLShare queries and public datasets (for the consenting users only). If you plan on using this corpus, please cite the following work:

* *SQLShare: Results from a Multi-Year SQL-as-a-Service Experiment, Shrainik Jain, Dominik Moritz, Daniel Halperin, Bill Howe, Ed Lazowska, In Proceedings of the 2016 ACM SIGMOD International Conference on Management of Data. ([pdf](https://uwescience.github.io/sqlshare/pdfs/sqlshare_shrainik.pdf))*

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
