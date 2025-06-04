# Awesome Cryptography [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<p align="center">
  <img src="https://github.com/sobolevn/awesome-cryptography/blob/master/awesome-crypto.png?raw=true" alt="Awesome Cryptography">
</p>

[![Follow us on twitter](https://img.shields.io/twitter/follow/awe_crypto_bot.svg?style=social&maxAge=0)](https://twitter.com/awe_crypto_bot)

A curated list of cryptography resources and links.

## Contents

<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- [Theory](#theory)
  - [Algorithms](#algorithms)
    - [Symmetric encryption](#symmetric-encryption)
    - [Asymmetric encryption](#asymmetric-encryption)
    - [Hash functions](#hash-functions)
  - [Articles](#articles)
  - [Books](#books)
  - [Courses](#courses)
  - [Other lists](#other-lists)
- [Tools](#tools)
  - [Standalone](#standalone)
  - [Plugins](#plugins)
    - [Git](#git)
  - [Playgrounds](#playgrounds)
- [Frameworks and Libs](#frameworks-and-libs)
  - [C](#c)
  - [C#](#c-sharp)
  - [C++](#c-1)
  - [Clojure](#clojure)
  - [Common Lisp](#common-lisp)
  - [Delphi](#delphi)
  - [Elixir](#elixir)
  - [Erlang](#erlang)
  - [Golang](#go)
  - [Haskell](#haskell)
  - [Haxe](#haxe)
  - [Java](#java)
  - [JavaScript](#javascript)
  - [Julia](#julia)
  - [Lua](#lua)
  - [OCaml](#ocaml)
  - [Objective-C](#objective-c)
  - [PHP](#php)
  - [Python](#python)
  - [R](#r)
  - [Ruby](#ruby)
  - [Rust](#rust)
  - [Scala](#scala)
  - [Scheme](#scheme)
  - [Swift](#swift)
- [Resources](#resources)
  - [Blogs](#blogs)
  - [Mailing lists](#mailing-lists)
  - [Web-tools](#web-tools)
  - [Web-sites](#web-sites)
- [Contributing](#contributing)
- [License](#license)

<!--lint enable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- - -

## Theory

### Algorithms

#### Symmetric encryption

- [3DES](https://en.wikipedia.org/wiki/Triple_DES) - Symmetric-key block cipher (or Triple Data Encryption Algorithm (TDEA or Triple DEA), which applies the Data Encryption Standard (DES) cipher algorithm three times to each data block.
- [AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) - Symmetric-key block cipher algorithm and U.S. government standard for secure and classified data encryption and decryption (also known as Rijndael).
- [Blowfish](https://en.wikipedia.org/wiki/Blowfish_(cipher)) - Symmetric-key block cipher, designed in 1993 by Bruce Schneier. Notable features of the design include key-dependent S-boxes and a highly complex key schedule.

#### Asymmetric encryption

- [DH](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange) - A method of exchanging cryptographic keys securely over a public channel. Unlike RSA, the Diffie-Hellman Key Exchange is not encryption, and is only a way for two parties to agree on a shared secret value. Since the keys generated are completely pseudo-random, DH key exchanges can provide forward secrecy (https://en.wikipedia.org/wiki/Forward_secrecy).
- [ECC](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography) - Public-key cryptosystems based on the algebraic structure of elliptic curves over finite fields.
- [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) - One of the first practical public-key cryptosystems and is widely used for secure data transmission. In RSA, this asymmetry is based on the practical difficulty of factoring the product of two large prime numbers, the factoring problem.

#### Transform Encryption

- [Transform Encryption (aka Proxy Re-Encryption)](https://docs.ironcorelabs.com/concepts/transform-encryption) - Transform encryption uses three  mathematically related keys: one to encrypt plaintext to a recipient, a second to decrypt the ciphertext, and a third to transform ciphertext encrypted to one recipient so it can be decrypted by a different recipient.

#### Hash functions

- [MD5](https://en.wikipedia.org/wiki/MD5) - Widely used hash function producing a 128-bit hash value. MD5 was initially designed to be used as a cryptographic hash function, but it has been found to suffer from extensive vulnerabilities. It can still be used as a checksum to verify data integrity, but only against unintentional corruption.
- [SHA1](https://en.wikipedia.org/wiki/SHA-1) -  Cryptographic hash function designed by the NSA. SHA-1 produces a 160-bit hash value known as a message digest. SHA-1 is no longer considered secure against well-funded opponents.
- [SHA2](https://en.wikipedia.org/wiki/SHA-2) - Set of hash functions designed by the NSA. SHA-256 and SHA-512 are novel hash functions computed with 32-bit and 64-bit words, respectively. They use different shift amounts and additive constants, but their structures are otherwise virtually identical, differing only in the number of rounds.
- [SHA3](https://en.wikipedia.org/wiki/SHA-3) - Cryptographic hash function that produces a fixed-size output, typically 224, 256, 384, or 512 bits, from variable-size input data. It is part of the SHA-3 family of cryptographic algorithms designed to resist attacks from quantum computers and offers security properties such as pre-image resistance, second pre-image resistance, and collision resistance.

### Articles

- [How to Generate Secure Random Numbers in Various Programming Languages](https://paragonie.com/blog/2016/05/how-generate-secure-random-numbers-in-various-programming-languages).
- [Password Insecurity](https://www.netlogix.at/news/artikel/password-insecurity-part-1/) - This article is written for everybody who is interested in password security.
- [Secure Account Recovery Made Simple](https://paragonie.com/blog/2016/09/untangling-forget-me-knot-secure-account-recovery-made-simple).

### Books

- [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/) - The book covers many constructions for different tasks in cryptography.
- [An Introduction to Mathematical Cryptography](http://www.math.brown.edu/~jhs/MathCryptoHome.html) - Introduction to modern cryptography.
- [Applied Cryptography: Protocols, Algorithms and Source Code in C](https://www.wiley.com/en-ie/Applied+Cryptography%3A+Protocols%2C+Algorithms+and+Source+Code+in+C%2C+20th+Anniversary+Edition-p-9781119439028) - This cryptography classic provides you with a comprehensive survey of modern cryptography.
- [Crypto101](https://www.crypto101.io/) - Crypto 101 is an introductory course on cryptography.
- [Cryptography Engineering](https://www.schneier.com/books/cryptography_engineering/) - Learn to build cryptographic protocols that work in the real world.
- [Handbook of Applied Cryptography](https://cacr.uwaterloo.ca/hac/) - This book is intended as a reference for professional cryptographers.
- [Introduction to Modern Cryptography](http://www.cs.umd.edu/~jkatz/imc.html) - Introductory-level treatment of cryptography written from a modern, computer science perspective.
- [OpenSSL Cookbook](https://www.feistyduck.com/library/openssl-cookbook/) - The book about OpenSSL.
- [Practical Cryptography for Developers](https://cryptobook.nakov.com) - Developer-friendly book on modern cryptography (hashes, MAC codes, symmetric and asymmetric ciphers, key exchange, elliptic curves, digital signatures) with lots of code examples.
- [Real World Cryptography](https://www.manning.com/books/real-world-cryptography/) - This book teaches you applied cryptographic techniques to understand and apply security at every level of your systems and applications.
- [Security Engineering](http://www.cl.cam.ac.uk/~rja14/book.html) - There is an extraordinary textbook written by Ross Anderson, professor of computer security at University of Cambridge.
- [Serious Cryptography](https://nostarch.com/seriouscrypto) - A Practical Introduction to Modern Encryption by Jean-Philippe Aumasson.
- [The Code Book](https://simonsingh.net/books/the-code-book/) - This book is a digest of the history of cryptography, covering both ancient times, and newer cryptography methods. There are exercises at the end and the solution of those was rewarded with $10.000.
- [The Cryptoparty Handbook](https://unglue.it/work/141611/) - This book provides a comprehensive guide to the various topics of the computer and internet security.
- [Understanding Cryptography](http://www.crypto-textbook.com/) - Often overlooked, this book is a boon for beginners to the field. It contains plenty of exercises at the end of each chapter, aimed at reinforcing concepts and cementing ideas.

### Courses

- [A Self-Study Course In Block-Cipher Cryptanalysis](https://www.schneier.com/wp-content/uploads/2016/02/paper-self-study.pdf) - This paper attempts to organize the existing literature of block-cipher cryptanalysis in a way that students can use to learn cryptanalytic techniques and ways to break algorithms, by Bruce Schneier.
- [Applied Cryptography](https://www.udacity.com/course/applied-cryptography--cs387) - Cryptography is present in everyday life, from paying with a credit card to using the telephone. Learn all about making and breaking puzzles in computing.
- [Crypto Strikes Back!](https://www.youtube.com/watch?v=ySQl0NhW1J0) - This talk will cover crypto vulnerabilities in widely-deployed systems and how the smallest oversight resulted in catastrophe.
- [Cryptography](https://www.coursera.org/learn/cryptography) - A practical oriented course in Cryptography by University of Maryland College Park.
- [Cryptography - Stanford University](http://online.stanford.edu/course/cryptography) - This course explains the inner workings of cryptographic primitives and how to correctly use them. Students will learn how to reason about the security of cryptographic constructions and how to apply this knowledge to real-world applications.
- [Cryptography 101: Building Blocks](https://cryptography101.ca/crypto101-building-blocks/) - This introductory course (Fall 2024) by Alfred Menezes covers the fundamental cryptographic primitives: symmetric-key encryption, hash functions, MACs, authenticated encryption, public-key encryption, signatures, key agreement, RSA, elliptic curve cryptography.
- [Cryptography I](https://www.coursera.org/learn/crypto) - The course begins with a detailed discussion of how two parties who have a shared secret key can communicate securely when a powerful adversary eavesdrops and tampers with traffic. We will examine many deployed protocols and analyze mistakes in existing systems.
- [Cybrary Cryptography](https://www.cybrary.it/course/cryptography/) - This online course we will cover how cryptography is the cornerstone of security, and how through its use of different encryption methods, such as ciphers, and public or private keys, you can protect private or sensitive information from unauthorized access.
- [Harvard's Cryptography Lecture notes](https://intensecrypto.org/) - An introductory but fast-paced undergraduate/beginning graduate course on cryptography, Used for Harvard CS 127.
- [Journey into cryptography](https://www.khanacademy.org/computing/computer-science/cryptography) - The course of cryptography by Khan Academy.
- [Practical Aspects of Modern Cryptography](http://courses.cs.washington.edu/courses/csep590/06wi/) - Practical Aspects of Modern Cryptography, Winter 2006 University of Washington CSE.
- [Theory and Practice of Cryptography](https://www.youtube.com/watch?v=ZDnShu5V99s) - Introduction to Modern Cryptography, Using Cryptography in Practice and at Google, Proofs of Security and Security Definitions and A Special Topic in Cryptography.

### Other lists

- [Awesome crypto-papers](https://github.com/pFarb/awesome-crypto-papers) – A curated list of cryptography papers, articles, tutorials and howtos.
- [Awesome HE](https://github.com/jonaschn/awesome-he) – A curated list of homomorphic encryption libraries, software and resources.
- [TLS Cipher Suites](https://stellastra.com/cipher-suite) - A list of TLS cipher suites and their security ratings. 

## Tools

### Standalone

- [Bcrypt](http://bcrypt.sourceforge.net/) - Cross-platform file encryption utility.
- [blackbox](https://github.com/StackExchange/blackbox) - safely store secrets in Git/Mercurial/Subversion.
- [certbot](https://github.com/certbot/certbot) - Previously the Let's Encrypt Client, is EFF's tool to obtain certs from Let's Encrypt, and (optionally) auto-enable HTTPS on your server. It can also act as a client for any other CA that uses the ACME protocol.
- [Coherence](https://github.com/liesware/coherence/) - Cryptographic server for modern web apps.
- [cryptomator](https://github.com/cryptomator/cryptomator) - Multi-platform transparent client-side encryption of your files in the cloud.
- [Databunker](https://databunker.org/) - API based personal data or PII storage service built to comply with GDPR and CCPA.
- [gpg](https://www.gnupg.org/) - Complete and free implementation of the OpenPGP standard. It allows to encrypt and sign your data and communication, features a versatile key management system. GnuPG is a command line tool with features for easy integration with other applications.
- [ironssh](https://github.com/IronCoreLabs/ironssh) - End-to-end encrypt transferred files using sftp/scp and selectively share with others. Automatic key management works with any SSH server. Encrypted files are gpg compatible.
- [Nipe](https://github.com/GouveaHeitor/nipe) - Nipe is a script to make Tor Network your default gateway.
- [sops](https://github.com/mozilla/sops) - sops is an editor of encrypted files that supports YAML, JSON and BINARY formats and encrypts with AWS KMS, GCP KMS, Azure Key Vault and PGP.
- [ves](https://ves.host/docs/ves-util) - End-to-end encrypted sharing via cloud repository, secure recovery through a viral network of friends in case of key loss.

### Plugins

#### Git

- [git-crypt](https://github.com/AGWA/git-crypt) - Transparent file encryption in git.
- [git-secret](https://sobolevn.github.io/git-secret/) - Bash-tool to store your private data inside a git repository.

### Playgrounds

- [Cryptography Playground](https://vishwas1.github.io/crypto/index.html#/crypto) - A simple web tool to play and learn basic concepts of cryptography like, hashing, symmetric, asymmetric, zkp etc.

## Frameworks and Libs

### C

- [crypto-algorithms](https://github.com/B-Con/crypto-algorithms) - Basic implementations of standard cryptography algorithms, like AES and SHA-1.
- [libgcrypt](http://directory.fsf.org/wiki/Libgcrypt) - Cryptographic library developed as a separated module of GnuPG.
- [libkcapi](https://github.com/smuellerDD/libkcapi) - Linux Kernel Crypto API User Space Interface Library.
- [libsodium](https://github.com/jedisct1/libsodium) - Modern and easy-to-use crypto library.
- [libtomcrypt](https://github.com/libtom/libtomcrypt) - Fairly comprehensive, modular and portable cryptographic toolkit.
- [libVES.c](https://github.com/vesvault/libVES.c) - End-to-end encrypted sharing via cloud repository, secure recovery through a viral network of friends in case of key loss.
- [milagro-crypto-c](https://github.com/apache/incubator-milagro-crypto-c) - Small, self-contained and fast open source crypto library. It supports RSA, ECDH, ECIES, ECDSA, AES-GCM, SHA2, SHA3 and Pairing-Based Cryptography.
- [monocypher](https://monocypher.org) - small, portable, easy to use crypto library inspired by libsodium and TweetNaCl.
- [NaCl](https://nacl.cr.yp.to/) - High-speed library for network communication, encryption, decryption, signatures, etc.
- [nettle](https://github.com/gnutls/nettle) - is a cryptographic library that is designed to fit easily in more or less any context: In crypto toolkits for object-oriented languages (C++, Python, Pike, ...), in applications like LSH or GNUPG, or even in kernel space.
- [OpenSSL](https://github.com/openssl/openssl) - TLS/SSL and crypto library.
- [PolarSSL](https://tls.mbed.org/) - PolarSSL makes it trivially easy for developers to include cryptographic and SSL/TLS capabilities in their (embedded) products, facilitating this functionality with a minimal coding footprint.
- [RHash](https://github.com/rhash/RHash) - Great utility for computing hash sums.
- [themis](https://github.com/cossacklabs/themis) - High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption). Ported on many languages and platforms, suitable for client-server infastructures.
- [tiny-AES128-C](https://github.com/kokke/tiny-AES128-C) - Small portable AES128 in C.
- [wolfSSL](https://github.com/wolfSSL/wolfssl) - Small, fast, portable implementation of TLS/SSL for embedded devices to the cloud.
- [XKCP](https://github.com/XKCP/XKCP) — is a repository that gathers different free and open-source implementations of the cryptographic schemes defined by the Keccak team.
- [xxHash](https://github.com/Cyan4973/xxHash) - Extremely fast hash algorithm.

### C++

- [=nil; Crypto3](https://github.com/NilFoundation/crypto3) - Modern Cryptography Suite in C++17 (complete applied cryptography suite starting with block ciphers and ending with threshold cryptography, zk proof systems, etc).
- [Botan](https://botan.randombit.net/) - Cryptography library written in `C++20`.
- [cryptopp](https://github.com/weidai11/cryptopp) - Crypto++ Library is a free C++ class library of cryptographic schemes.
- [HElib](https://github.com/shaih/HElib) - Software library that implements homomorphic encryption (HE).
- [Nettle](http://www.lysator.liu.se/~nisse/nettle/) - Low-level cryptographic library.
- [s2n](https://github.com/awslabs/s2n) - Implementation of the TLS/SSL protocols.

### C-sharp

- [Bouncy Castle](https://bouncycastle.org/csharp/index.html) - All-purpose cryptographic library.
- [libsodium-net](https://github.com/adamcaudill/libsodium-net) - Secure cryptographic library, port of libsodium for .NET.
- [Microsoft .NET Framework Cryptography Model](https://docs.microsoft.com/en-us/dotnet/standard/security/cryptography-model) - The .NET Framework implementations of many standard cryptographic algorithms.
- [PCLCrypto](https://github.com/AArnott/PCLCrypto) - Provides cryptographic APIs over algorithms implemented by the platform, including exposing them to portable libraries.
- [SecurityDriven.Inferno](https://github.com/sdrapkin/SecurityDriven.Inferno) - .NET crypto done right.
- [StreamCryptor](https://github.com/bitbeans/StreamCryptor) - Stream encryption & decryption with libsodium and protobuf.

### Clojure

- [buddy-core](https://funcool.github.io/buddy-core/latest/) - Cryptographic Api.
- [clj-crypto](https://github.com/macourtney/clj-crypto/) - Wrapper for Bouncy Castle.
- [pandect](https://github.com/xsc/pandect) - Fast and easy-to-use Message Digest, Checksum and HMAC library for Clojure.
- [secrets.clj](https://github.com/lk-geimfari/secrets.clj) - A Clojure library designed to generate cryptographically strong random numbers suitable for managing data such as passwords, account authentication, security tokens, and related secrets.

### Common Lisp

- [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts) - Collection of common cryptography functions.
- [ironclad](http://method-combination.net/lisp/ironclad/) - Collection of common crypto shortcuts.
- [trivial-ssh](https://github.com/eudoxia0/trivial-ssh) - SSH client library for Common Lisp (Built on libssh2).

### Delphi

- [DelphiEncryptionCompendium](https://github.com/winkelsdorf/DelphiEncryptionCompendium/releases) - Cryptographic library for Delphi.
- [LockBox](https://sourceforge.net/projects/tplockbox/) - LockBox 3 is a Delphi library for cryptography.
- [SynCrypto](https://github.com/synopse/mORMot/blob/master/SynCrypto.pas) - Fast cryptographic routines (hashing and cypher), implementing AES, XOR, RC4, ADLER32, MD5, SHA1, SHA256 algorithms, optimized for speed.
- [TForge](https://bitbucket.org/sergworks/tforge) - TForge is open-source crypto library written in Delphi, compatible with FPC.

### Elixir

- [cipher](https://github.com/rubencaro/cipher) - Elixir crypto library to encrypt/decrypt arbitrary binaries.
- [cloak](https://github.com/danielberkompas/cloak) - Cloak makes it easy to use encryption with Ecto.
- [comeonin](https://github.com/elixircnx/comeonin) - Password authorization (bcrypt) library for Elixir.
- [elixir-rsa](https://github.com/trapped/elixir-rsa) - `:public_key` cryptography wrapper for Elixir.
- [elixir_tea](https://github.com/keichan34/elixir_tea) - TEA implementation in Elixir.
- [ex_crypto](https://github.com/ntrepid8/ex_crypto) - Elixir wrapper for Erlang `:crypto` and `:public_key` modules. Provides sensible defaults for many crypto functions to make them easier to use.
- [exgpg](https://github.com/rozap/exgpg) - Use gpg from Elixir.
- [pot](https://github.com/yuce/pot) - Erlang library for generating one time passwords compatible with Google Authenticator.
- [siphash-elixir](https://github.com/zackehh/siphash-elixir) - Elixir implementation of the SipHash hash family.

### Erlang

- [crypto](http://erlang.org/doc/apps/crypto/) - Functions for computation of message digests, and functions for encryption and decryption.
- [public_key](http://erlang.org/doc/man/public_key.html) - Provides functions to handle public-key infrastructure.

### Go

- [crypto](https://golang.org/pkg/crypto/) - Official Website Resources.
- [dkeyczar](https://github.com/dgryski/dkeyczar) - Port of Google's Keyczar cryptography library to Go.
- [gocrypto](https://github.com/kisom/gocrypto) - Example source code for the Practical Crypto with Go book.
- [goThemis](https://github.com/cossacklabs/themis/wiki/Go-Howto) - Go wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [kyber](https://github.com/dedis/kyber) - Advanced crypto library for the Go language.


### Haskell

- [Cryptography](http://hackage.haskell.org/packages/#cat:Cryptography) - Collaborative Hackage list.
- [Cryptography & Hashing](https://wiki.haskell.org/Applications_and_libraries/Cryptography) - Official Website of Haskell.
- [cryptol](https://github.com/GaloisInc/cryptol) - The Language of Cryptography.
- [Cryptonite](https://hackage.haskell.org/package/cryptonite) - Haskell repository of cryptographic primitives.
- [HsOpenSSL](https://github.com/phonohawk/HsOpenSSL) - OpenSSL binding for Haskel.
- [scrypt](https://github.com/informatikr/scrypt) - Haskell bindings to Colin Percival's scrypt implementation.

### Haxe

- [haxe-crypto](http://lib.haxe.org/p/haxe-crypto/) - Haxe Cryptography Library.

### JavaScript

- [asmCrypto](https://github.com/vibornoff/asmcrypto.js/) - JavaScript implementation of popular cryptographic utilities with performance in mind.
- [bcrypt-Node.js](https://github.com/shaneGirish/bcrypt-Node.js) - Native implementation of bcrypt for Node.js.
- [cifre](https://github.com/openpeer/cifre) - Fast crypto toolkit for modern client-side JavaScript.
- [closure-library](https://github.com/google/closure-library/tree/master/closure/goog/crypt) - Google's common JavaScript library.
- [cryptico](https://github.com/wwwtyro/cryptico) - Easy-to-use encryption system utilizing RSA and AES for JavaScript.
- [crypto-js](https://github.com/brix/crypto-js) - JavaScript library of crypto standards.
- [cryptojs](https://github.com/gwjjeff/cryptojs) - Provide standard and secure cryptographic algorithms for Node.js.
- [forge](https://github.com/digitalbazaar/forge) - Native implementation of TLS in JavaScript and tools to write crypto-based and network-heavy webapps.
- [IronNode](https://docs.ironcorelabs.com/ironnode-sdk/overview) - Transform encryption library, a variant of proxy re-encryption, for encrypting to users or groups, and easily adding strong data controls to Node.js apps.
- [IronWeb](https://docs.ironcorelabs.com/ironweb-sdk/overview) - Transform encryption library, a variant of proxy re-encryption, for easily managing end-to-end encryption securely in the browser.
- [javascript-crypto-library](https://github.com/clipperz/javascript-crypto-library) - JavaScript Crypto Library provides web developers with an extensive and efficient set of cryptographic functions.
- [js-nacl](https://github.com/tonyg/js-nacl) - Pure-JavaScript High-level API to Emscripten-compiled libsodium routines.
- [jsencrypt](https://github.com/travist/jsencrypt) - JavaScript library to perform OpenSSL RSA Encryption, Decryption, and Key Generation.
- [JShashes](https://github.com/h2non/jshashes) - Fast and dependency-free cryptographic hashing library for Node.js and browsers (supports MD5, SHA1, SHA256, SHA512, RIPEMD, HMAC).
- [jsrsasign](https://github.com/kjur/jsrsasign) - The 'jsrsasign' (RSA-Sign JavaScript Library) is an opensource free cryptography library supporting RSA/RSAPSS/ECDSA/DSA signing/validation.
- [jsThemis](https://github.com/cossacklabs/themis/wiki/Nodejs-Howto) - JavaScript wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [libsodium.js](https://github.com/jedisct1/libsodium.js) - libsodium compiled to pure JavaScript, with convenient wrappers.
- [libVES.js](https://github.com/vesvault/libVES) - End-to-end encrypted sharing via cloud repository, secure recovery through a viral network of friends in case of key loss.
- [micro-rsa-dsa-dh](https://github.com/paulmillr/micro-rsa-dsa-dh) - Minimal implementation of older cryptography algorithms: RSA, DSA, DH, ElGamal.
- [milagro-crypto-js](https://github.com/apache/incubator-milagro-crypto-js) - MCJS is a standards compliant JavaScript cryptographic library with no external dependencies except for the random seed source. Compatible for Node.js and browser. It supports RSA, ECDH, ECIES, ECDSA, AES-GCM, SHA2, SHA3, Pairing-Based Cryptography and New Hope.
- noble - high-security, easily auditable set of contained cryptographic libraries and tools. Zero dependencies each.
  - [noble-ciphers](https://github.com/paulmillr/noble-ciphers) — cryptographic ciphers, including AES-SIV, Salsa20, ChaCha, Poly1305 and FF1
  - [noble-curves](https://github.com/paulmillr/noble-curves) — elliptic curve cryptography, including Weierstrass, Edwards, Montgomery curves, pairings, hash-to-curve, poseidon hash, schnorr, secp256k1, ed25519, ed448, p521, bn254, bls12-381 and others. Also 4kb [noble-secp256k1](https://github.com/paulmillr/noble-secp256k1), [noble-ed25519](https://github.com/paulmillr/noble-ed25519)
  - [noble-hashes](https://github.com/paulmillr/noble-hashes) — SHA2, SHA3, RIPEMD, BLAKE2/3, HMAC, HKDF, PBKDF2, Scrypt & Argon2id
  - [noble-post-quantum](https://github.com/paulmillr/noble-post-quantum) — ML-KEM, ML-DSA, SLH-DSA (CRYSTALS-Kyber, CRYSTALS-Dilithium, Sphincs+) and hybrids
- [node.bcrypt.js](https://github.com/ncb000gt/node.bcrypt.js) - bcrypt for Node.js.
- [OpenPGP.js](https://github.com/openpgpjs/openpgpjs) - OpenPGP implementation for JavaScript.
- [PolyCrypt](https://github.com/polycrypt/polycrypt) - Pure JS implementation of the WebCrypto API.
- [rusha](https://github.com/srijs/rusha) - High-performance pure-javascript SHA1 implementation suitable for large binary data, reaching up to half the native speed.
- [sjcl](https://github.com/bitwiseshiftleft/sjcl) - Stanford JavaScript Crypto Library.
- [TweetNaCl.js](https://github.com/dchest/tweetnacl-js) - A port of TweetNaCl / NaCl for JavaScript for modern browsers and Node.js.
- [URSA](https://github.com/quartzjer/ursa) - RSA public/private key OpenSSL bindings for Node.


### Java

- [Apache Shiro](http://shiro.apache.org/) - Performs authentication, authorization, cryptography and session management.
- [Bouncy Castle](https://www.bouncycastle.org/java.html) - All-purpose cryptographic library. JCA provider, wide range of functions from basic helpers to PGP/SMIME operations.
- [Flexiprovider](http://www.flexiprovider.de/) - Powerful toolkit for the Java Cryptography Architecture.
- [GDH](https://github.com/maxamel/GDH) - Generalized Diffie-Hellman key exchange Java library for multiple parties built on top of the Vert.x framework.
- [Google Tink](https://github.com/tink-crypto/tink-java) - A small crypto library that provides a safe, simple, agile and fast way to accomplish some common crypto tasks.
- [Java Themis](https://github.com/cossacklabs/themis/wiki/Java-and-Android-Howto) - Java/Android wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [jbcrypt](http://www.mindrot.org/projects/jBCrypt/) - jBCrypt is an implementation the OpenBSD Blowfish password hashing
algorithm.
- [Keycloak](https://github.com/keycloak/keycloak) - Open Source Identity and Access Management For Modern Applications and Services.
- [pac4j](https://github.com/pac4j/pac4j) - Security engine.
- [Password4j](https://github.com/Password4j/password4j) - A Java user-friendly cryptographic library for hashing and checking passwords with different Key derivation functions (KDFs) and Cryptographic hash functions (CHFs).
- [Project Kalium](http://abstractj.github.io/kalium/) - Java binding to the Networking and Cryptography (NaCl) library with the awesomeness of libsodium.
- [scrypt](https://github.com/wg/scrypt) - Pure Java implementation of the scrypt key derivation function and a JNI interface to the C implementations, including the SSE2 optimized version.
- [securitybuilder](https://github.com/tersesystems/securitybuilder) - Fluent Builder API for JCA/JSSE objects.



### Julia

- [Crypto.jl](https://github.com/danielsuo/Crypto.jl) - Library that wraps OpenSSL, but also has pure Julia implementations for reference.
- [MbedTLS.jl](https://github.com/JuliaWeb/MbedTLS.jl) - Wrapper around the mbed TLS and cryptography C libary.
- [Nettle.jl](https://github.com/staticfloat/Nettle.jl) - Julia wrapper around nettle cryptographic hashing/
encryption library providing MD5, SHA1, SHA2 hashing and HMAC functionality, as well as AES encryption/decryption.
- [SHA.jl](https://github.com/staticfloat/SHA.jl) - Performant, 100% native-julia SHA1, SHA2-{224,256,384,512} implementation.

### Lua

- [lua-lockbox](https://github.com/somesocks/lua-lockbox) - Collection of cryptographic primitives written in pure Lua.
- [LuaCrypto](https://github.com/mkottman/luacrypto) - Lua bindings to OpenSSL.

### OCaml

- [Digestif](https://github.com/mirage/digestif) - is a toolbox that implements various cryptographic primitives in C and OCaml.
- [ocaml-tls](https://github.com/mirleft/ocaml-tls) - TLS in pure OCaml.

### Objective-C

- [CocoaSecurity](https://github.com/kelp404/CocoaSecurity) - AES, MD5, SHA1, SHA224, SHA256, SHA384, SHA512, Base64, Hex.
- [ObjC Themis](https://github.com/cossacklabs/themis/wiki/Objective-C-Howto) - ObjC wrapper on Themis for iOS and macOS. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [ObjectivePGP](https://github.com/krzyzanowskim/ObjectivePGP) - ObjectivePGP is an implementation of OpenPGP protocol for iOS and macOS. OpenPGP is the most widely used email encryption standard.
- [RNCryptor](https://github.com/RNCryptor/RNCryptor) - CCCryptor (AES encryption) wrappers for iOS and Mac.


### PHP

- [halite](https://paragonie.com/project/halite) - Simple library for encryption using `libsodium`.
- [libsodium-laravel](https://github.com/scrothers/libsodium-laravel) - Laravel Package Abstraction using `libsodium`.
- [PHP Encryption](https://github.com/defuse/php-encryption) - Library for encrypting data with a key or password in PHP.
- [PHP Themis](https://github.com/cossacklabs/themis/wiki/PHP-Howto) - PHP wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).
- [TCrypto](https://github.com/timoh6/TCrypto) - TCrypto is a simple and flexible PHP 5.3+ in-memory key-value storage library.

### Python

- [bcrypt](https://github.com/pyca/bcrypt) - Modern password hashing for your software and your servers.
- [charm](https://github.com/JHUISI/charm) - Framework for rapidly prototyping cryptosystems.
- [Crypto-Vinaigrette](https://github.com/aditisrinivas97/Crypto-Vinaigrette) - Quantum resistant asymmetric key generation tool for digital signatures.
- [cryptography](https://cryptography.io/en/latest/) - Python library which exposes cryptographic recipes and primitives.
- [cryptopy](https://sourceforge.net/projects/cryptopy/) - Pure python implementation of cryptographic algorithms and applications.
- [django-cryptography](https://github.com/georgemarshall/django-cryptography) - Easily encrypt data in Django.
- [ecdsa](https://github.com/tlsfuzzer/python-ecdsa) - An easy-to-use implementation of ECC with support for ECDSA and ECDH.
- [hashids](https://github.com/davidaurelio/hashids-python) - Implementation of [hashids](http://hashids.org) in Python.
- [paramiko](http://www.paramiko.org/) - Python implementation of the SSHv2 protocol, providing both client and server functionality.
- [Privy](https://github.com/ofek/privy) - An easy, fast lib to correctly password-protect your data.
- [pycryptodome](https://github.com/Legrandin/pycryptodome) - Self-contained Python package of low-level cryptographic primitives.
- [PyElliptic](https://github.com/yann2192/pyelliptic) - Python OpenSSL wrapper. For modern cryptography with ECC, AES, HMAC, Blowfish.
- [pynacl](https://github.com/pyca/pynacl) - Python binding to the Networking and Cryptography (NaCl) library.
- [pythemis](https://github.com/cossacklabs/themis/wiki/Python-Howto) - Python wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).

### R

- [rscrypt](https://github.com/rstudio/rscrypt) - Package for a collection of scrypt cryptographic functions.

### Ruby

- [bcrypt-ruby](https://github.com/codahale/bcrypt-ruby) - Ruby binding for the OpenBSD bcrypt() password hashing algorithm, allowing you to easily store a secure hash of your users' passwords.
- [RbNaCl](https://github.com/cryptosphere/rbnacl) - Ruby binding to the Networking and Cryptography (NaCl) library.
- [Ruby Themis](https://github.com/cossacklabs/themis/wiki/Ruby-Howto) - Ruby wrapper on Themis. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).

### Rust

- [AEADs](https://github.com/RustCrypto/AEADs) - Authenticated Encryption with Associated Data Algorithms: high-level encryption ciphers.
- [BLAKE3](https://github.com/BLAKE3-team/BLAKE3) - is official Rust and C implementations of the BLAKE3 cryptographic hash function.
- [botan-rs](https://github.com/randombit/botan-rs) - Botan bindings for Rust.
- [cryptoballot](https://github.com/cryptoballot/cryptoballot) - Cryptographically secure online voting.
- [dalek cryptography](https://github.com/dalek-cryptography/) - Fast yet safe mid-level API for ECC, Bulletproofs, and more.
- [dryoc](https://github.com/brndnmtthws/dryoc) - A pure-Rust, general purpose crypto library that implements libsodium primitives.
- [elliptic-curves](https://github.com/RustCrypto/elliptic-curves) - Collection of pure Rust elliptic curve implementations: NIST P-224, P-256, P-384, P-521, secp256k1, SM2.
- [formats](https://github.com/RustCrypto/formats) - Cryptography-related format encoders/decoders: DER, PEM, PKCS, PKIX.
- [hashes](https://github.com/RustCrypto/hashes) - Collection of cryptographic hash functions written in pure Rust.
- [mundane](https://github.com/google/mundane) - is a Rust cryptography library backed by BoringSSL that is difficult to misuse, ergonomic, and performant.
- [ockam](https://github.com/ockam-network/ockam) - is a Rust library for end-to-end encryption and mutual authentication.
- [octavo](https://github.com/libOctavo/octavo) - Highly modular & configurable hash & crypto library.
- [orion](https://github.com/orion-rs/orion) - is a cryptography library written in pure Rust. It aims to provide easy and usable crypto while trying to minimize the use of unsafe code.
- [password-hashes](https://github.com/RustCrypto/password-hashes) - Collection of password hashing algorithms, otherwise known as password-based key derivation functions, written in pure Rust.
- [proteus](https://github.com/wireapp/proteus) - Axolotl protocol implementation, without header keys, in Rust.
- [rage](https://github.com/str4d/rage) - is a simple, modern, and secure file encryption tool, using the age format.
- [recrypt](https://github.com/IronCoreLabs/recrypt-rs) - A pure-Rust library that implements cryptographic primitives for building a multi-hop Proxy Re-encryption scheme, known as Transform Encryption.
- [ring](https://github.com/briansmith/ring) - Safe, fast, small crypto using Rust & BoringSSL's cryptography primitives.
- [ronkathon](https://github.com/pluto/ronkathon) - Educational, mathematically transparent, well documentated cryptography in rust.
- [rust-crypto](https://github.com/DaGenix/rust-crypto) - Mostly pure-Rust implementation of various cryptographic algorithms.
- [rust-openssl](https://github.com/sfackler/rust-openssl) - OpenSSL bindings for Rust.
- [rustls](https://github.com/ctz/rustls) - Rustls is a new, modern TLS library written in Rust.
- [signatures](https://github.com/RustCrypto/signatures) - Cryptographic signature algorithms: DSA, ECDSA, Ed25519.
- [snow](https://github.com/mcginty/snow?tab=readme-ov-file) - Pure Rust implementation of Trevor Perrin’s [Noise Protocol](https://noiseprotocol.org/noise.html).
- [sodiumoxide](https://github.com/dnaq/sodiumoxide) - Sodium Oxide: Fast cryptographic library for Rust (bindings to libsodium).
- [suruga](https://github.com/klutzy/suruga) - TLS 1.2 implementation in Rust.
- [webpki](https://github.com/briansmith/webpki) - Web PKI TLS X.509 certificate validation in Rust.

### Scala

- [recrypt](https://github.com/IronCoreLabs/recrypt) - Transform encryption library for Scala.
- [scrypto](https://github.com/input-output-hk/scrypto) - Cryptographic primitives for Scala.
- [tsec](https://github.com/jmcardon/tsec) - A type-safe, functional, general purpose security and cryptography library.

### Scheme

- [chicken-sodium](https://github.com/caolan/chicken-sodium) - Bindings to libsodium crypto library for Chicken Scheme.
- [crypto-tools](https://wiki.call-cc.org/eggref/5/crypto-tools) - Useful cryptographic primitives for Chicken Scheme.
- [guile-gnutls](https://gitlab.com/gnutls/guile/) - GnuTLS bindings for GNU Guile.
- [guile-ssh](https://github.com/artyom-poptsov/guile-ssh) - libssh bindings for GNU Guile.
- [industria](https://gitlab.com/weinholt/industria) - Motley assortment of cryptographic primitives, OpenSSH, DNS.

### Swift

- [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - Crypto related functions and helpers for Swift implemented in Swift programming language.
- [IDZSwiftCommonCrypto](https://github.com/iosdevzone/IDZSwiftCommonCrypto) - Wrapper for Apple's [CommonCrypto](https://opensource.apple.com/source/CommonCrypto/) library written in Swift.
- [OpenSSL](https://github.com/Zewo/OpenSSL) - Swift OpenSSL for macOS and Linux.
- [SweetHMAC](https://github.com/jancassio/SweetHMAC) - Tiny and easy to use Swift class to encrypt strings using HMAC algorithms.
- [Swift-Sodium](https://github.com/jedisct1/swift-sodium) - Swift interface to the Sodium library for common crypto operations for iOS and macOS.
- [SwiftSSL](https://github.com/SwiftP2P/SwiftSSL) - Elegant crypto toolkit in Swift.
- [SwiftThemis](https://github.com/cossacklabs/themis/wiki/Swift-Howto) - Swift wrapper on Themis for iOS and macOS. High level crypto library for storing data (AES), secure messaging (ECC + ECDSA / RSA + PSS + PKCS#7) and session-oriented, forward secrecy data exchange (ECDH key agreement, ECC & AES encryption).

## Resources

### Blogs

- [A Few Thoughts on Cryptographic Engineering](http://blog.cryptographyengineering.com/) - Some random thoughts about crypto.
- [Bristol Cryptography Blog](http://bristolcrypto.blogspot.co.uk/) - Official blog for the University of Bristol cryptography research group. It's a group blog, primarily targeted towards cryptographers and crypto students.
- [Charles Engelke's Blog](https://blog.engelke.com/tag/webcrypto/) - WebCrypto Blog Posts.
- [Root Labs rdist](https://rdist.root.org/) - Nate Lawson and his co-authors write on a variety of topics including hardware implementation, cryptographic timing attacks, DRM, and the Commodore 64.
- [Salty Hash](https://blog.ironcorelabs.com) - Covers topics on encryption, data control, privacy, and security.
- [Schneier on security](https://www.schneier.com/) - One of the oldest and most famous security blogs. Bruce covers topics from block cipher cryptanalysis to airport security.

### Mailing lists

- [metzdowd.com](http://www.metzdowd.com/mailman/listinfo/cryptography) - "Cryptography" is a low-noise moderated mailing list devoted to cryptographic technology and its political impact.
- [Modern Crypto](https://moderncrypto.org/) - Forums for discussing modern cryptographic practice.
- [randombit.net](https://lists.randombit.net/mailman/listinfo/cryptography) - List for general discussion of cryptography, particularly the technical aspects.

### Web-tools

- [Boxentriq](https://www.boxentriq.com/code-breaking) - Easy to use tools for analysis and code-breaking of the most frequent ciphers, including Vigenère, Beaufort, Keyed Caesar, Transposition Ciphers, etc.
- [Cryptolab](http://manansingh.github.io/Cryptolab-Offline/cryptolab.html) - is a set of cryptography related tools.
- [CrypTool](http://www.cryptool-online.org/) - Great variety of ciphers, encryption methods and analysis tools are introduced, often together with illustrated examples.
- [CyberChef](https://gchq.github.io/CyberChef/) - a web app for encryption, encoding, compression, and data analysis.
- [factordb.com](http://factordb.com/) - Factordb.com is tool used to store known factorizations of any number.
- [keybase.io](https://keybase.io/) - Keybase maps your identity to your public keys, and vice versa.

### Web-sites

- [Applied Crypto Hardening](https://bettercrypto.org/) - A lot ready to use best practice examples for securing web servers and more.
- [Cryptocurrencies Dashboard](https://dashboard.nbshare.io/apps/reddit/top-crypto-subreddits/) - A dashboard of most active cryptocurrencies discussed on Reddit.
- [Cryptography Stackexchange](http://crypto.stackexchange.com/) - Cryptography Stack Exchange is a question and answer site for software developers, mathematicians and others interested in cryptography.
- [Cryptohack](https://cryptohack.org/) - A platform with lots of interactive cryptography challenges, similar to Cryptopals.
- [Cryptopals Crypto Challenges](http://cryptopals.com/) - A series of applied cryptography challenges, starting from very basic challenges, such as hex to base 64 challanges, and gradually increasing the difficulty up to abstract algebra.
- [Eliptic Curve Calculator](https://paulmillr.com/noble/#demo) - simple form that allows to calculate elliptic curve public keys and signatures. Features include ability to create custom curves and different signature types
- [Garykessler Crypto](http://www.garykessler.net/library/crypto.html) - An Overview of Cryptography.
- [IACR](https://www.iacr.org/) - The International Association for Cryptologic Research is a non-profit scientific organization whose purpose is to further research in cryptology and related fields.
- [Learn Cryptography](https://learncryptography.com/) - Dedicated to helping people understand how and why the cryptographic systems they use everyday without realizing work to secure and protect their privacy.
- [Subreddit of Cryptography](https://www.reddit.com/r/cryptography/) - This subreddit is intended for links and discussions surrounding the theory and practice of strong cryptography.
- [TikZ for Cryptographers](https://www.iacr.org/authors/tikz/) - A collection of block diagrams of common cryptographic functions drawn in TikZ to be used in research papers and presentations written in LaTeX.
- [WebCryptoAPI](https://www.w3.org/TR/WebCryptoAPI/) - This specification describes a JavaScript API for performing basic cryptographic operations in web applications, such as hashing, signature generation and verification, and encryption and decryption.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/sobolevn/awesome-cryptography/blob/master/CONTRIBUTING.md) first.

## License

`awesome-cryptography` by [@sobolevn](https://github.com/sobolevn)

To the extent possible under law, the person who associated CC0 with
`awesome-cryptography` has waived all copyright and related or neighboring
rights to `awesome-cryptography`.

You should have received a copy of the CC0 legalcode along with this
work.  If not, see [https://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1.0/).
