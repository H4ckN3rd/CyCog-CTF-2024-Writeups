# Above Average

Donwload the given attachment.

## Solution

First run the code which is like the most obvious thing a person do.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/0d67dd61d7de831cc336e8d1581061fde05ba375/Reverse%20Engineering/Above%20Average/Images/Picture1.png)

Didn’t find anything interseting. So now let’s see the code.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/0d67dd61d7de831cc336e8d1581061fde05ba375/Reverse%20Engineering/Above%20Average/Images/Picture2.png)

In this code we can clearly see decode which can give us the flag is not being called so let’s change the script.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/0d67dd61d7de831cc336e8d1581061fde05ba375/Reverse%20Engineering/Above%20Average/Images/Picture3.png)

Add the function decode() with  the variabe as it was not being called.
Now after saving and running it. We get :-

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/0d67dd61d7de831cc336e8d1581061fde05ba375/Reverse%20Engineering/Above%20Average/Images/Picture4.png)

## Flag
CCTF{Hav3_u_Tr13d_rUnN1ng_7he_fUnct10n}
