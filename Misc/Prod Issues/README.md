# Prod Issues (100)

Who hired this stupid intern?

## Solution

First download the attachment and then unzip it as it is a zip file.
Now after unzipping there will be a folder so after going into the folder use command ``ls -al`` to see for any hidden files and folders in long format.

![image1](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/main/Misc/Prod%20Issues/Images/Picture1.png?raw=true)

Now we notice a .git folder which means it is a git repository so now we will use some git commands to find the flag.

``git log`` command shows the logs of changes and version in which they were done.

Now there are three different versions. 
We can shift version using ``git checkout`` command.

Now after shifting to another version i can see all the changes done in this version.

Now i will see contents of file “flag.txt”.

The flag seems to be in ROT13. 

## Flag
CCTF{g1t_g0t_Iss3es_ROT13}
