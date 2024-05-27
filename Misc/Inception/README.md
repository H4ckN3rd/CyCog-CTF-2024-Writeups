# Inception

First Download all the attachments. For this challenge we will be using john.
First we will use “zip2john” command to create a hash for the zip file.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/02b2a8f915d0c823eb31de40e70a750f542ec83f/Misc/Welcome%20to%20the%20Shop/Images/Picture1.png)

Now we will use command like “john zip.hash -wordlist=rockyou.txt”

Now 1st password is “roscommonboys”.
Now after extracting we get another zip file by name “zippsy_extract_1.zip”.

Now we will repeat same above process several times until we get a text file that contains a flag.

``Step-1`` (use “zip2john” command to create hash”)

``Step-2`` (now use “john <hash_name> -wordlist=rockyou.txt” until you get the text file containing flag)

2nd password = maximus (zippsy_extract_1.zip)

3rd password = cedric (zippsy_extract_2.zip)

4th password = bigdog (zippsy_extract_3.zip)

5th password = declan (zippsy_extract_4.zip)

6th password = forever21 (zippsy_extract_5.zip

After extracting “zippsy_extract_5.zip”we got a text file by the name “flag”


