Challenge Name: Mod 26
Category: Cryptography

  #Challenge Description

We are given the following ciphertext:
cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_uJdSftmh}
The challenge hints at ROT13, which is a Caesar cipher with a shift of 13.

#Solution Overview
From the description, it’s clear that ROT13 is the key to solving this. ROT13 substitutes each letter with the one 13 positions further in the alphabet.
I used the CyberChef tool to decode it.

Input: cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_uJdSftmh}
The decoded text revealed the flag.
-> picoCTF{next_time_I'll_try_2_rounds_of_rot13_hWqFsgzu}

