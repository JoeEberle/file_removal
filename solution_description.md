
The delete_files_with_keywords function is a Python script designed to selectively remove files from 
a specified target directory based on user-defined keywords. The function takes two parameters: 
target_directory denotes the directory where the deletion operation will be performed, and keywords 
is a list of strings that serve as criteria for identifying files to be deleted. 
The function utilizes the os module to navigate and manipulate the file system. 
It begins by listing all files in the target directory, then iterates through each file, 
checking if its name contains any of the specified keywords. 
If a match is found, the file is deleted using os.remove(), and its name is added to the deleted_files list. 
The function concludes by returning the list of deleted files. 
In the event of an error during the deletion process, an exception is caught, 
and an error message is printed, ensuring graceful error handling.