## **LINUX Assignment**<a id="linux-assignment"></a>

**1. How to make a directory.**

The ‘mkdir’ command is used for creating a directory.

Exa-
```
 mkdir test
 ```
**Output:** 
```
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ mkdir test
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ ll -ld test
drwxrwxr-x 2 vivek vivek 4096 Dec 13 14:19 test/
vivek@vivek-HP-EliteBook-840-G2:~/Linux$
```
![](https://lh7-us.googleusercontent.com/XeQJQTURAr0RYMpwqNmdhDzcORPgioTeceRflGAYbf47ayROYcBe19pQ4QocgR08LlZT_sRIo6XMQAtJFmCnheE2XomJrykjp8yCbPJ3lzi-w-nyJk7y67hMo_GNZkvZ_mQhXV6UrN7gzrQEjqVFI0M)

**mkdir:** It is used to create a directory.

**test:** this is a directory name.

**2.Remove a directory.**

The ‘rmdir’  command is used to remove(delete) a directory.

Exa- 
```
rmdir test 
```
**Output:**
```
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ rmdir test
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ ls
vivek@vivek-HP-EliteBook-840-G2:~/Linux$
```
![](https://lh7-us.googleusercontent.com/meOAhnQCD6JVwqkOrpldXLImZcegOARJ7YtdQc9yPtErn-JCAoFQViFXMkLvnvi_U-FZbOBRNMrZwGH7tOqaTNrG8rc4XH26aOyjDdK1IvElDSw0d8CO35EAHgTAVly8dL4MUQOJGO-xmURVojkfq7w)

**rmdir:** It is used to remove a directory.

**Test:** this is a directory name.

**ls:** The ‘ls’ command  is used to list files and directories in a directory.

**3.Make a copy of a file.**

The ‘cp’ command is used to copy files or directories.

Exa-
```
touch file.txt
```
**Output:**
```
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ touch file.txt
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ mkdir directory\_1
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ cp file.txt directory_1/
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ ls directory\_1/
file.txt
vivek@vivek-HP-EliteBook-840-G2:~/Linux$
```
![](https://lh7-us.googleusercontent.com/elpv9nJWAbv8m-i-IXE2onXrSxstFL-CR4QOWdf4HUbtu41bFNHimOF_pa6c8o-pF-1BgdbP5-X3GdE9M8DtrvH1s-F9cYyUrjPnORdYQMkhwoL8wzpWLNmoiCkBx59502qHooMzdW42ZyaOI9ueGYI)

**touch:** This command is used to create an empty file.

**file.txt:** This is a file name. 

**mkdir directory\_1:** create a new directory with name “directory\_1”

**cp file.txt directory\_1:** copy the file “file.txt” into the directory name “directory\_1”

**ls directory\_1:** list the content of the directory “directory\_1”.

**4.Move or rename a file.**

The “mv” command is used to move or rename a file and directory.

Exa- 
```
mv file1.txt file2.txt
```
**Output:**
```
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ ls
directory\_1  file1.txt
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ mv file1.txt file2.txt
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ ls
directory\_1  file2.txt
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ mv file2.txt /home/vivek/Linux/directory\_1/
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ ls
directory\_1
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ ls directory\_1/
file2.txt
vivek@vivek-HP-EliteBook-840-G2:~/Linux$
```
![](https://lh7-us.googleusercontent.com/60wJLJoXM5hMcn9mpMuwQNxRfpYrVAL8068M9muV0QSZ6YSYurFRXzQikmvk5rRIiZXFgp1F84pxNJvpDSlAaxLKjDMabzTwShVs31Q_-UlyYMkaj1q4W079NKVBYLdDd4tYjVmiNpuCnWyIYBIVIWI)

**ls:**  The ‘ls’ command  is used to list files and directories in a directory.

**mv file1.txt file2.txt:** Here ‘mv’ command is used to rename the file.

**mv:** mv command is used to rename.

**file1.txt:** this is an old file name.

**file2.txt:** this is a new file name.

**mv file2.txt /home/vivek/Linux/directory_1:** Here ‘mv’ command is used to move a file to a directory.

**mv:** this command is used to move a file.

**/home/vivek/Linux/directory_1:** this is the path of the moving file.

**ls directory_1:** this command shows the list of files and directories.

**5.Create an empty file.**

Touch command is used to create an empty file.

Exa-
```
touch a.txt
```
**Output:**
```
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ touch test.txt
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ cat test.txt
vivek@vivek-HP-EliteBook-840-G2:~/Linux$
```
![](https://lh7-us.googleusercontent.com/DtrTqhSSbQUXC-BFJ0SNB_KyZwe7O5qscRkHnQr0YYZ2isItYUREcgtHT_7XYMLWsWG8j1JC26vqN6FFod47IocrMdG9qeqYxfpt3gCg6vP2jb-mbkiFCQwjmT99Q-RAqtvjZt-i9gujD6IzhiRWwhc)

**touch:** this command is used to create a file.

**test.txt:** this is the name of the file..

**cat:** Here ‘cat’ command is used to display the content of the file.

**test.txt:** this is the name of the file.

**6.Remove multiple files with a single command.**

We can use the ‘rm’ command to delete multiple files.

* If you are delete all file then use ‘rm *’ this command.

Exa-
```
rm a.txt b.txt c.txt d.txt e.txt 
```
**Output:**
```
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ touch a.txt b.txt c.txt d.txt e.txt f.txt g.txt h.txt
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ ls
a.txt  b.txt  c.txt  directory_1  d.txt  e.txt  f.txt  g.txt  h.txt  test.txt
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ rm a.txt b.txt c.txt d
directory_1/ d.txt    
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ rm a.txt b.txt c.txt d.txt e.txt f.txt g.txt h.txt
vivek@vivek-HP-EliteBook-840-G2:~/Linux$ ls
directory_1  test.txt
vivek@vivek-HP-EliteBook-840-G2:~/Linux$
```
![](https://lh7-us.googleusercontent.com/XaYF8avnQEWEFKq9XswuiY_TUWOYWtGJGaHsIX0wREpUfM1UWsfE7pSx3pI0GgprLLJ0GuEDwFd_hYfa3uD61bybnnGw-GWMxGWZcIuL1Uc4d66M8lL67KYAS7qEDMozxFo2HHgSbx77CMHYNTEItok)

**touch:** I have already mentioned above.

**rm :** this command is used to remove files.

**ls:** I have already maintained the above.

**7.Remove content from the folder without removing folder.**

To remove the contents of a folder without removing the folder itself, use the command rm -r /path/to/main_directory/*.

Exa- 
```
rm -r /home/vivek/linux/a/*
```
**Output:** 
```
vivek@vivek-HP-EliteBook-840-G2:~/linux$ mkdir a
vivek@vivek-HP-EliteBook-840-G2:~/linux$ cd a
vivek@vivek-HP-EliteBook-840-G2:~/linux/a$ mkdir a b c d e && touch 1.txt 2.txt 3.txt 4.txt
vivek@vivek-HP-EliteBook-840-G2:~/linux/a$ ls
1.txt  2.txt  3.txt  4.txt  a  b  c  d  e
vivek@vivek-HP-EliteBook-840-G2:~/linux/a$ cd ../
vivek@vivek-HP-EliteBook-840-G2:~/linux$ rm -r /home/vivek/l
linux/             local-minio-test.yaml  
vivek@vivek-HP-EliteBook-840-G2:~/linux$ rm -r /home/vivek/linux/a/*
vivek@vivek-HP-EliteBook-840-G2:~/linux$ ls
a
vivek@vivek-HP-EliteBook-840-G2:~/linux$ cd a
vivek@vivek-HP-EliteBook-840-G2:~/linux/a$ ls
vivek@vivek-HP-EliteBook-840-G2:~/linux/a$
```
![](https://lh7-us.googleusercontent.com/3114aGmdZ4ziRdZhRTNoo_g6-X-cVaFWfKR3kQwn-iyWJg10cqeI1FH61jACw4K_wEH-xYxifTd8ujZ6tFQyRnploUBiSiZAUEYEXKQ4NcdzVuIxyESoyJDzyVS9A8Iw1b4cqRIHjyfzITUNKZRGu5A)

**mkdir:** I have maintained the above.

**cd a:** cd command is used to change the current working directory and ‘a’ is the name of the directory.

**mkdir:** I have already mentioned above but a b c … is the name of multiple directories.

**Touch:** I have already mentioned above but  1.txt 2.txt 3.txt … is the name of multiple files.

**ls:** I have already mentioned the above.

**cd../**: this command is used to one step back from the current directory.

**rm:** rm stands for remove.

**-r:** Stands for "recursive" meaning it will delete directories and their contents.

**/home/vivek/linux/linux/a/:** Specifies the path to the directory you want to operate on.

***:** It represents all files and subdirectories inside the specified directory.

Then  we check the directory-

**cd a:** I have already mentioned the above.

**ls :** check the list.

Now the data is removed but directory ‘a’ is not removed.

**8.Create multiple folder(a-z) with a single command.**

“mkdir {a..z}” command is used to create multiple folders(a-z) with a single command.

Exa-
```
 mkdir {a..z}
```
**Output:**
```
vivek\@vivek-HP-EliteBook-840-G2:\~/linux$ mkdir {a..z}
vivek\@vivek-HP-EliteBook-840-G2:\~/linux$ ls
a  b  c  d  e  f  g  h  i  j  k  l  m  n  o  p  q  r  s  t  u  v  w  x  y  z
vivek\@vivek-HP-EliteBook-840-G2:\~/linux$
```
![](https://lh7-us.googleusercontent.com/glpsEsnO1L61ukkFpdPLn962DJmayBnJikXuTvVw5-I_tMHfMBIgK5cH4lgWJQ6C9GYsAEqkpz6SNpli7PxvX0PwcNQMkn1eSJsydSy5hCpJv26zCbtNQsQ969d0bZ0emd32jPcw7cfJ0ZOEEF10-fQ)

**mkdir:** this command is used to make a directory.

**{a..z}:** This is a brace expansion in the shell. It generates a sequence of values between 'a' and 'z'.

-Brace expansion in the shell is a feature that allows you to generate a sequence of text or values by specifying a range or a list within curly braces { }.


 
