# team synchronizing
## scenarios
1. right click on a file, then choose `team -> synchronize with repository`.
   it works just like **diff**. hence it can be substituted with **diff**. 
   this is not quite useful(in the sense that it is a substitute, not the 
   operation itself).
2. right click on a folder, then choose `team -> synchronize with repository`.
   this is quite useful, as it shows the status of all files in the folder.
   still, there are different scenarios.
   - right click on a java project
     > this shows two perspectives: project perspective and package perspective
   - right click on a java package
     > this shows package perspective
   - rigjt click on a non-java folder
     > this shows project perspective
## untracked 
eclipse labels **untracked** files with a <u>question mark</u>.
## modified
eclipse labels **modified** files with a <u>></u>.
## conflict
eclipse labels files with **conflict** with a <u>rhombus</u>.
## how to solve conflict in eclipse
just delete the file, and the right click the folder containing the file, choose `team -> synchronize with repository`, right click the file in repository, click `update`
## what `team -> update` does
it actually does a merge. hence it might introduce conflict
## substitute
use `substitute` instead of `update` to avoid conflict
