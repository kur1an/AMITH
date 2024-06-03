# Caesar Cipher Encryption and Decryption

## Theory, Concept, and Logic

### Caesar Cipher

The Caesar Cipher is one of the simplest and most widely known encryption techniques. It is a substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

#### Encryption Process

1. **Shift Letters**: Each letter in the plaintext is shifted by a fixed number of positions down the alphabet.
2. **Wrapping**: If the shift extends past 'z', it wraps around to the beginning of the alphabet.
3. **Maintaining Case**: Preserve the case (uppercase or lowercase) of each letter in the plaintext.

#### Decryption Process

1. **Reverse Shift**: Each letter in the ciphertext is shifted back by the same number of positions to recover the original plaintext.
2. **Handling Wrapping**: If the shift extends past 'a', it wraps around to the end of the alphabet.

### Implementation Logic

1. **Alphabet Representation**: The alphabet is represented as a string of lowercase letters.
2. **Encryption Function**: Each letter in the plaintext is shifted by the specified key using modular arithmetic.
3. **Decryption Function**: Each letter in the ciphertext is shifted back by the specified key to recover the original plaintext.
