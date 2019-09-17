sort record.txt | uniq | head -5 | tail -8
This will sort the given file and then print the unique values only.
The head and tail command will select the first 5 lines and then the last 5 lines from the file and then print the lines that are common to both of them.
