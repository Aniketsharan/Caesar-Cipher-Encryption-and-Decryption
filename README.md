# Caesar-Cipher-Encryption-and-Decryption
This C++ program implements a simple Caesar Cipher encryption and decryption algorithm. The Caesar Cipher is a substitution cipher where each letter in the plaintext is shifted a certain number of positions to the right (for encryption) or left (for decryption) to produce the ciphertext.
# How It Works
The program takes the following steps:

1. User Input: The user is prompted to choose between encryption ('encode') or decryption ('decode') and provides the message to be processed and the number of shifts.

2. Encryption Function: The Encrypt function iterates through each character in the input message and shifts the ASCII value to the right by the given number of shifts. If the shift exceeds the letter 'Z' or 'z', the alphabet cycles back to 'A' or 'a'.

3. Decryption Function: The Decrypt function performs the opposite process by shifting the ASCII value to the left by the given number of shifts. If the shift preceeds 'A' or 'a', the alphabet cycles back to 'Z' or 'z'.

4. Output: The program displays the encoded or decoded message based on the user's choice.
