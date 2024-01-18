**I. User Configuration**

1. Add a user with the username “admin2” and password “currentpass”

   ```
   # useradd -u 210 -g dba -c “Surizal Nazeri” \ -d /home/dc010101 -s /bin/ksh -m dc010101

   Options:
   -u: UID
   -g: GID
   -c: Comment or GCOS
   -d: default initial location when logging in
   -s: Login shell
   -m: ensure create home directory
   ```

   <br>
   
   ```
   sudo adduser admin2
   ```

3. Give the sudo permission to “admin2”
   ```
   sudo usermod -aG sudo admin2
   ```

4. Change the password for “admin2” to “P@ssword”
   ```
   passwd command: change the user’s password

   surizal@dc12345-cmpd153:~$   passwd
   Changing password for surizal.
   (current) UNIX password :
   Enter new UNIX password :
   Retype new UNIX password :
   Passwd:  password updated succesfully
   surizal@dc12345-cmpd153:~$  _

   surizal@dc12345-cmpd153:~$   sudo passwd sn010101
   [sudo] password for surizal :
   Enter new UNIX password :
   Retype new UNIX password :
   Passwd:  password updated succesfully
   surizal@dc12345-cmpd153:~$  _
   ```

   <br>

   ```
   sudo passwd admin2
   ```

5. Insert the details for “admin2” user as follow:
   ```
   i. Name: John Watson
   ii. Office Phone: 0389212020
   iii. Room Number: TA-5-999
   ```
   ```
   sudo usermod -c "John Watson,TA-5-999,0389212020" admin2
   ```

6. Create a new group named as “investigators” with the ID number of “1437”.
   ```
   groupadd command: add group to the system

   # groupadd -g 123 mygroup

   Options:
   -g: GID
   -o: This option permits to add group with non-unique GID
   -r: This flag instructs groupadd to add a system account
   -f: This option causes to just exit with success status, if the specified group already exists. 
   g: If the specified GID already exists, other (unique) GID is chosen
   ```

   <br>

   ```
   sudo groupadd -g 1437 investigators
   ```

7. Add a new user with the username “MonaLisa” with the following details:
   ```
   i. UserID : 369
   ii. Login shell : /bin/sh
   ```
   ```
   sudo useradd -m MonaLisa -u 369 -s /bin/sh
   ```

**II. File and Directory Management**

1. Create a new directory name “Private” under /home/<YourIDNumber> directory.
   ```
   mkdir /home/<YourIDNumber>/Private
   ```

2. Create a new directory name “Family” under /home/<YourIDNumber> directory.
   ```
   mkdir /home/<YourIDNumber>/Family
   ```

3. Create a new directory name “Colleague” under /home/<YourIDNumber>.
   ```
   mkdir /home/<YourIDNumber>/Colleague
   ```

4. Create a new subdirectory name “MyStorage” under “Private” directory.
   ```
   mkdir /home/<YourIDNumber>/Private/MyStorage
   ```

5. Create a new subdirectory name “Tasks” under “Private” directory.
   ```
   mkdir /home/<YourIDNumber>/Private/Tasks
   ```

6. Create a new subdirectory name “FamilyDoc” under “Family” directory.
   ```
   mkdir /home/<YourIDNumber>/Family/FamilyDoc
   ```

7. Create a new directory name “List” under “Colleague" directory.
   ```
   mkdir /home/<YourIDNumber>/Colleague/List
   ```

8. Create a new file name “Mylist.txt” under “<YourIDNumber>” directory. The content of the file should have the list of files and directories at “<YourIDNumber>” directory.
   ```
   ls /home/<YourIDNumber> > /home/<YourIDNumber>/Mylist.txt
   ```

9. Create a new file name “timetable.doc” under “Private” directory. The file should contain the following text: “This is my timetable file for this semester”
   ```
   echo "This is my timetable file for this semester" > /home/<YourIDNumber>/Private/timetable.doc
   ```

10. Create a new file name “Assignment.docx” under “Colleague” directory.
    ```
    touch /home/<YourIDNumber>/Colleague/Assignment.docx
    ```

11. Create a new file name “TaskDate.png” under “Colleague” directory.
    ```
    touch /home/<YourIDNumber>/Colleague/TaskDate.png
    ```

12. Create a new file name “harddisk.txt” under “MyStorage” directory.
    ```
    touch /home/<YourIDNumber>/Private/MyStorage/harddisk.txt
    ```

13. Create a new file name “date.txt” under “FamilyDoc” directory. The file should contain the current date and time. (date command)
    ```
    date > /home/<YourIDNumber>/Family/FamilyDoc/date.txt
    ```

14. Create a new file name “login.txt” under “List” directory. The file should contain the list of users who are currently logged in. (who command)
    ```
    who > /home/<YourIDNumber>/Colleague/List/login.txt
    ```

15. Change the permission for “timetable.doc” so that:
    ```
    • owner can write and execute
    • group can read and execute, and
    • others can only read.
    ```
    ```
    chmod 334 /home/<YourIDNumber>/Private/timetable.doc
    ```

16. Change both the owner and group for the file “date.txt” to root
    ```
    General structure:
    chown <newUser>:<newGroup> <filename>
    ```

    <br>
    
    ```
    sudo chown root:root /home/<YourIDNumber>/Family/FamilyDoc/date.txt
    ```

17. Copy the file “login.txt” to the “Tasks” directory.
    ```
    cp command: copy one or more files or directory structures
    cp <source> <destination>

    $ cp /etc/apt/sources.list /home/surizal
    ```

    <br>
    
    ```
    cp /home/<YourIDNumber>/Colleague/List/login.txt /home/<YourIDNumber>/Private/Tasks/
    ```

18. Archive and compress the “Assignment.docx” and “TaskDate.png” files as an archive file named “NewArchive.tar.gz” at your home directory.

    | **Key options** | **Description**              |
    | :---: | :--- |
    | -c              | Creates an archive           |
    | -x              | Extracts files from archive  |
    | -t              | Displays files in archive    |
    | -v              | Verbose – shows the progress |
    | -f              | Specify archive’s name       |

    -c, -x, -t, cannot be combined with each other.<br>
    -v = optional, but highly advised to used<br>
    -f = COMPULSORY, must specify name of archive<br>
    
    ```
    $ tar –cvzf archive.tar.gz index.html pic2.jpg
    ```

    <br>

    ```
    tar -czvf /home/<YourIDNumber>/NewArchive.tar.gz /home/<YourIDNumber>/Colleague/Assignment.docx /home/<YourIDNumber>/Colleague/TaskDate.png
    ```

20. At your home directory, Copy and extract “NewArchive.tar.gz”
    ```
    cp /home/<YourIDNumber>/NewArchive.tar.gz /home/<YourIDNumber>/
    tar -xzvf /home/<YourIDNumber>/NewArchive.tar.gz -C /home/<YourIDNumber>/
    ```

**III. Package Installation & Configuration**

1. Update and upgrade your server
    ```
   # apt-get update
   # apt-get upgrade
    ```

2. Search the game sgt-puzzles
    ```
    # apt-cache search sgt-puzzles
    ```

3. Install the sgt-puzzles game
    ```
    # apt-get install sgt-puzzles
    ```

<br>**Question 1**

(a) What are the permission for all user category of the files that have permission of 761?

| **Octal** | **String Representation** | **Permissions**        |
| :---: | :---: | :--- |
| 0 (0+0+0) | ---                       | No Permission          |
| 1 (0+0+1) | --x                       | Execute                |
| 2 (0+2+0) | -w-                       | Write                  |
| 3 (0+2+1) | -wx                       | Write + Execute        |
| 4 (4+0+0) | r--                       | Read                   |
| 5 (4+0+1) | r-x                       | Read + Execute         |
| 6 (4+2+0) | rw-                       | Read + Write           |
| 7 (4+2+1) | rwx                       | Read + Write + Execute |

Category<br>
• Owner (user)<br>
• Group<br>
• World (public/everyone/all)

   <br>
   
   ```
   World is only allowed to execute.
   ```

<br>(b) Predict the output for last command in Figure 1.
   ```
   $ WORD1=“ is easy?”
   $ WORD2=“The examination”
   $ WORD3=$WORD2$WORD1
   $ echo $WORD3
   ```
   Figure 1<br>
   ```
   The examination is easy?
   ```

<br>(c) Based on Figure 2, write the correct command (i) until (iii) based on the output stated:-
   ```
   $ ls
   obj01   obj2   obj03   obj04   obj05
   objt1   objt02   objt3   objt04   objt05
   subj1   subj2   subj3   subj14   subj15
   ```

   Figure 2<br><br>

Asterisk (*)<br>
Matches any number of characters including none.

Example:
   ```
   $ ls
   chap   chap01   chap02   chap03   chap04
   chapx  chapy    chapz    draft01  draft02
   $ ls chap*
   chap   chap01   chap02   chap03   chap04
   chapx  chapy    chapz
   ```

<br>

Question Mark (?)<br>
Matches single of character

Example:
   ```
   $ ls
   chap   chap01   chap02   chap03   chap04
   chapx  chapy    chapz    draft01  draft02
   $ ls chap?
   chapx  chapy    chapz
   $ ls chap??
   chap01   chap02   chap03   chap04
   ```

<br>

Rectangular Brackets ([ ])<br>
Matches single of character in the class

Example:
   ```
   $ ls
   chap   chap01   chap02   chap03   chap04
   chapx  chapy    chapz    draft01  draft02
   $ ls chap0[124]
   chap01   chap02   chap04
   $ ls chap0[1-4]
   chap01   chap02   chap03   chap04
   ```

<br>

   (i) obj03   obj04   obj05
   ```
   ls objt0[3-5]
   ```
   <br>(ii) objt02   objt04   objt05
   ```
   ls objt0[245]
   ```
   <br>(iii) subj1   subj2   subj3   subj14   subj15
   ```
   ls subj*
   ```

<br>(d) There are specific commands for all of the following tasks from (i) to (iii). Write a complete and correct command:-
   <br><br>(i) Protect variable VARIABLE1 from being reassigned.
   ```
   $ readonly VARIABLE1
   ```
   <br>(ii) Rename directory1 file as directory2.
   ```
   $ mv directory1 directory2
   ```
   <br>(iii) Delete user danial together with his home directory. 
   ```
   # userdel –r danial
   ```

<br>**Question 2**

(a) Predict the output for the script in Figure 3.
   ```
   $ vi commitment
      #!/bin/bash
      echo "Hi $3"
      echo "You guys are $2"
      echo "I like your $4"
      echo "Thank you for your $0"
      echo "All the best for your $1"
   $ ./commitment final fun everyone focus
   ```
   Figure 3<br>
   ```
   Hi everyone
   You guys are fun
   I like your focus
   Thank you for your commitment
   All the best for your final
   ```

<br>(b) Create a shell script that will display the output as in Figure 4. The script should get a user input and 10 will be added to the input value. Then print the new value. Also, the script will print outputs for some commands.
   ```
   $ final_script
   Welcome to Songs World
   Current User Directory : /home/Azizul

   How many songs do you know? : 15

   The new number is 25

   Malay_lyric.pdf
   English_lyric.txt
   ```
   Figure 4<br><br>
   
   ```
   sudo vi final_script
   ```

   <br>

   You will get a page to write something. To insert some text, please press 'i' and you will see the “INSERT” word at the bottom of the page.

   <br>

   ```
   #!/bin/bash

   echo "Welcome to Songs World"
   echo "Current User Directory : $(pwd)"
   echo
   read -p "How many songs do you know? : " input
   new_value=$((input + 10))
   echo
   echo "The new number is $new_value"
   echo
   touch Malay_lyric.pdf
   touch English_lyric.txt

   echo "Malay_lyric.pdf"
   echo "English_lyric.txt"
   ```

   <br>

   To save, press 'Esc' and 'w' to write and 'q' to quit from “INSERT” mode and press ':' at the keyboard. You need to see ':' at the bottom of your page. Press 'wq' to save and exit. You will get your prompt back.

   <br>

   ```
   sudo chmod +x final_script
   ./final_script
   ```

<br>**I. User Configuration**

1. Add a user with the username “king” and password “current”.
    ```
    sudo adduser king
    ```

2. Give the sudo permission to “king”
    ```
    sudo usermod -aG sudo king
    ```

3. Change the password for “king” to “I@mkinG”
    ```
    sudo passwd king
    ```

4. Insert the details for “king” user as follow:
    ```
    i. Name: Michael
    ii. Office Phone: 039999999
    iii. Room Number: BN-0-04
    ```
    ```
    sudo usermod -c "Michael,BN-0-04,039999999" king
    ```

5. Create a new group named as “royalty” with the ID number of “999”.
    ```
    sudo groupadd -g 999 royalty
    ```

6. Add a new user with the username “Queen” with the following details:
    ```
    i. UserID : 143
    ii. Login shell : /bin/bash
    ```
    ```
    sudo useradd -m Queen -u 143 -s /bin/sh
    ```

<br>**II. File and Directory Management**

1. Create a new directory name Personal under /home directory.
    ```
    $ mkdir /home/Personal
    ```

2. Create a new directory name Family under /home directory.
    ```
    $ mkdir /home/Family
    ```

3. Create a new directory name Friends under /home directory.
    ```
    $ mkdir /home/Friends
    ```

4. Create a new directory name Special under /home directory.
    ```
    $ mkdir /home/Special
    ```

5. Create a new directory name Study under /home/Personal directory.
    ```
    $ mkdir /home/Personal/Study
    ```

6. Create a new directory name Expenditure under /home/Personal directory.
    ```
    $ mkdir /home/Personal/Expenditure
    ```

7. Create a new directory name Cousins under /home/Family directory.
    ```
    $ mkdir /home/Family/Cousins
    ```

8. Create a new directory name Siblings under /home/Family directory.
    ```
    $ mkdir /home/Family/Siblings
    ```

9. Create a new directory name Sem1 under /home/Personal/Study directory.
    ```
    $ mkdir /home/Personal/Study/Sem1
    ```

10. Create a new directory name Sem2 under /home/Personal/Study directory.
    ```
    $ mkdir /home/Personal/Study/Sem2
    ```

11. Create a new file name etc.txt under/ home/ directory. The content of the file should have current date and time.
    ```
    date > /home/etc.txt
    ```

12. Create a new file name result.png under /home/Personal/Study/Sem1 directory.
    ```
    touch /home/Personal/Study/Sem1/result.png
    ```

13. Create two new files under /home/Personal/Expenditure directory. Filenames are:-
    ```
    i) january.xlsx
    ii) february.png
    ```
    ```
    touch /home/Personal/Expenditure/january.xlsx
    touch /home/Personal/Expenditure/february.png
    ```

14. Create two new files under /home/Friends directory. Filenames are:-
    ```
    i) contact.doc
    ii) addresses.txt **contact.doc should contain the following text: “This is the list of contact person.” **Addresses.txt should have list of files and directory at /home directory
    ```
    ```
    echo "This is the list of contact person." > /home/Friends/contact.doc
    ls -la /home > /home/Friends/addresses.txt
    ```

15. Create two new files under /home/Special directory. Filenames are:-
    ```
    i) photo.jpg
    ii) interests.doc
    ```
    ```
    touch /home/Special/photo.jpg
    touch /home/Special/interests.doc
    ```

16. Set the permission of the file result.png under home/Personal/Study/Sem1 directory to be: 
    ```
    • Only the owner can read, write and execute
    ```
    ```
    chmod 700 /home/Personal/Study/Sem1/result.png
    ```

17. Set the permission of the january.xlsx under home/Personal/Expenditure directory to be:
    ```
    • Owner : can read and write only
    • Group : can read and write only
    • World/Others : can read and write only
    ```
    ```
    chmod 666 /home/Personal/Expenditure/january.xlsx
    ```

18. Change both the owner and group for the file etc.txt to root.
    ```
    sudo chown root:root /home/etc.txt
    ```

19. Archive and compress the “photo.jpg” and “interests.doc” files as an archive file named “archive1.tar.gz”.
    ```
    tar -czvf /home/archive1.tar.gz /home/Special/photo.jpg /home/Special/interests.doc
    ```

20. Copy and extract “archive1.tar.gz” to /home directory.
    ```
    cp /home/archive1.tar.gz
    tar -xzvf /home/archive1.tar.gz -C /home/
    ```

<br>**III. Package Installation & Configuration**

1. Update and upgrade your server
    ```
    # apt-get update
    # apt-get upgrade
    ```

2. Search the service postfix
    ```
    # apt-cache search postfix
    ```

<br>**Question 1**

(a) What are the symbol representation for a normal user and superuser?
   - Normal User: $
   - Superuser: #

<br>(b) Predict the output for last command in Figure 1.
   ```
   $ SENT1=“is virtue”
   $ SENT2=“patience”
   $ SENT3=$SENT1$SENT2
   $ echo $SENT3
   ```
   Figure 1<br>
   ```
   is virtuepatience
   ```

<br>(c) Based on figure below, answer the following set of questions.

```
ikhsan@dc99999-server:~$ ls -l
total 84
-rw-rw-r-- 1 ikhsan ikhsan 15 Mar 21 07:44 aaa.doc
-rw-rw-r-- 1 ikhsan ikhsan 17 Nov 30 03:53 abc.txt
-rw-rw-r-- 1 ikhsan ikhsan 0 Mar 21 05:19 abc.xlsx
-rw-rw-r-- 1 ikhsan ikhsan 5 Mar 21 07:32 addresses.txt
drwxrwxr-x 5 ikhsan ikhsan 4096 Nov 1 05:18 dc123456
drwxrwxr-x 2 ikhsan ikhsan 4096 Nov 1 04:30 examdemo
-rw-rw-r-- 1 ikhsan ikhsan 0 Nov 30 03:51 index.html
-rw-rw-r-- 1 ikhsan ikhsan 0 Oct 3 04:32 marks.xls
-rw-rw-r-- 1 ikhsan ikhsan 10240 Oct 17 01:43 myarchive.tar
drwxrwxr-x 2 ikhsan ikhsan 4096 Nov 14 02:44 mybackup
-rwxrwxrwx 1 root root 90 Nov 14 02:07 my first
drwxrwxr-x 2 ikhsan ikhsan 4096 Oct 17 01:44 myfolder
```
   Figure 2<br><br><br>
(i) Identify the type of permissions for myfolder.
   - Read and execute permission for all users. The owner and group also has write permission.

<br>(ii) What is the type of files for abc.txt?
   - Regular file

<br>(iii) Elaborate on the command that are used in Figure 2.
   - The `ls -l` command is used to list files and directories with detailed information, including permissions, owner, group, size, modification time, and name.

<br>(iv) Identify how many directory files can be found in Figure 2.
   - dc123456, examdemo, mybackup, and myfolder.

<br>(d) There are specific commands for all of the following tasks from (i) to (iii). Write a complete and correct command:-

<br>(i) View history of commands executed earlier with the sentence ‘boot’ as part of the command.
   ```
   history | grep boot
   ```

<br>(ii) View test.txt file which are in the directory /home/folder1/subfolder1.
   ```
   cat /home/folder1/subfolder1/test.txt
   ```

<br>(iii) Delete user alyph together with his home directory.
   ```
   # userdel –r alyph
   ```

<br>**Question 2**

(a) Predict the output for the script in Figure 3.
   ```
   $ vi commitment
      #!/bin/bash
      echo "Greetings $3"
      echo "Today is $2"
      echo "So there will be no $1"
      echo "Enjoy your $0"
      echo "See you next $4"
   $ ./holiday assessment Friday everyone week
   ```
   Figure 3<br>
   ```
   Greetings everyone
   Today is Friday
   So there will be no assessment
   Enjoy your holiday
   See you next week
   ```

<br>(b) Create a shell script that will display the output as in Figure 4. The script should display current user who’s using the system, get a user input and 10 will be deducted from the input value and will be printed. The script will also displays various files of different extensions.

   ```
   $ test_scripting
   Welcome to My Second Script
   I am logged in as : User

   What is your favorite number? : 99

   After subtracting with 10, the number will be : 89

   Fav_number.png
   Fav_food.txt
   Fav_drink.doc
   ```
   Figure 4<br><br>
Create a script named `test_scripting` with the following content:

```
#!/bin/bash

echo "Welcome to My Second Script"
echo "I am logged in as : $(whoami)"
echo
read -p "What is your favorite number? : " input
result=$((input - 10))
echo
echo "After subtracting with 10, the number will be : $result"
echo
echo "Fav_number.png"
echo "Fav_food.txt"
echo "Fav_drink.doc"
```
