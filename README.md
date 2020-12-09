# Caesar-Cipher-Encryption
The code contain a function for all methametics behind the encryption, the program takes two inputs
1- a text for encryption
2- an encryption key (int) between 1-26

The encryption is done with standard Unicode for the characters in the text.
The function "encrypt" takes two parameters text and key. The function split the text into words (stored in the string variable) 
then for each word the function split further into characters. then order of the character finds using "ord()" function, the 
values added up to the keys to have the encrypted character.
All the encrypted characters are concatenate at the end for proper formate.
