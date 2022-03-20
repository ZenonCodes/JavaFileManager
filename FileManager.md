# FileManager

The File Manager consists of the following commands:
- _**list:**_ a folder
- _**info:**_ on a file
- **_mkdir:_** make a new folder
- _**rename:**_ a file
- _**copy**_, _**move**_, _**delete:**_ files
- _**quit:**_ the file manager shell


## The *list* command:
> This command takes 1 parameter: a string indicating the file path. 
> It then checks two conditions. The first condition is whether the path exists and the second condition is whether the path is a directory. If both conditions are true and the folder is not empty, then the method iterates through the strings or file names and prints them to the console.
>- _**The list command gives a user a clear view of what contents are contained within a path in addition to whether the path exists.**_

## The *info* command:
> This command takes one parameter: a string indicating the file or folder's path. It returns the name, relative path, absolute path, size, and time of last modification for a file or a folder. 
>- _**The info command gives a user more ample information with which accurately to search, organize, and identify files/folders.**_ 
## The *mkdir* command:
> This command takes one parameter: a string indicating the desired name of the new folder and creates it under the following conditions:
 >1. The intended name does not contain any illegal characters. 
 >2. The intended name is not already in use by an existing file or folder.
 >3. If for some other reason the method cannot create a folder it catches the exception.
 >- **_The info command gives a user the ability to create new folders/files with built-in safeguards._**

## The *rename* command:
>The rename command allows you to modify the name of an existing file/folder. If no such file/folder exists the method notifies the user. 
>- **_There are several reasons a user may want to rename a folder/file, whatever they may be the rename method allows one to do so with ease._**

## The *copy/move/delete* command:
> The copy command creates a duplicate of a file in a requested path. The move command transfers a file from one path to another. While the delete command removes a file from a specified path.  
>- **_The copy command is recommended if you want to create a duplicate file in a new path while the move command is recommended if you want to move the original file. The delete command allows a user to remove a file they no longer need nor want from a specified path._**

## The *quit* command:
> Allows the user to terminate their session with the file manager. 

