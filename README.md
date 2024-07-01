<h2>Crytpography</h2>
<br>
Cryptography is a technique of securing communication by converting plain text into ciphertext. It involves various algorithms and protocols to ensure data.
<br>
In Cryptography, the techniques that are used to protect information are done by algorithms to convert messages in ways that make it hard to decode them
<br>
<br>
There are mainly 3 types of Cryptography
<br>
1)Symmetric Crytpography
<br>
2)Asymmetric Crytpography
<br>
3)Hashing

<br>

<div>
<h3>Symmetric Cryptography</h3>

Symmetric Key cryptography is an encryption methodology where the sender and receiver uses a single common key to encrypt and decrypt messages.
<br>
The most popular symmetric key cryptography systems are Data Encryption Systems (DES) and Advanced Encryption Systems (AES).
<br>

<h4>Data Encryption Standard(DES)</h4>

Data Encryption Standard (DES) is a block cipher with a 56-bit key length that has played a significant role in data security.DES is a block cipher which encrypts data in blocks of size of 64 bits each, where 64 bits of plain text go as the input to DES algorithm and produces 64 bits of ciphertext. The same algorithm and key(public) are used for encryption and decryption, with minor differences.

<h4>Advanced Encryption Standard(AES)</h4>

Advanced Encryption Standard (AES) is a Block Cipher and key size can be 128/192/256 bits which encrypts data in blocks of 128 bits each.That means it takes 128 bits as input and outputs 128 bits of encrypted cipher text.The same algorithm and key(public) are used for encryption and decryption, with minor differences

</div>

<div>
<h3>Asymetric Cryptography</h3>

In Asymmetric Key Cryptography, a pair of keys is used to encrypt and decrypt information. A receiver’s public key is used for encryption and a receiver’s private key is used for decryption. Public keys and Private keys are different. Even if the public key is known by everyone the intended receiver can only decode it because he alone knows his private key.
<br>
The most popular asymmetric key cryptography algorithm is the RSA algorithm.

<h4>Rivest-Shamir-Aldemann(RSA)</h4>

RSA algorithm is an asymmetric cryptography algorithm. Asymmetric actually means that it works on two different keys i.e. Public Key and Private Key. As the name describes that the Public Key is given to everyone and the Private key is kept private.
<br>
RSA algorithm can be used for Digital Signatures, which means that a sender can sign a message using their private key, and the receiver can verify the signature using the sender’s public key.


<h4>Digital Signature Algorithm(DSA)</h4>

Digital Signature Algorithm(DSA) is a cryptographic algorithm used to generate digital signatures, authenticate the sender of a digital message, and prevent message tampering.
<br>
DSA works by having two keys: a private key owned by the sender and a public key held by the receiver which means that a sender can sign a message using their private key, and the receiver can verify the signature using the sender’s public key.

</div>

<div>
<h2>Hashing</h2>

A Hashing function in cryptography is like a mathematical function that takes various inputs, like messages or data, and transforms them into fixed-length strings of characters. Means the input to the hash function is of any length but output is always of fixed length

</div>

<div>
<h2>Diffie-Hellman Key Exchange</h2>

Diffie-Hellman key exchange is a method of digital encryption that securely exchanges cryptographic keys between two parties over a public channel without their conversation being transmitted over the internet. The two parties use symmetric cryptography to encrypt and decrypt their messages

</div>