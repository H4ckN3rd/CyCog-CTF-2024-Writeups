# Prod Issues (100)

Who hired this stupid intern?

## Solution

First download the attachment and then unzip it as it is a zip file.
Now after unzipping there will be a folder so after going into the folder use command ``ls -al`` to see for any hidden files and folders in long format.

![image1](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/main/Misc/Prod%20Issues/Images/Picture1.png?raw=true)

Now we notice a .git folder which means it is a git repository so now we will use some git commands to find the flag.

``git log`` command shows the logs of changes and version in which they were done.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/assets/126105931/a6d14f87-576f-44b9-9fb0-90ffc735e003)


Now there are three different versions. 
We can shift version using ``git checkout`` command.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/assets/126105931/abd842d3-db99-4b02-bdb0-2cc0b294d7ff)

Now after shifting to another version i can see all the changes done in this version.

Now i will see contents of file “flag.txt”.

The flag seems to be in ROT13. 

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/assets/126105931/b1e46022-f7c6-471b-8c38-245dc633d19d)

## Flag
CCTF{g1t_g0t_Iss3es_ROT13}
