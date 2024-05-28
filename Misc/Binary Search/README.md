# Binary Search (150)

Binary Search...Naam toh suna hee hoga...

## Solution

Again after downloading we used ``file`` command and came to know that file is executable.
Now we simply change permssions and run the program and some output is displayed.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/main/Misc/Binary%20Search/Images/Picture1.png?raw=true)

Now binary search means there are two values one is known is high and another is known as low and it’s mid value is (high+low)/2   and basically we have to guess right mid value.
Now let’s say start guessing...

1st guess = 500

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/main/Misc/Binary%20Search/Images/Picture2.png?raw=true)

2nd Guess = 250

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/main/Misc/Binary%20Search/Images/Picture3.png?raw=true)

3rd Guess = 375

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/assets/126105931/64c9423a-3b37-48d5-ad38-914ccc5ea263)

4th Guess = 437

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/main/Misc/Binary%20Search/Images/Picture5.png?raw=true)

5th Guess = 406

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/main/Misc/Binary%20Search/Images/Picture6.png?raw=true)

6th Guess = 421

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/main/Misc/Binary%20Search/Images/Picture7.png?raw=true)

7th Guess = 429

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/main/Misc/Binary%20Search/Images/Picture8.png?raw=true)

8th Guess = 433

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/main/Misc/Binary%20Search/Images/Picture9.png?raw=true)

9th Guess = 435

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/assets/126105931/31d11c39-b657-4bd4-9214-133b3fbd691a)


Now we can see that the flag is in base64 format. So, Now we can use below mentioned way to convert base64 to normal text.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/assets/126105931/185baca4-e697-44ab-9caf-1c44d1920cca)

## Flag
CCTF{B1n4ry_S34r(h}
