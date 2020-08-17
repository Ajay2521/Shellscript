# Shellscript
In this Shellscript programming language which is used in Unix / Linux has been explained.

<p align="center">

<img width="200" height="200" src="https://user-images.githubusercontent.com/60919132/90394617-99f41e80-e0b0-11ea-8062-4722e9fb2124.jpg" >

</p>
 
### What is Unix / Linux ?

  Unix/Linux is an operating system like windows or IOS. The computer programs that allocate the system resources and coordinate all the details of the computer's internals is called the "operating system" or the "kernel". Unix was developed during 1969 by AT & T Bell labs by Dennis Ritchie, Douglas Mcllroy ,Ken Thompson and Joe Ossanna.
  
  Unix was orginally developed to handle multiple activities from multiple users at the same time.Thus unix was famously known as "Multiuser System" and "Multitasking System".
  
### What is Shell ?

  The program which is used to allow the user to communicate with the "Kernel" is called as "Shell".Shell is an command line interpreter which is used to translates commands entered by the user to the complier language which will be understand by the kernel.
  
### Working with vi editor.!

- Open the Unix/Linux terminal.
  
- vi FileName.FileType = used to open a vi editor with the specific filename which is mentioned. Here FileName is the name of the file and FileType is the type of the file in which file has to be created.

- After opening the vi editor press " i " which is used to enter into "Edit mode" / "Insert mode".

- After the work has done then press "esc" button and type ":qw" to exit the vi editor by saving the file.

- To open the file again just type "vi FileName.FileType" again in the terminal.

- To display the file content in the terminal then type "cat FileName.FileType".

- To excute a shellscript file then first change the mode of the file by typing "chmod +x FileName.sh" in the terminal.

- Then after changing the file mode type "./FileName.sh" to excute the program or instruction present in the specific script file.

