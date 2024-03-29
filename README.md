# Final Year Project
This is for the code for my Final Year Project on medical information retrieval

* This project is done in java, using the Eclipse IDE.
  * Inclusion of the Lucene Library Jar file is needed to access the methods that are used in this project,
    found here : https://lucene.apache.org/core/
* Inclusion of the Jar files found in the Jars folder is needed to compile, simple add to build path as an external Jar file in the project setup.
  * This report is based on the CLEF eHealth Task 2, found here https://sites.google.com/site/clefehealth2015/task-2
  * Data used for this project was access from https://physionet.org/users/, where an exsisting user must allow the use of the data set.
  
# Note: 
<b>The inverted index used for this project is saved in a file over 40GB in size before the stemming is done and HTML content is removed, ~4.5GB after cleaning. Not possible to include here.</b>

# DB
This contains the database that holds the queries and their relevance scores for the different retrieval models used.

# Graphs
This contains the retrieval graphs created for the different retrievals for the different metrics and languages used.

# Jars
This contains the Jar files used in this project, these are needed to be included to run the setup.

# Trec_Eval Relevancy Scores
This contains all of the test files of relevance, and the scores over the different metrics used in this project including NDCG and Precision, for all 8 languages used.

# Translations
This contains the queries in XML format, queries translated with the XML content, and queries that are not translated with the XML content added, and translated queries that have the XML content stripped out.

# Learning Files
This contains the java files that were used in the beginning to get to grips with the development with Lucene.

# Supplementary Files
This contains the files that are extra, including the EXE for Trec_Eval, a Gantt Chart for progress, the report, and the images used.

# Final Code
This contains all of the code that was ultimately used in this research project.
