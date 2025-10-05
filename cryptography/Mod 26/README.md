# Mod 26 – Cryptography Challenge

## Challenge Description

We are given the following ciphertext:

```
cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_uJdSftmh}
```

The challenge hints at **ROT13**, a Caesar cipher variant that shifts each letter by 13 positions in the alphabet.

---

## Solution

### Step 1: Understanding the Cipher

- **ROT13** is a simple letter substitution cipher that replaces each letter with the 13th letter after it in the alphabet.
- Applying ROT13 twice restores the original text (since 13+13=26, the alphabet length).

### Step 2: Decoding the Ciphertext

- Tools like [CyberChef](https://gchq.github.io/CyberChef/) or online ROT13 decoders can be used.
- Input the ciphertext into a ROT13 decoder.

**Ciphertext:**
```
cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_uJdSftmh}
```

**Decoded Text:**
```
picoCTF{next_time_I'll_try_2_rounds_of_rot13_hWqFsgzu}
```

---

## Flag

```
picoCTF{next_time_I'll_try_2_rounds_of_rot13_hWqFsgzu}
```

---

## Summary

- **Cipher Used:** ROT13
- **Tool Used:** CyberChef / Online ROT13 Decoder
- **Approach:** Substituted each letter using ROT13 to reveal the flag.

---

**References:**
- [ROT13 – Wikipedia](https://en.wikipedia.org/wiki/ROT13)
- [CyberChef – GCHQ](https://gchq.github.io/CyberChef/)
