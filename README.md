<h2>Cryptography</h2>

Cryptography is a technique of securing communication by converting plain text into ciphertext. It involves various algorithms and protocols to ensure data.
<br>
In Cryptography, the techniques that are used to protect information are done by algorithms to convert messages in ways that make it hard to decode them.
<br><br>
There are mainly three types of Cryptography:
<ul>
    <li><b>Symmetric Cryptography</b></li>
    <li><b>Asymmetric Cryptography</b></li>
    <li><b>Hashing</b></li>
</ul>

<div>
<h2><b>Symmetric Cryptography</b></h2>

Symmetric Key cryptography is an encryption methodology where the sender and receiver use a single common key to encrypt and decrypt messages.
<br>
The most popular symmetric key cryptography systems are Data Encryption Systems (DES) and Advanced Encryption Systems (AES).
<br>

<h3><b>Data Encryption Standard (DES)</b></h3>

Data Encryption Standard (DES) is a block cipher with a 56-bit key length that has played a significant role in data security. DES is a block cipher that encrypts data in blocks of size 64 bits each, where 64 bits of plain text go as the input to the DES algorithm and produce 64 bits of ciphertext. The same algorithm and key (public) are used for encryption and decryption, with minor differences.

<h3><b>Advanced Encryption Standard (AES)</b></h3>

Advanced Encryption Standard (AES) is a Block Cipher and key size can be 128/192/256 bits, which encrypts data in blocks of 128 bits each. That means it takes 128 bits as input and outputs 128 bits of encrypted ciphertext. The same algorithm and key (public) are used for encryption and decryption, with minor differences.

</div>

<div>
<h2><b>Asymmetric Cryptography</b></h2>

In Asymmetric Key Cryptography, a pair of keys is used to encrypt and decrypt information. A receiver’s public key is used for encryption, and a receiver’s private key is used for decryption. Public keys and Private keys are different. Even if the public key is known by everyone, the intended receiver can only decode it because he alone knows his private key.
<br>
The most popular asymmetric key cryptography algorithm is the RSA algorithm.

<h3><b>Rivest-Shamir-Adleman (RSA)</b></h3>

The RSA algorithm is an asymmetric cryptography algorithm. Asymmetric actually means that it works on two different keys, i.e., Public Key and Private Key. As the name describes, the Public Key is given to everyone, and the Private key is kept private.
<br>
The RSA algorithm can be used for Digital Signatures, which means that a sender can sign a message using their private key, and the receiver can verify the signature using the sender’s public key.

<h3><b>Digital Signature Algorithm (DSA)</b></h3>

The Digital Signature Algorithm (DSA) is a cryptographic algorithm used to generate digital signatures, authenticate the sender of a digital message, and prevent message tampering.
<br>
DSA works by having two keys: a private key owned by the sender and a public key held by the receiver, which means that a sender can sign a message using their private key, and the receiver can verify the signature using the sender’s public key.

</div>

<div>
<h2><b>Hashing</b></h2>

A Hashing function in cryptography is like a mathematical function that takes various inputs, like messages or data, and transforms them into fixed-length strings of characters. This means the input to the hash function is of any length, but the output is always of fixed length.

</div>

<div>
<h2><b>Diffie-Hellman Key Exchange</b></h2>

Diffie-Hellman key exchange is a method of digital encryption that securely exchanges cryptographic keys between two parties over a public channel without their conversation being transmitted over the internet. The two parties use symmetric cryptography to encrypt and decrypt their messages.

</div>
