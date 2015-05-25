# DNAFamily
Java project to process gene sequences and emit same family of genes

What this project does:
A file contains the DNA sequence of people in the format shown below. This projeect finds all the people who have same DNAs.

Input:
“User1 ACGT”
“User2 TGCA”
“User3 ACG”
“User4 ACGT”
“User5 ACG”
“User6 AGCT”

Output:
User1, User4
User2
User3, User 5
User6

How to run it: Import the project in eclipse and create a JAR. Copy the jar file onto the local machine with Hadoop and use the hadoop streaming command similar to what's given below to execute it:

$ hadoop jar <location of jar file on hadoop local> <package_name.driver_class_name> <location on HDFS with input files> <output location on HDFS>

You can visit www.knowbigdata.com for more details and courses on Hadoop and Hadoop related technologies.
