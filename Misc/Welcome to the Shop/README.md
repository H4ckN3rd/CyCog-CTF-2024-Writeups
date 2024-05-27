# Welcome to the Shop (150)

Our return policy allows customers to purchase items with the confidence that they can return them for a refund if necessary. We offer a hassle-free return process for all eligible products.

## Solution

First download the file and use ``file`` command to determine type of the file.

![image](https://github.com/joykhaneja/CyCog-CTF-2024-Writeups/blob/02b2a8f915d0c823eb31de40e70a750f542ec83f/Misc/Welcome%20to%20the%20Shop/Images/Picture1.png)

Now we can see it is an executable file so now we have to change permissions using ``chmod`` command and simply run it.
Now it will show something like this :- 

Now we add any number and we will notice that it is just a normal menu drive program so now let’s try entering any negative number.

After adding negative character we can see that our coins increased and now we can buy a flag so in short in this question entering any negative number in quantity columns will increase the coins instead of decreasing them.

```
Flag: [67 67 84 70 123 98 52 100 95 98 114 111 103 114 97 109 109 101 114 125]
```
Now we can see that these are ascii values so we'll convert it to get the actual flag.


## Flag
CCTF{b4d_brogrammer}
