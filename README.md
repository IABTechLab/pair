# Publisher Advertiser Identity Reconciliation (PAIR)

This repository lists libraries that may be useful when implementing the workflows described in the [Publisher Advertiser Identity Reconciliation (PAIR)](https://iabtechlab.com/pair/) protocol.

## Cryptographic Libraries

Below are some cryptographic libraries that provide the key generation, hashing, and commutative encryption operations involved in PAIR workflows.

* **Java**: Commutative key generation and encryption/decryption operations can be implemented using [elliptic curve operations](https://github.com/google/private-join-and-compute/blob/master/java/com/google/privacy/private_join_and_compute/encryption/commutative/EcCommutativeCipher.java) that are available in [Bouncy Castle](https://www.bouncycastle.org/).

* **Python**: The [pairid](https://pypi.org/p/pairid) library provides all the necessary key generation, hashing, and commutative encryption/decryption operations. The commutative encryption operations leverage [Curve25519](https://cr.yp.to/ecdh.html) and the [Ristretto group](https://ristretto.group/).

