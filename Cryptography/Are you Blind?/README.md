# Are you blind? (150)

I hope you can see me

``
⠒⠲⠀⠖⠢⠀⠢⠢⠀⠒⠦⠀⠖⠙⠀⠖⠙⠀⠒⠖⠀⠲⠆⠀⠶⠖⠀⠖⠙⠀⠶⠢⠀⠖⠦⠀⠒⠒⠀⠢⠖⠀⠲⠃⠀⠶⠔⠀⠒⠶⠀⠲⠃⠀⠒⠖⠀⠲⠉⠀⠢⠔⠀⠶⠴⠀⠶⠖⠀⠲⠉⠀⠖⠔⠀⠖⠶⠀⠲⠁⠀⠢⠒⠀⠢⠁⠀⠢⠆⠀⠢⠢⠀⠖⠲⠀⠶⠁⠀⠒⠖⠀⠲⠒⠀⠲⠲⠀⠒⠦⠀⠲⠙⠀⠒⠖⠀⠲⠉
``

## Solution

Downlaod the attachment.

I don’t know what these dots are so i randomly searched the text and first website said that it is braille. SO now use any online braille translator to decode the same.

From Braille we get:

``
34 65 55 38 6D 6D 36 42 76 6D 75 68 33 56 4B 79 37 4B 36 4C 59 70 76 4C 69 67 4A 53 5A 52 55 64 7A 36 43 44 38 4D 36 4C
``

This seems to be hexadecimal.

From deciphering using hex,  we get:

``
4eU8mm6Bvmuh3VKy7K6LYpvLigJSZRUdz6CD8M6L
``

Then by checking from various base ciphers, we get to know that is Base58.
From Base58, we get:

``
PPGS{GU4AX_T0Q_H_E_A0G_OY1AQ}
``

It seems like the flag has been ROT-ed, from ROT13 we finally get the flag.

## Flag
CCTF{TH4NK_G0D_U_R_N0T_BL1ND}
