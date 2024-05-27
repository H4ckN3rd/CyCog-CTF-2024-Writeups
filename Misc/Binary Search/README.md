# Binary Search (150)

Binary Search...Naam toh suna hee hoga...

## Solution

Again after downloading we used ``file`` command and came to know that file is executable.
Now we simply change permssions and run the program and some output is displayed.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/assets/126105931/2601bbd2-2319-4f72-b4b3-412bb59f96bc)

Now binary search means there are two values one is known is high and another is known as low and it’s mid value is (high+low)/2   and basically we have to guess right mid value.
Now let’s say start guessing...

1st guess = 500

2nd Guess = 250

3rd Guess = 375

4th Guess = 437

5th Guess = 406

6th Guess = 421

7th Guess = 429

8th Guess = 433

9th Guess = 435

Now we can see that the flag is in base64 format. So, Now we can use below mentioned way to convert base64 to normal text.




## Flag
CCTF{B1n4ry_S34r(h}
