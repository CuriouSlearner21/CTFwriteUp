 Challenge Name: Disko1  

Category: Digital Forensics  
Points: 100  
Difficulty: Easy  

#Challenge Description  
In this challenge, we are given a compressed disk image file `disko-1.dd.gz`.
The hint provided was *strings*, which suggested the use of the `strings` utility to extract readable text from the raw disk image.  

  
 

#Solution Overview  
1. First, I downloaded the provided file `disko-1.dd.gz`. Since it was a compressed `.gz` file, I decompressed it using:  
   gunzip disko-1.dd.gz



3. Next, following the hint strings, I ran the strings command to extract human-readable text from the disk image. To narrow down the results,
   I piped the output into grep to search for the keyword strings
   strings disko-1.dd | grep -i picoctf

4. The command revealed the hidden file
    picoCTF{1t5_ju5t_4_5tr1n9_e3408eef}


