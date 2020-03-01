# LOC Counting Tool
Demonstration video: http://www.lukas-graber.tk/projects/loc_counter_for_github.html

A small Python application that counts the lines of code (LOC) for all repositories of a specific user account on GitHub. The application will iterate over the repositories of the user account, clone them into a temporary local repository and afterwards count the LOC for a specific file extension. Afterwards the local repository will be deleted.  
  
The Python Script is based on the following Script: https://gist.github.com/ralphbean/5733076
