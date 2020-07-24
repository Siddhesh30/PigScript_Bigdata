# PigScript_Bigdata
A Big project on various analysis

To run the pig script make sure you have copied the .csv or .text file in necessary hdfs folder.
To process
$ hadoop fs -mkdir /(your desired folder name)/()
$ hadoop fs -put input.txt /(path to the folder created) --> cd to folder containing input file

Command to execute script

$ pig -x mapreduce '(PATH TO YOUR .pig File)' in my case it is
$ pig -x mapreduce '/home/cloudera/analysis.pig'


Happy Coding :)
