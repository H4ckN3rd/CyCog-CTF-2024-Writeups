# Rabbit Hole

Download the file attachment and use “file” command to see which type of file it is.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/cc355c6be7e8b98a4a8d27ef398949eae9eab82d/Reverse%20Engineering/Rabbit%20Hole/Images/Picture1.png)

## Solution

Let’s to ``“chmod +x Rabbit_Hole”`` to give the file executable permissions and run it. After running it starts printing table of inputted number (even -ve ones).

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/cc355c6be7e8b98a4a8d27ef398949eae9eab82d/Reverse%20Engineering/Rabbit%20Hole/Images/Picture2.png)

Nothing interseting!!!! 

Let’s try seeing its contents using “cat” command.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/cc355c6be7e8b98a4a8d27ef398949eae9eab82d/Reverse%20Engineering/Rabbit%20Hole/Images/Picture3.png)

Now in this confusing we found something....

Enter the password and password is written (Pa&&W0Rd) may be in input entering it would give us something....

After entering password directly in input it was an infinite loop so let’s start entering number 1 to 10  (Bruteforce 1 to 10) . At 10 it asks for password and we enter the password.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/cc355c6be7e8b98a4a8d27ef398949eae9eab82d/Reverse%20Engineering/Rabbit%20Hole/Images/Picture4.png)

It gives us some ascii values. But i don’t know which type of ascii values so i will brute force it.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/cc355c6be7e8b98a4a8d27ef398949eae9eab82d/Reverse%20Engineering/Rabbit%20Hole/Images/Picture5.png)

So only first one in brute fortce is right and looks like a base64.

So we will use command ``(echo "Q0NURntSNGJiMXRfSDBsZV9EMXNjMHYzcjNkfQ==" | base64 -d)`` to decode base64.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/cc355c6be7e8b98a4a8d27ef398949eae9eab82d/Reverse%20Engineering/Rabbit%20Hole/Images/Picture6.png)

## Flag
CCTF{R4bb1t_H0le_D1sc0v3r3d} 
