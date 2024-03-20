# https://chat.openai.com/share/0beb0f51-84f3-4dcd-a1dc-fe32d8a72944

```
1. Which of the following is NOT a function available with iostream?
   A. cin
   B. cout
   C. endl
 = D. namespace


2. Which of the following describe about cin object?
   A. Store data from the keyboard only.
 = B. Accepts a stream of data from the standard input device.
   C. Outputs a stream of data from the standard input device.
   D. Accepts a stream of data from the standard output device.


3. A function prototype will tell the ____________ that there exist a function with this name defined at begin in the program and therefore it can be used even though the function has not yet been defined at that point.
   A. call
 = B. compiler
   C. computer
   D. prototype


4. In order to write and use our own function, we need NOT do these:

   I. Create a function prototype.
   II. Include header file for standard input output.
   III. Call the function whenever it need to be used.
   IV. Define the function at beginning of the program.

   A. I only
 = B. IV only
   C. I and III only
   D. I, II and III


5. Which of the following is a right example for the function call?
   A. add(int, int);
   B. add(num1, num2);
 = C. add(int num, int num2);
   D. void add(int num, int num2);


6. Which statement dynamically allocates an array of integers of n elements?
   A. int numbers[n];
   B. int *numbers[n];
   C. int numbers = new int[n];
 = D. int *numbers = new int[n];**


7. Which of the following is the proper keyword to deallocate memory in C++?
   A. free
   B. clear
 = C. delete
   D. remove


8. Choose the correct way(s) to declare a 2-dimensional array with 2 rows and 3 columns.

   I. int arr [2][3];
   II. int arr [3][2];
   III. int arr [ ][ ] = { 2, 3, 4 };
   IV. int arr [ ][ ] = { { 2, 3, 4 }, {5, 6, 7 } };

 = A. I only
   B. II only
   C. I and III only
   D. I, II and III


9. Which of the following is NOT describe about a structure?
   A. We can have pointers of type structures.
   B. Defining a structure is like defining a new data type.
   C. A structure may contain members of many data types.
 = D. A structure may contain function as members of its elements.


10. Which of the following is a properly defined struct?
    A. struct { int x; }
    B. struct my_struct int x;
  = C. struct my_struct{ int x; }
    D. struct my_struct{ int x; };


11. Which symbol is used to define the member of a class externally?
    A. :
    B. #
  = C. ::
    D. };


12. Which of the following is declare just like a regular member function, but with a name that matches the class name and without any return type?
    A. Cass
    B. Object
  = C. Constructor
    D. User-defined


13. The default constructor does not take any __________.
    A. return
    B. function
    C. data type
  = D. parameter


14. When constructor is invoked automatically?
    A. A class is defined.
    B. A class is referenced.
  = C. An object is instantiated.
    D. An object is called by a function.


15. What will be the output if the string syafiqah is entered in code Figure 1?

    Char name[20];
    cout << “Enter your name : ” ;
    cin.width(5);
    cin >> name;
    cout << name << endl;

    Figure 1

  = A. syaf
    B. syafi
    C. syafiq
    D. syafiqah


16. Which stream manipulator forces a floating point number to display a specific number of digits to the right of the decimal point?
  = A. fixed
    B. setw()
    C. width()
    D. scientific


17. Which stream manipulator is used to reset function showpos back to default display mode?
  = A. noshowpos
    B. stopshowpos
    C. cancelshowpos
    D. removeshowpoint


18. Which stream manipulator forces a floating point number to be output with its decimal point and trailing zeros?
    A. showcase
  = B. showpoint
    C. showarray
    D. noshowpoint


19. Which class file handle both file input and output?
    A. infile
    B. outfile
  = C. fstream
    D. ofstream


20. What does it mean by ofstream in C++?
    A. Delete the file.
  = B. Writes to a file.
    C. Reads from a file.
    D. Writes to a file & Reads from a file.


1. Which of the following correctly declares an array?
 = A. float rainfall[8];
   B. float rainfall;
   C. rainfall{8};
   D. rainfall[8] float;


2. Which reference modifier is used to define reference variable?
 = A. &
   B. $
   C. #
   D. >>


3. The standard output stream in C++ is represented by _______ operator.
 = A. <<
   B. >>
   C. ==
   D. %


4. The standard input stream in C++ is represented by _______ operator.
   A. <<
 = B. >>
   C. ==
   D. %


5. What will happen when we use void in argument passing?
 = A. It will not return value to its caller.
   B. It will return value to its caller.
   C. Maybe or may not be returning value to its caller.
   D. All of the above.


6. Which symbol is used to terminate a class definition?
   A. *
   B. &
 = C. };
   D. {


7. A function has been declared through the following prototype:

   float process salary (int, char);

   Which statement is true for this function?

 = A. This function returns no value.
   B. This function returns two values which are an integer and a character.
   C. During the function call, a value of type float is passed to the function.
   D. During the function call, two values are passed to the function.


8. What will be the output of the following code segment in Figure 1?

   enum Fruits {orange, apple, pear};
   Fruits Myfave = orange;
   cout << "My favorite fruit is: " <<Myfave;

   Figure 1

   A. My favorite fruit is orange
 = B. My favorite fruit is 0
   C. My favorite fruit is 1
   D. No output generator: error


9. Which the following is the correct function prototype for the function call below?

   functionABC (10, 2, 3.5) ;

   A. int functionABC(float, float, int);
   B. void functionABC(int, float, int);
 = C. void functionABC(int, int, float);
   D. void functionABC(int, float);


10. What is the output of the following code segment in Figure 2?

    #include<iostream>
    using namespace std;
    int main() {
       int a[] = {10,20,30};
       cout<<*a+1;
    }
 
    Figure 2
 
    A. 10
    B. 20
  = C. 21
    D. 11


11. If x is an integer and p and q are pointers to integers, which of the following assignments will not cause a compilation error?
    A. p = **&q;
    B. x = *&p;
  = C. q = *&x;
    D. p = &x;


12. Which the following is used to call function within a class?
    A. Member
    B. Operator
    C. Class
  = D. Method


13. What will be the output of the following code segment in Figure 3?

    void fun (int*, int*);
    int main(){
       int i=5, j=2;
        fun (&i, &j);
         cout << i << j;
        return 0;
    }
    void fun (int *i, int *j)
    {
        *i = *i**i;
        *j = *j**j;
    }
 
    Figure 3

    A. 5 2
  = B. 10 4
    C. 2 5
    D. 25 4


14. All of the following is a valid access specifier in a class EXCEPT:
    A. private
    B. public
    C. protected
  = D. encapsulated


15. How many times a derived class can inherit from a base class?
  = A. One
    B. Maximum three
    C. Maximum five
    D. More than one
```

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>




















1. OS are developed to fulfill the following set of objectives: - 

   ```
     A. free, open source, evolvability
     B. convenience, evolvability, closed source
     C. efficiency, cheap, reliable
   = D. Convenience, efficiency, ability to evolve 
   ```

<br>

2. The following components makes a whole computer environment **EXCEPT** 

   ```
     A. user
   = B. malware
     C. software
     D. hardware 
   ```

<br>

3. "Internal and external software and hardware errors“
    Which of the following aspect is fulfilled by the above statements?? 

   ```
   = A. Error detection and response
     B. Program development
     C. System Access
     D. Accounting 
   ```

<br>

4. Select the correct order of OS evolution. 

   ```
     A. Serial Processing > Multiprogramming batch system > Time sharing system > Simple batch System.
   = B. Serial Processing > Simple batch System > Multiprogramming batch system > Time sharing system.
     C. Time sharing system > Serial Processing > Multiprogramming batch system > Simple batch System.
     D. Multiprogramming batch system >Serial Processing > Time sharing system > Simple batch System. 
   ```

<br>

5. Generally, for any scheduling policies, selection functions must be based on the following criteria, **EXCEPT** 

   ```
     A. execution characteristics of process.
     B. resource requirement.
   = C. process size.
     D. priority. 
   ```

<br>

6. An operating system could employ virtual memory with the following specifications **EXCEPT** 

   ```
     A. hardware support paging
   = B. algorithm for disk scheduling
     C. hardware support segmentation
     D. algorithm for various memory management 
   ```

<br>

7. Frame could be defined as 

   ```
     A. variable-length block of secondary memory
     B. fixed-length block of secondary memory
     C. variable-length block of main memory
   = D. fixed-length block of main memory 
   ```

<br>

8. Select the relevant tables that are maintained by the operating system.
   ```
   I – Memory Table
   II – I/O Table
   III – Deadlock table
   IV – State table
   ```

   ```
     A. All of the above
     B. I, II and III only.
   = C. I and II only
     D. III and IV only 
   ```

<br>

9. Primary memory is also known as 

   ```
     A. secondary memory
     B. hard disk memory
     C. virtual memory
   = D. real memory 
   ```

<br>

10. “If a frame is locked, it may not be replaced by any incoming frames.”
    The statement above refers to the occurrence of 

    ```
    = A. frame locking
      B. starvation.
      C. deadlock
      D. livelock 
    ```

<br>

11. Which of the following is an example of non-parasitic malware? 

    ```
      A. Virus
    = B. Worms
      C. Backdoor
      D. Logic bomb 
    ```

<br>

12. The following types of scheduling are related to the 7-states Process Model **EXCEPT**  

    ```
    = A. I/O scheduling
      B. long-term scheduling
      C. short-term scheduling
      D. medium-term scheduling 
    ```

<br>

13. “Doing inefficient tasks by swapping pieces to and from main memory to secondary memory rather than executing instructions”.
    The statement above refers to 

    ```
      A. livelock
    = B. thrashing
      C. deadlock
      D. dispatcher 
    ```

<br>

14. Categorize the following machine-readable hardware correctly.
    ```
    I – External Hard Disk
    II – Sensors
    III – Keyboard
    IV – Joystick
    V – Modem 
    ```

    ```
    = A. I and II only
      B. III, IV and V only
      C. I, II and IV only
      D. III and V only 
    ```

<br>

15. In a generic File System Architecture, _________________ is considered as machine level equivalent. 

    ```
      A. basic file system
      B. indexed sequential
      C. logical Input / Output (I/O)
    = D. device drivers 
    ```

<br>

1. The following functions are all views in a computer system **EXCEPT** 

   ```
   = A. batch system.
     B. computer hardware
     C. application program
     D. utilities 
   ```

<br>

2. The following services fulfils convenience objective for operating system, **EXCEPT** 

   ```
     A. error detection and response
     B. program development
     C. accounting
   = D. I/O devices 
   ```

<br>

3. “The amount of time reserved for hardware setup for the purpose of running programs.” The given explanation best explains 

   ```
     A. installing time
   = B. setup time
     C. schedule time
     D. runtime 
   ```

<br>

4. A process could be defined as the following, **EXCEPT** 

   ```
     A. unit of activity characterized by execution of a sequence of instruction
   = B. entity that can be assigned to and executed on a memory.
     C. instance of program running on a computer
     D. program in execution. 
   ```

<br>

5. While a program is executing, it could be characterized by all the element as the following, **EXCEPT** 

   ```
   = A. thread
     B. identifier
     C. program counter
     D. accounting information 
   ```

<br>

6. Which of the following process state that is **NOT** relevant for 5-states process model? 

   ```
     A. Exit.
     B. Ready.
     C. Running.
   = D. Blocked/suspend. 
   ```

<br>

7. Select the relevant tables that are maintained by the operating system.
   ```
   I- Memory Table
   II- I/O Table
   III- Deadlock Table
   IV- State Table 
   ```

   ```
     A. I, II, III and IV.
     B. I, II and III.
   = C. I and II only.
     D. III and IV only. 
   ```

<br>

8. Atomic Operation could be defined as 

   ```
   = A. fixation or action that ensures sequence of operation to be indivisible
     B. section of code within process that request access to shared resources
     C. requirement of ensuring no two concurrent processes are in critical section at same time
     D. events occur simultaneously 
   ```

<br>

9. The following are all type of process interaction, **EXCEPT** 

   ```
     A. unaware of each other
   = B. indirectly unaware of each other
     C. directly aware of each other
     D. indirectly aware of each other 
   ```

<br>

10. Primary memory is also known as 

    ```
      A. secondary memory
      B. virtual memory
    = C. real memory
      D. hard disk memory 
    ```

<br>

11. Whenever a new process is created, a series of actions are done by OS. The following are the processes, **EXCEPT** 

    ```
      A. create or expand other data structures
      B. assigns a unique process identifier
    = C. assigning a new process state
      D. set up appropriate linkages 
    ```

<br>

12. Among all of Disk Scheduling Algorithms, _________________ chooses tracks with the minimum seek time, starting from the disk arm’s position. 

    ```
      A. SCAN
      B. C-SCAN
    = C. SSTF
      D. FIFO 
    ```

<br>

13. Which of the following that is **NOT** the common type of buffering in traditional OS? 

    ```
      A. Circular Buffer
      B. Double Buffer
    = C. Internal Buffer
      D. Single Buffer 
    ```

<br>

14. “If a frame is locked, it may not be replaced by any incoming frames.”
    The statement above refers to the occurrence of 

    ```
    = A. frame locking
      B. starvation
      C. livelock
      D. deadlock 
    ```

<br>

15. The following set of operations are commonly doable in any OS, **EXCEPT** 

    ```
      A. create
    = B. code
      C. delete
      D. write CO2 
    ```

<br>

1. In internal fragmentation, memory is internal to a partition and _________________. 

   ```
     a) is being used
   = b) is not being used
     c) is always used
     d) none of the mentioned
   ```

<br>
 
2. A solution to the problem of external fragmentation is _________________. 

   ```
   = a) compaction
     b) larger memory space
     c) smaller memory space
     d) none of the mentioned
   ```

<br>
 
3. Another solution to the problem of external fragmentation problem is to _________________. 

   ```
   = a) permit the logical address space of a process to be non-contiguous
     b) permit smaller processes to be allocated memory at last
     c) permit larger processes to be allocated memory at last
     d) all of the mentioned
   ```

<br>
 
4. _________________ is generally faster than _________________ and _________________. 

   ```
   = a) first fit, best fit, worst fit
     b) best fit, first fit, worst fit
     c) worst fit, best fit, first fit
     d) none of the mentioned
   ```

<br>

5. Consider the following page reference string.<br><br>
12342156212376321236<br><br>
For FIFO page replacement algorithms with 3 frames, the number of page faults is? 

   ```
   = a) 16
     b) 15
     c) 14
     d) 11

     ANSWER : 16
   ```

<br>

6. When will external fragmentation not occur? 

   ```
     a) first fit is used
     b) best fit is used
     c) worst fit is used
   = d) no matter which algorithm is used, it will always occur (answer)
   ```

<br>
 
7. _________________ occurs when the memory allocated to a process is slightly larger than the process. 

   ```
   = a) internal fragmentation
     b) external fragmentation
     c) both internal and external fragmentation
     d) neither internal nor external fragmentation
   ```

<br>
 
8. A process is thrashing if _________________. 

   ```
     a) it spends a lot of time executing, rather than paging
   = b) it spends a lot of time paging than executing
     c) it has no memory allocated to it
     d) none of the mentioned
   ```

<br>
 
9. When a process is copied into the main memory from the secondary memory according to the requirement. This concept refers to _________________. 

   ```
     a) Paging
   = b) Demand paging
     c) Segmentation
     d) Swapping
   ```

<br>
 
10. _________________ happens when a program tries to access a page that is mapped in address space but not loaded in physical memory. 

    ```
      a) segmentation fault occurs
      b) fatal error occurs
    = c) page fault occurs
      d) no error occurs
    ```

<br>
 
11. Why are page replacement algorithms required? 

    ```
      a) to replace pages faster
      b) to increase the page fault rate
    = c) to decrease the page fault rate
      d) to allocate multiple pages to processes
    ```

<br>
 
12. One of the replacement replacement algorithm which is the optimal replacement algorithm is considerably difficult to implement. This is because _________________. 

    ```
      a) the algorithm requires a lot of information
    = b) the algorithm requires future knowledge on the page reference
      c) the algorithm is too complex
      d) the algorithm is extremely expensive
    ```

<br>
 
13. When the memory allocated to a process is slightly larger than the process, then _________________. 

    ```
    = a) internal fragmentation occurs
      b) external fragmentation occurs
      c) both internal and external fragmentation occurs
      d) neither internal nor external fragmentation occurs
    ```

<br>
 
14. The techniques which move the program blocks to or from the physical memory is called as _________________. 

    ```
      a) Paging
    = b) Virtual memory organisation
      c) Overlays
      d) Framing
    ```

<br>
 
15. The main aim of virtual memory organisation is _________________. 

    ```
      a) To provide effective memory access
      b) To provide better memory transfer
      c) To improve the execution of the program
    = d) All of the mentioned
    ```

<br>
 
16. What is true about memory management? 

    ```
      A. Memory management keeps track of each and every memory location
      B. It decides which process will get memory at what time.
      C. It tracks whenever some memory gets freed or unallocated and correspondingly it updates the status.
    = D. All of the above
    ```

<br>
 
17. How many types of Fragmentation are there? 

    ```
    = A. 2
      B. 3
      C. 4
      D. 5
    ```

<br>
 
18. The memory management system must, therefore, allow controlled access to _________________ areas of memory without compromising essential protection. 

    ```
      a) relocated
      b) protected
    = c) shared
      d) organized
    ```

<br>
 
19. _________________ is based on the use of one or both of two basic techniques: segmentation and paging. 

    ```
      a) memory partitioning
    = b) virtual memory
      c) real memory
      d) memory organization
    ```

<br>
 
20. In _________________. there is not necessary to load all of the segments of a process and non-resident segments that are needed are brought in later automatically. 

    ```
      a) Fixed partitioning
      b) Simple Paging
    = c) Virtual memory segmentation
      d) Simple segmentation
    ```

<br>
 
21. In _________________, there is an inefficient use of memory due to internal fragmentation. 

    ```
    = a) Fixed partitioning
      b) Simple Paging
      c) Virtual memory paging
      d) Simple segmentation
    ```

<br>
 
22. In almost all modern multiprogramming systems, the principal operation of memory management involves a sophisticated scheme known as _________________. 

    ```
      a) memory partitioning
    = b) virtual memory
      c) real memory
      d) memory organization
    ```

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>


























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
