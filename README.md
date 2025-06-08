# Advance-Linux :-- File Creation Task

Task 1 :


vagrant@ubuntu-bionic:~$ mkdir my_folder
mkdir: cannot create directory ‘my_folder’: File exists
vagrant@ubuntu-bionic:~$ mkdir my_folder.1
vagrant@ubuntu-bionic:~$
vagrant@ubuntu-bionic:~$
vagrant@ubuntu-bionic:~$
vagrant@ubuntu-bionic:~$ cd my_folder.1
vagrant@ubuntu-bionic:~/my_folder.1$
vagrant@ubuntu-bionic:~/my_folder.1$
vagrant@ubuntu-bionic:~/my_folder.1$
vagrant@ubuntu-bionic:~/my_folder.1$ echo "RCB won the match in the my_file.txt." > my_file.txt
vagrant@ubuntu-bionic:~/my_folder.1$
vagrant@ubuntu-bionic:~/my_folder.1$
vagrant@ubuntu-bionic:~/my_folder.1$ echo "But I am not the fan of RCB another_file.txt." > another_file.txt
vagrant@ubuntu-bionic:~/my_folder.1$
vagrant@ubuntu-bionic:~/my_folder.1$
vagrant@ubuntu-bionic:~/my_folder.1$
vagrant@ubuntu-bionic:~/my_folder.1$
vagrant@ubuntu-bionic:~/my_folder.1$ cat another_file.txt >> my_file.txt
vagrant@ubuntu-bionic:~/my_folder.1$
vagrant@ubuntu-bionic:~/my_folder.1$ cat my_file.txt
RCB won the match in the my_file.txt.
But I am not the fan of RCB another_file.txt.
vagrant@ubuntu-bionic:~/my_folder.1$ ls
another_file.txt  my_file.txt
vagrant@ubuntu-bionic:~/my_folder.1$ ls -a
.  ..  another_file.txt  my_file.txt
vagrant@ubuntu-bionic:~/my_folder.1$ ls -
ls: cannot access '-': No such file or directory
vagrant@ubuntu-bionic:~/my_folder.1$ ls -l
total 8
-rw-rw-r-- 1 vagrant vagrant 46 Jun  8 11:53 another_file.txt
-rw-rw-r-- 1 vagrant vagrant 84 Jun  8 11:56 my_file.txt

################################################################################################################################################################################################

Task-2

vagrant@ubuntu-bionic:~$ touch file1.txt file2.txt file3.txt file3.txt file4.txt file5.txt file6.txt file7.txt file8.txt file9.txt file10.txt
vagrant@ubuntu-bionic:~$ touch file11.txt file12.txt file13.txt file14.txt file15.txt
vagrant@ubuntu-bionic:~$ ls
BASH      My_folder  cp         file10.txt  file13.txt  file2.save  file4.txt  file7.txt  my_folder    task3     trail
Mani      Task       editor     file11.txt  file14.txt  file2.txt   file5.txt  file8.txt  my_folder.1  test
Manikant  bash       file1.txt  file12.txt  file15.txt  file3.txt   file6.txt  file9.txt  task1        test.txt
vagrant@ubuntu-bionic:~$ mv file1.txt file1.yml'
>
>
> ^C
vagrant@ubuntu-bionic:~$ mv file1.txt file1.yml'
Create 20 files with .txt extensions and rename the first 5 files to .yml extension and Print the latest created top 5 files among the total no of filesCreate 20 files with .txt extensions and rename the first 5 files to .yml extension and Print the latest created top 5 files among the total no of files^C
vagrant@ubuntu-bionic:~$ mv file1.txt file1.yml'

^C
vagrant@ubuntu-bionic:~$ mv file1.txt file1.yml
vagrant@ubuntu-bionic:~$ mv file2.txt file2.yml
vagrant@ubuntu-bionic:~$ mv file3.txt file3.yml
vagrant@ubuntu-bionic:~$ mv file4.txt file4.yml
vagrant@ubuntu-bionic:~$ mv file5.txt file5.yml
vagrant@ubuntu-bionic:~$ mv file6.txt file6.yml
vagrant@ubuntu-bionic:~$ ls
BASH      My_folder  cp         file10.txt  file13.txt  file2.save  file4.yml  file7.txt  my_folder    task3     trail
Mani      Task       editor     file11.txt  file14.txt  file2.yml   file5.yml  file8.txt  my_folder.1  test
Manikant  bash       file1.yml  file12.txt  file15.txt  file3.yml   file6.yml  file9.txt  task1        test.txt
vagrant@ubuntu-bionic:~$
vagrant@ubuntu-bionic:~$
vagrant@ubuntu-bionic:~$ ls -lt *.yml | head -n 6
-rw-rw-r-- 1 vagrant vagrant 0 Jun  8 12:11 file1.yml
-rw-rw-r-- 1 vagrant vagrant 0 Jun  8 12:11 file2.yml
-rw-rw-r-- 1 vagrant vagrant 0 Jun  8 12:11 file3.yml
-rw-rw-r-- 1 vagrant vagrant 0 Jun  8 12:11 file4.yml
-rw-rw-r-- 1 vagrant vagrant 0 Jun  8 12:11 file5.yml
-rw-rw-r-- 1 vagrant vagrant 0 Jun  8 12:11 file6.yml
vagrant@ubuntu-bionic:~$ ls -lt *.yml | head -n 10
-rw-rw-r-- 1 vagrant vagrant 0 Jun  8 12:11 file1.yml
-rw-rw-r-- 1 vagrant vagrant 0 Jun  8 12:11 file2.yml
-rw-rw-r-- 1 vagrant vagrant 0 Jun  8 12:11 file3.yml
-rw-rw-r-- 1 vagrant vagrant 0 Jun  8 12:11 file4.yml
-rw-rw-r-- 1 vagrant vagrant 0 Jun  8 12:11 file5.yml
-rw-rw-r-- 1 vagrant vagrant 0 Jun  8 12:11 file6.yml
vagrant@ubuntu-bionic:~$ ls -lt *.txt | head -n 10
-rw-rw-r-- 1 vagrant vagrant 47 Jun  8 12:12 file11.txt
-rw-rw-r-- 1 vagrant vagrant  0 Jun  8 12:12 file12.txt
-rw-rw-r-- 1 vagrant vagrant  0 Jun  8 12:12 file13.txt
-rw-rw-r-- 1 vagrant vagrant  0 Jun  8 12:12 file14.txt
-rw-rw-r-- 1 vagrant vagrant  0 Jun  8 12:12 file15.txt
-rw-rw-r-- 1 vagrant vagrant  0 Jun  8 12:11 file10.txt
-rw-rw-r-- 1 vagrant vagrant  0 Jun  8 12:11 file7.txt
-rw-rw-r-- 1 vagrant vagrant  0 Jun  8 12:11 file8.txt
-rw-rw-r-- 1 vagrant vagrant  0 Jun  8 12:11 file9.txt
-rw-rw-r-- 1 vagrant vagrant 57 Nov  6  2024 test.txt

#########################################################################################################################################################################################3
