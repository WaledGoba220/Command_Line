# Command_Line
Command Line Commands

# Background:

The command line is a text interface for your computer. It’s a program that takes in commands, which it passes on to the computer’s operating system to run.

From the command line, you can navigate through files and folders on your computer, just as you would with Windows Explorer on Windows or Finder on Mac OS. The 

difference is that the command line is fully text-based.

Here’s an appendix of commonly used commands.



▶  Command Line 

Shell ➼ Command Line Interpreter 
Terminal ➼ Text Input & Output environment
CMD ➼ The Original Shell for Microsoft Dos Operating System
PowerShell  ➼ After CMD 


Why to Use ? 
-	Use less  System Resources 
-	Complete Paths and  Commands 
-	Same Like Code
-	Very Important in Software System 
-	Very Important for Companies to Work 
-	Deal With Package manager 
-	Use Git Commands 
-	Commands is Commands Nothing Change
-	Increase Writing Speed 


Example : 

☑  IP Config 

☑ Move all Text in Subdirectories 

☑ Delete Files with Extensions 

☑ Change Settings Quickly 

☑ Edit System Files Quickly

☑ Create many Directories At Once 

                                                                 ====================
                                                                 
                                                                 
     
==➽  ipconfig 

✓  Get Ip Of device and Subnet mask (Information of IP)

✓ ping	➙ pings the network

                                                                  ====================
                                                                                                                             
     
==➽ Change Color

✓  color -help

                                                                   ====================
                                                                    
 
==➽   Change Command title

✓  title sys  ➙  change cmd title to sys

                                                                   ====================
                                                                   

   ==➽  explorer
   
✓  explorer .  ➙  go to the file location
                                                     
                                                                    ====================
                                                                    

==➽  cls

✓  cls   ➙  cls == Clear delete all

                                                                    ====================
                                                                    

==➽  dir

✓  dir .  ➙  Show folders Paths
                                                                    ====================
                                                                    
==➽  mkdir

✓  mkdir D:\sys .  ➙ create file named sys

                                                                     ====================
                                                                     
                                                                     
==➽  cd
 
✓  cd  D: .  ➙ Path is D > go to the Path

==➽ cd ..

✓  cd ..  ➙ back one on path
                                         
                                                                     ====================
                                                                      
                                                               
==➽  move

✓  دا ك امر لية فايدتين يقدر يحذف ويعدل عالاسم

Move sys ➙ Delete 

Move sys system ➙ Rename 

rmdir / rd	➙ delete directory

** طيب لو انا عاوز اغيرو لاسم والاسم دا موجود بالفعل --- هنا بقي هيعمل نقل للملف  لان بالتاكيد هو موجود** 



==➽ rename

✓ rename sys doc ➙  تغير اسم الملف 

✓ replace	 ➙ replace files  

                                                                      ====================
                                                                      
✓ echo ➙	text output

✓ date ➙	show/set date

✓ exit ➙	exits the command prompt or a batch file

✓ time ➙	display/edit the system time

✓ timeout ➙	wait any time

✓ type ➙	display content of text files

✓ copy / xcopy ➙	copy files

                                                                  ====================
                                                                  

✓ ftp	➙ transfer files to a FTP server

✓ ftype ➙	display file type and mapping

✓ tftp ➙ transfer files to a TFTP server

✓ tracert ➙	trace routes similar to patchping

✓ comp ➙ compare file contents

✓ compact ➙	display/change file compression

✓ expand ➙extract files

✓ fc ➙copare files and display the differences

✓ tree ➙	display folder structure graphically

✓ format ➙	format volumes

✓ label ➙	change volume name

✓ mode ➙ configure interfaces/devices

✓ mountvol ➙ assign/delete drive mountpoints

✓ verify ➙ monitoring whether volumes are written correctly

✓ vol	show ➙ volume description and serial numbers of the HDDs

✓ hostname ➙	display host name

✓ shutdown ➙	shutdown the computer

✓ sort ➙	sort the screen output

✓ start ➙	start an own window to execute a program or command

✓ call ➙	calls a batch file from another one

✓ pause ➙	pauses the execution of a batch file and shows a message

                                                                ====================
                                                                
                                                               
C:\> type file.txt 


### Create files:

C:\> echo "line from file1" > file1.txt
C:\> echo "line from file2" > file2.txt


### Concatenate files:

C:\> type file1.txt file2.txt > result.txt
C:\> type result.txt
line from file1
line from file2

                                                               
                                                              ====================
                                                              
                                                              
 ### Grep the output of a netstat command for a specific port:

#### Windows CMD
C:\> netstat -na | findstr /c:"PORT"

####  Windows PowerShell
PS C:\> netstat -na | Select-String "PORT"                                                            
                                                              

### Grep a file for a pattern that matches a regular expression (case insensitive):

#### Windows CMD
C:\> findstr /i /r /c:"^SEARCH.*STRING$" file.txt

#### Windows PowerShell
PS C:\> Select-String "^SEARCH.*STRING$" file.txt

                                                              ====================
                                                              
## DOS Commands Help

✓ You can display all available commands with the help command




In the 1960s, using only computer terminals, this was the only way to interact with computers.
In the 1970s an 1980s, command line input was commonly used by Unix systems and PC systems like MS-DOS and Apple DOS.
Today, with graphical user interfaces (GUI), most users never use command-line interfaces (CLI).
However, CLI is still used by software developers and system administrators to configure computers, install software, and access features that are not available in the graphical interface.

#### It is possible to use cymder instead of CMD Especially since it has better looking screen features than it
