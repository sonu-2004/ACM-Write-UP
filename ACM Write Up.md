***ACM Write Up***

*GENERAL SKILLS*

**Wave a flag**

In my terminal I ran the given program by <a name="_int_gysdbxcq"></a>typing ./warm and then <a name="_int_qua6db1w"></a>typed ./<a name="_int_yfimmhef"></a>warm -h to get more information regarding the file, it displayed the flag.

I learned how to run a program in terminal and get more information regarding the file

**Nice netcat...**

I ran the command given in the description of the task in terminal and I got many numbers. I thought it might be ASCII values. I went into this site: <https://www.duplichecker.com/ascii-to-text.php> to convert ASCII values to text, then after conversion I got the flag.

I learned how to convert ASCII values into text

*Cryptography*

**Mod 26**

I searched for ROT13 <a name="_int_4ime26da"></a>in google, I went to this site: <https://www.dcode.fr/rot-13-cipher> and pasted the text given in the description of the task over there and decrypted it. <a name="_int_emrnvv2q"></a>So I got the flag after decrypting.

I learned many types of ROT ciphers and to decrypt something using it

**Mind your Ps and Qs**

I searched for RSA decryption in google and got into this site: <https://www.dcode.fr/rsa-cipher> where I pasted the values of <a name="_int_y8pyqlhe"></a>C,E and N according to the file given in description of the task and when tried to decrypt it, I got the flag.

Learned more about RSA decryption

*Forensics*

**Information**

I used exiftool in terminal to get the details of the image given. I found that in <a name="_int_nuiwen2w"></a>license part of the details it was some <a name="_int_vahd8ygw"></a>text so I tried to decode it online. I decoded it in this site: <https://www.base64decode.org/> and the flag was available after decoding

Learned to use exiftool command in terminal and get the details of given file
### **Matryoshka doll**
As in the description of the task Matryoshka doll is a doll inside which another doll can be found and goes on, we need to unbox each doll which we find inside the doll. <a name="_int_fblrfvu6"></a>So I thought of extracting the image multiple times to get the flag. I used binwalk –e command to extract files from the image. After using the command 4-5 times I got a file named as flag.txt, inside the file flag was given

Learned to use binwalk command in terminal and extract files
