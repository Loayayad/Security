# Security

This program support encryption and decryption using shift, affine, and vigenere ciphers.

it can be  callable from command line as follows:

◦ First argument is the cipher type [“shift”,”affine”,”vigenere”].

◦ Second argument is the operation type [“encrypt”, “decrypt”].

◦ The Third argument is the name of input file.(without adding txt, it already handled in the program)
  which must be created before running the program or it will raises I/O error

◦ The fourth argument is the name of output file.(without adding txt, it already handled in the program)
  the program creates the file with the output file name entered in the cmd if the file does not exists.

◦ The last argument is the the list of encryption keys required for the cipher. 
    - one key for shift cipher
    - two keys for affine cipher
    - A string key for vigenere cipher

• Examples calls from terminal:

◦ cipher.py affine decrypt input output a b

◦ cipher.py shift encrypt input output a 

◦ cipher.py vigenere decrypt input output string


