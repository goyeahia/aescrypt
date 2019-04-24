# Aescrypt
An open source encrytion tool for security concerned people. 
## Overview
Aescrypt is a simple user friendly data encryption tool which encrypts & decrypts files with strong encryption algorithm. Sometimes we often need to store our document securely after wiritng but we don't have much time for encrytion or privacy. That's why we can use this simple  tool to automatically save and encrypt our documents.
## Usage
- Open up your linux terminal or windows command promt
- To create a new document or text file, type the command as below
~~~ 
python nabcrypt newfilename.txt
~~~
- To encrypt old text file or any kinds of file make sure that the exisiting file or document you want to encrypt it is in the same directory or folder. To encrypt, type in the terminal
~~~
python aescrypt filename
~~~
- To decrypt any document or any text files,make sure the file ends with nab extension. Now type in the terminal
~~~
python aescrypt filename.nab
~~~
## Technical Details
- Algorithm : Aescrypt uses the popular 256 - AES algorithm. The Advanced Encryption Standard (AES) is a symmetric-key block cipher algorithm and U.S. government standard for secure and classified data encryption and decryption.The AES has three fixed 128-bit block ciphers with cryptographic key sizes of 128, 192 and 256 bits. Key size is unlimited, whereas the block size maximum is 256 bits. The AES design is based on a substitution-permutation network (SPN) and does not use the Data Encryption Standard (DES) Feistel network.[Click here for more details](https://www.techopedia.com/definition/1763/advanced-encryption-standard-aes)
- Key Source : Aescrypt uses password based key derivation technique to get the a strong key generated by a password. It uses SHA - 512 as main hash algorithm and md5 as salt. 
## Author
[Yeahia Sarker](https://www.linkedin.com/in/goyeahia/)
<br>
Warning :
If you forget the password of encryption then all of your data are gone. This tool usage password based key derivation technique to generate key for encryption.
So remember your password. Yeah i know it's difficult. That's why i am building another tool for managing passwords ! "
