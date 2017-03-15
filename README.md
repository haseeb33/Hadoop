### hadoop fs -ls
Show the files in hadoop environment

### hadoop fs -rm filename
Remove the filename from hadoop environment

### hadoop fs -rm -r directory
Remove the directory from hadoop environment

### hadoop fs -mkdir test
Create the new directory test in hadoop environment

### hadoop fs -cat filename.txt
Show the file content in countinues for

### hadoop fs -cat filename | less
Show the file content from start and see more by pressing enter

### hadoos fs -tail a-file.txt
Show the last few entries of content of a-file

### hadoop fs -get a-file b-file.txt
Copy the a-file from hadoop to current working directory by name b-file.txt

### hadoop fs -put abc.txt test
Put the abc.txt to hadoop directory test

### hadoop fs -mv oldname.txt newname.txt
Rename the file from oldename to newname

### hadoop jar jar-file-location-on-local-directory -mapper mapper-file.py -reducer reducer-file.py -file mapper-file.py -file reducer-file.py -input input-directory on-which-job-has-to-be-done -output output-directroy-on-which-hadoop-will-write-code 