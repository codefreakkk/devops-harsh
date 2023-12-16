1. hostname 
- check host of computer 

2. whoami

3. ip addr
- check ip address

4. pwd
- prints the working directory path

5. ls
- list directories of current folder

6. mkdir folder_name

7. find directorypath/ -name folder_name
- check's if there are any folder with given name in cmd 

8. ls folder_name*
- get all folder name starting with folder_name and anything after that

9. rmdir directory_name 
- this cmd deletes folder which does not contain any files

10. rm -r directory_name
- this cmd deletes the directory as well as its sub files and directories

11. ls -l 
- gives the detail information of folder and files

NOTE 
* rwx -> r stands for read
      -> w stands for write
      -> x stands for execute (delete, cannot run etc)

12. cat file_name
- show's output on terminal

13. wc file_name
- show's details of files

14. tar cvf new_file_name.tar file1 file2
- packages the files 

15. gzip file_name.tar
- performs zip operation and produces .tar.gz file

16. cp source_file destination
- copies the file to destination

17. mv file_name destination
- move file to destination

18. tar xvf file_name.tar.gz 
- unzip .tar.gz files 

19. zip file_name files
- zip the file with .zip extension

20. unzip file_name
- unzip the file with .zip extension

21. mv original_file_name new_file_name
- rename the file

22. cat file1 file2 > newfilename
- copies content of file1 and file2 to new file

22. split -l 1 file_name
- splits the content of file 

23. cat file | grep word_name
- show's the perticular word from the given file 

Note - 
* | -> pipe symbol which redirects output to another source 

23. head -1 file_name
- show's only 1 line from start of file

24. tail -2 file_name
- show's only 2 lines from end of file

25. sort file_name
- sort the file content

26. sort filename | uniq
- sort the file content and removes duplicates

27. su -
- switch user to root
- su stands for switch user and '-' stands for root user, instead of that we can also provide name of user

** GREP COMMAND **

- GREP (Global regular expression print)
- GREP command search for a particular string/keyword from a file and print lines matching a pattern.
- It checks line by line and print lines matching given pattern  

* Syntax : grep [OPTION].. Pattern [File]..

* Examples : 
1. grep "keyword" file_name
- gives perticular line of matching word

2. grep -i "keyword" file_name
- not case sensetive

3. grep -v "keyword" file
- To search everything except given pattern/keyword
	
4. grep -c "keyowrd" file
- Prints how many times (count) given keyword is present in file it consider's only one word from one line

5. grep -w "kewyord" file
- To search for exact match of given keyword in a file

6. grep -n "keyword" file
- Prints the line number and word of matching keyword
 
7. grep "keyword" file1 file2
- To search a given keyword in multiple files
































