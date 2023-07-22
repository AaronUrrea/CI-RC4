## CI-RC4 - Aaron Urrea
 - Course: COMP-424 Computer System Security
 - Professor: Sami Al-Salman

# RC4 Algorithm Implementation

## Description
This is a Python3 program that implements the RC4 algorithm for encryption and decryption. RC4 (Rivest Cipher 4) is a symmetric stream cipher widely used in various applications like secure communications over networks.

## Purpose
The purpose of this program is to demonstrate how the RC4 algorithm works and to showcase its encryption and decryption process using a given plaintext and key.

## Implementation
The implementation of the RC4 algorithm involves the following steps:
1. Setting up the initial state vector array (S).
2. Generating the key stream using the Key Scheduling Algorithm (KSA).
3. Performing the Pseudo-Random Generation Algorithm (PGRA) to generate the key stream.
4. Encrypting the plaintext using XOR operation with the key stream to produce the ciphertext.
5. Decrypting the ciphertext back to the original plaintext using XOR operation with the key stream.

## Usage
To use the program, you can modify the `plain_text` and `key` variables in the `encryption()` function with your desired plaintext and key. Then, run the program to see the encryption and decryption results.

## How to Run the Program
1. Clone the repository to your local machine.
2. Open a terminal and navigate to the project directory.
3. Run the program using the Python3 interpreter:

## Sample Output
After running the program, you will see the plaintext, key, initial state vector array (S), KSA iterations, PGRA iterations, key stream, and the ciphertext.

## Contributions
Contributions to this project are welcome. Feel free to fork this repository, make changes, and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
