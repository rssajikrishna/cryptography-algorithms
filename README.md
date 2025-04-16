# cryptography-algorithms

Welcome to the **Classical Ciphers** collection written in **C language**. This repository serves as an educational resource for understanding the implementation and working of various classical encryption techniques used in cryptography.

---

## 📜 Ciphers Included

| Cipher | Description |
|--------|-------------|
| **Affine Cipher** | A type of monoalphabetic substitution cipher using mathematical functions. |
| **Atbash Cipher** | A simple substitution cipher where letters are reversed (A ↔ Z, B ↔ Y, etc.). |
| **Autokey Cipher** | A polyalphabetic cipher that uses the plaintext to extend the key. |
| **Beaufort Cipher** | Similar to the Vigenère cipher but with a different encryption algorithm. |
| **Caesar Cipher** | One of the oldest and simplest ciphers, using a fixed shift. |
| **Columnar Cipher** | A transposition cipher that writes plaintext into columns based on a keyword. |
| **Double Transpositional Cipher** | Encrypts the plaintext by performing two successive transpositions. |
| **Gronsfeld Cipher** | A variation of the Vigenère cipher using digits as the key. |
| **Hill Cipher** | A polygraphic cipher based on linear algebra and matrix multiplication. |
| **Myszkowski Cipher** | A transposition cipher that handles repeated keyword characters uniquely. |
| **Rail Fence Cipher** | A form of transposition cipher that arranges text in a zigzag pattern. |
| **Route Cipher** | Encrypts text by placing it in a grid and reading in a specific pattern. |
| **Running Key Cipher** | Uses a long passage of text as the key, typically from a book. |
| **Vigenère Cipher** | A famous polyalphabetic cipher that uses a keyword to shift letters. |

---

## 📂 File Structure

Each cipher has its own `.c` file and contains:

- Clear input prompts
- Encryption and decryption functions
- Example usage in `main()`
- Comments for easy understanding

---

## 🚀 Getting Started

### 🔧 Compile and Run

```bash
gcc caesar_cipher.c -o caesar_cipher
./caesar_cipher
