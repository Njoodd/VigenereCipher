# Vigenere Cipher

## King Saud University - College of Computer and Information Sciences
## Information Systems Department
Course: Security - IS493 </br>
Supervisor: Ms. Afnan Alsadhan

Projected done by:
- Najoud Alhajery
- Amjad Althinyyan
- Norah Alsuwailem
- Lamia Alfawzan


### Description:
The keyword method of the Vigenere cipher encrypts a message using an agreed upon key by the sender and receiver. The keyword can be of any length greater than one, which provides an unlimited number of possible keys. To form the key, the sender writes the keyword repeatedly on the line underneath the plaintext, then the sender will use the plaintext and corresponding key letter to select a row and a column in the Vigenère square. A ciphertext letter will be the letter that appears in the Vigenère square at the intersecting position of the selected row and  column [1].


### How it works
Constraints:
Input must be characters from A-Z.

#### Encryption
In this section, the user enters the text they want to encrypt in the plaintext field and the key in the key field, and then click the Encrypt button. A table will pop up showing how every character got encrypted. Finally, the result will be shown in the ciphertext field.

#### Decryption
In this section, the user enters the text they want to decrypt in the ciphertext field and the key in the key field, and then click the Decrypt button. A table will pop up showing how every character got decrypted. Finally, The result will be shown in the plaintext field.

