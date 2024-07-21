Advanced File and Directory Commands

--------------------------------------------------

find - Search for files in a directory hierarchy.

find /path/to/search -name "filename"
find /path/to/search -type d -name "dirname"  # search for directories

=====================================================================================
grep - Search text using patterns.

grep "pattern" file_name
grep -r "pattern" /path/to/search  # recursive search in directory
======================================================================================

tar - Archive files.
tar -cvf archive_name.tar directory_name  # create tar archive
tar -xvf archive_name.tar  # extract tar archive
tar -czvf archive_name.tar.gz directory_name  # create compressed tar archive
tar -xzvf archive_name.tar.gz  # extract compressed tar archive
======================================================================================
zip and unzip - Compress and decompress files.

zip archive_name.zip file_name
unzip archive_name.zip
=======================================================================================

ln - Create links between files.

ln -s target_file link_name  # create a symbolic link
ln target_file link_name  # create a hard link
=========================================================================================
__________________________________________________________________________________________

explanations of cammands

Basic Usage
Search by Name:

find path -name "pattern"
Example: find /home -name "*.txt" (finds all .txt files in /home)
Search by Type:

find path -type type
Example: find /home -type d (finds all directories in /home)
Search by Size:

find path -size size
Example: find /home -size +50M (finds files larger than 50MB in /home)
Search by Modified Time:

find path -mtime n
Example: find /home -mtime -7 (finds files modified in the last 7 days)
Execute a Command:

find path -name "pattern" -exec command {} \;
Example: find /home -name "*.log" -exec rm {} \; (finds and deletes all .log files in /home)

______________________________________________________________________________________________________















































































