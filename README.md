# Working with processes in Linux

**Operating systems & System Programming, Laboratory work #3**

## Task
Write a program to search for a user-specified combination of m bytes (m <255) in all files of the specified directory. Main process opens the catalog and
starts for each catalog file a separate search process for the specified combinations of m bytes. Each process displays its own pid, absolute path to file, the total number of bytes scanned, and the results (how many times it was found combination) of the search (all in one line). Number of simultaneously working processes should not exceed N (entered by the user). Check programs work for the /etc directory and the "ifconfig" line.

