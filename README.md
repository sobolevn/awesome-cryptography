# Awesome Cryptography [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![Join the chat at https://gitter.im/sobolevn/awesome-cryptography](https://badges.gitter.im/sobolevn/awesome-cryptography.svg)](https://gitter.im/sobolevn/awesome-cryptography?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Build Status](https://travis-ci.org/sobolevn/awesome-cryptography.svg)](https://travis-ci.org/sobolevn/awesome-cryptography)

A curated list of cryptography resources and links.

<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- [Theory](#theory)
  - [Algorithms](#algorithms)
    - [Symmetric encryption](#symmetric-encryption)
    - [Asymmetric encryption](#asymmetric-encryption)
    - [Hash functions](#hash-functions)
  - [Articles](#articles)
  - [Books](#books)
  - [Courses](#courses)

- [Tools](#tools)
  - [Standalone](#standalone)
  - [Plugins](#plugins)
    - [Git](#git)

- [Frameworks and Libs](#frameworks-and-libs)
  - [C](#c)
  - [C#](#c-sharp)
  - [C++](#cpp)
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
  - [Objective-C](#objective-c)
  - [PHP](#php)
  - [Python](#python)
  - [Ruby](#ruby)
  - [Rust](#rust)
  - [Scala](#scala)
  - [Swift](#swift)

- [Resources](#resources)
  - [Web-tools](#web-tools)
  - [Web-sites](#web-sites)
  - [Blogs](#blogs)

- [Contributing](#contributing)
- [License](#license)

<!--lint enable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- - -

## Theory

### Algorithms

#### Symmetric encryption

- [3DES](https://en.wikipedia.org/wiki/Triple_DES) - or Triple Data Encryption Algorithm (TDEA or Triple DEA) symmetric-key block cipher, which applies the Data Encryption Standard (DES) cipher algorithm three times to each data block.
- [AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) - is a symmetric-key block cipher algorithm and U.S. government standard for secure and classified data encryption and decryption (also known as Rijndael).
- [Blowfish](https://en.wikipedia.org/wiki/Blowfish_(cipher)) - is a symmetric-key block cipher, designed in 1993 by Bruce Schneier. Notable features of the design include key-dependent S-boxes and a highly complex key schedule.

#### Asymmetric encryption

- [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) - is one of the first practical public-key cryptosystems and is widely used for secure data transmission. In RSA, this asymmetry is based on the practical difficulty of factoring the product of two large prime numbers, the factoring problem.

#### Hash functions

- [MD5](https://en.wikipedia.org/wiki/MD5) - is a widely used hash function producing a 128-bit hash value. MD5 was initially designed to be used as a cryptographic hash function, but it has been found to suffer from extensive vulnerabilities. It can still be used as a checksum to verify data integrity, but only against unintentional corruption.
- [SHA1](https://en.wikipedia.org/wiki/SHA-1) -  is a cryptographic hash function designed by the NSA. SHA-1 produces a 160-bit hash value known as a message digest. SHA-1 is no longer considered secure against well-funded opponents.
- [SHA2](https://en.wikipedia.org/wiki/SHA-2) - is a set of hash functions designed by the NSA. SHA-256 and SHA-512 are novel hash functions computed with 32-bit and 64-bit words, respectively. They use different shift amounts and additive constants, but their structures are otherwise virtually identical, differing only in the number of rounds.

### Books

- [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/) - The book covers many constructions for different tasks in cryptography.
- [An Introduction to Mathematical Cryptography](http://www.math.brown.edu/~jhs/MathCryptoHome.html) -  is an introduction to modern cryptography.
- [Crypto101](https://www.crypto101.io/) - Crypto 101 is an introductory course on cryptography.
- [Cryptography Engineering](https://www.schneier.com/books/cryptography_engineering/) - Learn to build cryptographic protocols that work in the real world.
- [Handbook of Applied Cryptography](http://cacr.uwaterloo.ca/hac/index.html) - This book is intended as a reference for professional cryptographers.
- [Introduction to Modern Cryptography](http://www.cs.umd.edu/~jkatz/imc.html) -  is an introductory-level treatment of cryptography written from a modern, computer science perspective.
- [OpenSSL Cookbook](https://www.feistyduck.com/library/openssl-cookbook/) - The book about OpenSSL.
- [Security Engineering](http://www.cl.cam.ac.uk/~rja14/book.html) - There is an extraordinary textbook written by Ross Anderson, professor of computer security at University of Cambridge.
- [The Cryptoparty Handbook](https://unglue.it/work/141611/) - This book provides a comprehensive guide to the various topics of the computer and internet security.
- [Understanding Cryptography](http://www.crypto-textbook.com/) - Often overlooked, this book is a boon for beginners to the field. It contains plenty of exercises at the end of each chapter, aimed at reinforcing concepts and cementing ideas.

### Courses

- [Applied Cryptography](https://www.udacity.com/course/applied-cryptography--cs387) - Cryptography is present in everyday life, from paying with a credit card to using the telephone. Learn all about making and breaking puzzles in computing.
- [Crypto Strikes Back!](https://www.youtube.com/watch?v=ySQl0NhW1J0) - This talk will cover crypto vulnerabilities in widely-deployed systems and how the smallest oversight resulted in catastrophe.
- [Cryptography - Stanford University](http://online.stanford.edu/course/cryptography) - This course explains the inner workings of cryptographic primitives and how to correctly use them. Students will learn how to reason about the security of cryptographic constructions and how to apply this knowledge to real-world applications.
- [Cryptography I](https://www.coursera.org/learn/crypto) - The course begins with a detailed discussion of how two parties who have a shared secret key can communicate securely when a powerful adversary eavesdrops and tampers with traffic. We will examine many deployed protocols and analyze mistakes in existing systems.
- [Cybrary Cryptography](https://www.cybrary.it/course/cryptography/) - This online course we will cover how cryptography is the cornerstone of security, and how through its use of different encryption methods, such as ciphers, and public or private keys, you can protect private or sensitive information from unauthorized access.
- [Journey into cryptography](https://www.khanacademy.org/computing/computer-science/cryptography) - The course of cryptography by Khan Academy.
- [Practical Aspects of Modern Cryptography](http://courses.cs.washington.edu/courses/csep590/06wi/) - Practical Aspects of Modern Cryptography, Winter 2006 University of Washington CSE.
- [Theory and Practice of Cryptography](https://www.youtube.com/watch?v=ZDnShu5V99s) - Introduction to Modern Cryptography, Using Cryptography in Practice and at Google, Proofs of Security and Security Definitions and A Special Topic in Cryptography.

## Tools

### Standalone

- [blackbox](https://github.com/StackExchange/blackbox) - safely store secrets in Git/Mercurial/Subversion.
- [certbot](https://github.com/certbot/certbot) - previously the Let's Encrypt Client, is EFF's tool to obtain certs from Let's Encrypt, and (optionally) auto-enable HTTPS on your server. It can also act as a client for any other CA that uses the ACME protocol.
- [cryptomator](https://github.com/cryptomator/cryptomator) - Multi-platform transparent client-side encryption of your files in the cloud.
- [gpg](https://www.gnupg.org/) - is a complete and free implementation of the OpenPGP standard. It allows to encrypt and sign your data and communication, features a versatile key management system. GnuPG is a command line tool with features for easy integration with other applications.

### Plugins

#### Git

- [git-crypt](https://github.com/AGWA/git-crypt) - Transparent file encryption in git.
- [git-secret](https://sobolevn.github.io/git-secret/) - A bash-tool to store your private data inside a git repository.

## Frameworks and Libs

### C

- [crypto-algorithms](https://github.com/B-Con/crypto-algorithms) - Basic implementations of standard cryptography algorithms, like AES and SHA-1.
- [libgcrypt](http://directory.fsf.org/wiki/Libgcrypt) - is a cryptographic library developed as a separated module of GnuPG.
- [libsodium](https://github.com/jedisct1/libsodium) - a modern and easy-to-use crypto library.
- [libtomcrypt](https://github.com/libtom/libtomcrypt) - is a fairly comprehensive, modular and portable cryptographic toolkit.
- [NaCl](https://nacl.cr.yp.to/) - high-speed library for network communication, encryption, decryption, signatures, etc.
- [OpenSSL](https://github.com/openssl/openssl) - TLS/SSL and crypto library.
- [PolarSSL](https://tls.mbed.org/) - PolarSSL makes it trivially easy for developers to include cryptographic and SSL/TLS capabilities in their (embedded) products, facilitating this functionality with a minimal coding footprint.
- [RHash](https://github.com/rhash/RHash) - Great utility for computing hash sums.
- [tiny-AES128-C](https://github.com/kokke/tiny-AES128-C) - Small portable AES128 in C.
- [wolfSSL](https://github.com/wolfSSL/wolfssl) - wolfSSL is a small, fast, portable implementation of TLS/SSL for embedded devices to the cloud.
- [xxHash](https://github.com/Cyan4973/xxHash) - Extremely fast hash algorithm.

### C++

- [Bcrypt](http://bcrypt.sourceforge.net/) - a cross platform file encryption utility.
- [Botan](https://botan.randombit.net/) - is a cryptography library written in `C++11`.
- [cryptopp](https://github.com/weidai11/cryptopp) - Crypto++ Library is a free C++ class library of cryptographic schemes.
- [HElib](https://github.com/shaih/HElib) - is a software library that implements homomorphic encryption (HE).
- [Nettle](http://www.lysator.liu.se/~nisse/nettle/) - a low-level cryptographic library.
- [s2n](https://github.com/awslabs/s2n) - an implementation of the TLS/SSL protocols.

### C-sharp

- [Bouncy Castle](https://bouncycastle.org/csharp/index.html) - All-purpose cryptographic library.
- [libsodium-net](https://github.com/adamcaudill/libsodium-net) - libsodium for .NET - A secure cryptographic library.
- [PCLCrypto](https://github.com/AArnott/PCLCrypto) - provides cryptographic APIs over algorithms implemented by the platform, including exposing them to portable libraries.
- [SecurityDriven.Inferno](https://github.com/sdrapkin/SecurityDriven.Inferno) - .NET crypto done right.
- [StreamCryptor](https://github.com/bitbeans/StreamCryptor) - Stream encryption & decryption with libsodium and protobuf.

### Clojure

- [buddy-core](https://funcool.github.io/buddy-core/latest/) - Cryptographic Api.
- [pandect](https://github.com/xsc/pandect) - Fast and easy-to-use Message Digest, Checksum and HMAC library for Clojure.

### Common Lisp

- [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts) - Collection of common cryptography functions.
- [ironclad](http://method-combination.net/lisp/ironclad/) - Collection of common crypto shortcuts.
- [trivial-ssh](https://github.com/eudoxia0/trivial-ssh) - an SSH client library for Common Lisp (Built on libssh2).

### Delphi

- [DelphiEncryptionCompendium](https://github.com/winkelsdorf/DelphiEncryptionCompendium/releases) - Cryptographic library for Delphi.
- [LockBox](https://sourceforge.net/projects/tplockbox/) - LockBox 3 is a Delphi library for cryptography.
- [SynCrypto](https://github.com/synopse/mORMot/blob/master/SynCrypto.pas) - Fast cryptographic routines (hashing and cypher), implementing AES, XOR, RC4, ADLER32, MD5, SHA1, SHA256 algorithms, optimized for speed.
- [TForge](https://bitbucket.org/sergworks/tforge) - TForge is open-source crypto library written in Delphi, compatible with FPC.

### Elixir

- [cipher](https://github.com/rubencaro/cipher) - Elixir crypto library to encrypt/decrypt arbitrary binaries.
- [cloak](https://github.com/danielberkompas/cloak) - Cloak makes it easy to use encryption with Ecto.
- [comeonin](https://github.com/elixircnx/comeonin) - Password authorization (bcrypt) library for Elixir.
- [elixir-rsa](https://github.com/trapped/elixir-rsa) - `public_key` cryptography wrapper for Elixir.
- [elixir_tea](https://github.com/keichan34/elixir_tea) - TEA implementation in Elixir.
- [ex_crypto](https://github.com/ntrepid8/ex_crypto) - Elixir wrapper for Erlang `crypto` and `public_key` modules. Provides sensible defaults for many crypto functions to make them easier to use.
- [exgpg](https://github.com/rozap/exgpg) - Use gpg from Elixir.
- [pot](https://github.com/yuce/pot) - Erlang library for generating one time passwords compatible with Google Authenticator.
- [siphash-elixir](https://github.com/zackehh/siphash-elixir) - Elixir implementation of the SipHash hash family.

### Erlang

- [crypto](http://erlang.org/doc/apps/crypto/) - The functions for computation of message digests, and functions for encryption and decryption.

### Go

- [crypto](https://golang.org/pkg/crypto/) - Official Website Resources.
- [cryptoballot](https://github.com/cryptoballot/cryptoballot) - Cryptographically secure online voting.
- [dedis/crypto](https://github.com/dedis/crypto) - Advanced crypto library for the Go language.
- [dkeyczar](https://github.com/dgryski/dkeyczar) - Port of Google's Keyczar cryptography library to Go.
- [gocrypto](https://github.com/kisom/gocrypto) - Example source code for the Practical Crypto with Go book.

### Haskell

- [Crypto](http://hackage.haskell.org/packages/#cat:Crypto) - a collaborative Hackage list.
- [Cryptography](http://hackage.haskell.org/packages/#cat:Cryptography) - a collaborative Hackage list.
- [Cryptography & Hashing](https://wiki.haskell.org/Applications_and_libraries/Cryptography) - Official Website of Haskell.
- [Cryptonite](https://hackage.haskell.org/package/cryptonite) - Cryptonite is a haskell repository of cryptographic primitives.
- [HsOpenSSL](https://github.com/phonohawk/HsOpenSSL) - OpenSSL binding for Haskel.

### Haxe

- [haxe-crypto](http://lib.haxe.org/p/haxe-crypto/) - Haxe Cryptography Library.

### JavaScript

- [asmCrypto](https://github.com/vibornoff/asmcrypto.js/) - JavaScript implementation of popular cryptographic utilities with performance in mind.
- [cifre](https://github.com/openpeer/cifre) - Fast crypto toolkit for modern client-side JavaScript.
- [closure-library](https://github.com/google/closure-library/tree/master/closure/goog/crypt) - Google's common JavaScript library.
- [cryptico](https://github.com/wwwtyro/cryptico) - An easy-to-use encryption system utilizing RSA and AES for javascript.
- [crypto-js](https://github.com/brix/crypto-js) - JavaScript library of crypto standards.
- [cryptojs](https://github.com/gwjjeff/cryptojs) - Provide standard and secure cryptographic algorithms for NodeJS.
- [forge](https://github.com/digitalbazaar/forge) - A native implementation of TLS in Javascript and tools to write crypto-based and network-heavy webapps.
- [javascript-crypto-library](https://github.com/clipperz/javascript-crypto-library) - The JavaScript Crypto Library provides web developers with an extensive and efficient set of cryptographic functions.
- [js-nacl](https://github.com/tonyg/js-nacl) - Pure-Javascript High-level API to Emscripten-compiled libsodium routines.
- [jsencrypt](https://github.com/travist/jsencrypt) - A Javascript library to perform OpenSSL RSA Encryption, Decryption, and Key Generation.
- [JShashes](https://github.com/h2non/jshashes) - Fast and dependency-free cryptographic hashing library for node.js and browsers (supports MD5, SHA1, SHA256, SHA512, RIPEMD, HMAC).
- [libsodium.js](https://github.com/jedisct1/libsodium.js) - libsodium compiled to pure JavaScript, with convenient wrappers.
- [OpenPGP.js](https://github.com/openpgpjs/openpgpjs) - OpenPGP implementation for JavaScript.
- [PolyCrypt](https://github.com/polycrypt/polycrypt) - A pure JS implementation of the WebCrypto API.
- [rusha](https://github.com/srijs/rusha) - High-performance pure-javascript SHA1 implementation suitable for large binary data, reaching up to half the native speed.
- [sjcl](https://github.com/bitwiseshiftleft/sjcl) - Stanford Javascript Crypto Library.
- [URSA](https://github.com/quartzjer/ursa) - RSA public/private key OpenSSL bindings for Node.

### Java

- [Apache Shiro](http://shiro.apache.org/) - Performs authentication, authorization, cryptography and session management.
- [Bouncy Castle](https://www.bouncycastle.org/java.html) - All-purpose cryptographic library. JCA provider, wide range of functions from basic helpers to PGP/SMIME operations.
- [Flexiprovider](http://www.flexiprovider.de/) - The FlexiProvider is a powerful toolkit for the Java Cryptography Architecture.
- [Google Keyczar](https://github.com/google/keyczar) - Easy to use, yet safe encryption framework with key versioning.
- [pac4j](https://github.com/pac4j/pac4j) - Security engine.

### Julia

- [Crypto.jl](https://github.com/danielsuo/Crypto.jl) - a library that wraps OpenSSL, but also has pure Julia implementations for reference.
- [MbedTLS.jl](https://github.com/JuliaWeb/MbedTLS.jl) - A wrapper around the mbed TLS and cryptography C libary.
- [Nettle.jl](https://github.com/staticfloat/Nettle.jl) - Julia wrapper around nettle cryptographic hashing/
encryption library providing MD5, SHA1, SHA2 hashing and HMAC functionality, as well as AES encryption/decryption.
- [SHA.jl](https://github.com/staticfloat/SHA.jl) - A performant, 100% native-julia SHA1, SHA2-{224,256,384,512} implementation.

### Lua

- [lua-lockbox](https://github.com/somesocks/lua-lockbox) - a collection of cryptographic primitives written in pure Lua.
- [LuaCrypto](https://github.com/mkottman/luacrypto) - Lua bindings to OpenSSL.

### Objective-C

- [CocoaSecurity](https://github.com/kelp404/CocoaSecurity) - AES, MD5, SHA1, SHA224, SHA256, SHA384, SHA512, Base64, Hex.
- [RNCryptor](https://github.com/RNCryptor/RNCryptor) - CCCryptor (AES encryption) wrappers for iOS and Mac.
- [Themis](https://github.com/cossacklabs/themis) - High-level crypto library, providing basic asymmetric encryption.

### PHP

- [halite](https://paragonie.com/project/halite) - a simple library for encryption using `libsodium`.
- [PHP Encryption](https://github.com/defuse/php-encryption) - This is a library for encrypting data with a key or password in PHP.
- [TCrypto](https://github.com/timoh6/TCrypto) - TCrypto is a simple and flexible PHP 5.3+ in-memory key-value storage library.

### Python

- [charm](https://github.com/JHUISI/charm) - a framework for rapidly prototyping cryptosystems.
- [cryptography](https://cryptography.io/en/latest/) - is a Python library which exposes cryptographic recipes and primitives.
- [cryptopy](https://sourceforge.net/projects/cryptopy/) - is a pure python implmentation of cryptographic algorithms and applications.
- [hashids](https://github.com/davidaurelio/hashids-python) - Implementation of [hashids](http://hashids.org) in Python.
- [paramiko](http://www.paramiko.org/) - a Python implementation of the SSHv2 protocol, providing both client and server functionality.
- [pycrypto](https://github.com/dlitz/pycrypto) - The Python Cryptography Toolkit.
- [pycryptodome](https://github.com/Legrandin/pycryptodome) - is a self-contained Python package of low-level cryptographic primitives.
- [PyElliptic](https://github.com/yann2192/pyelliptic) - Python OpenSSL wrapper. For modern cryptography with ECC, AES, HMAC, Blowfish.
- [pynacl](https://github.com/pyca/pynacl) - Python binding to the Networking and Cryptography (NaCl) library.

### Ruby

- [RbNaCl](https://github.com/cryptosphere/rbnacl) - Ruby binding to the Networking and Cryptography (NaCl) library.

### Rust

- [octavo](https://github.com/libOctavo/octavo) - Highly modular & configurable hash & crypto library.
- [ring](https://github.com/briansmith/ring) - Safe, fast, small crypto using Rust & BoringSSL's cryptography primitives.
- [rust-crypto](https://github.com/DaGenix/rust-crypto) - a (mostly) pure-Rust implementation of various cryptographic algorithms.
- [rust-openssl](https://github.com/sfackler/rust-openssl) - OpenSSL bindings for Rust.
- [sodiumoxide](https://github.com/dnaq/sodiumoxide) - Sodium Oxide: Fast cryptographic library for Rust (bindings to libsodium).
- [suruga](https://github.com/klutzy/suruga) - TLS 1.2 implementation in Rust.
- [webpki](https://github.com/briansmith/webpki) - Web PKI TLS X.509 certificate validation in Rust.

### Scala

- [scrypto](https://github.com/input-output-hk/scrypto) - Cryptographic primitives for Scala.

### Swift

- [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - Crypto related functions and helpers for Swift implemented in Swift programming language.
- [IDZSwiftCommonCrypto](https://github.com/iosdevzone/IDZSwiftCommonCrypto) - a wrapper for Apple's Common Crypto library written in Swift.
- [OpenSSL](https://github.com/Zewo/OpenSSL) - Swift OpenSSL for OS X and Linux.
- [SweetHMAC](https://github.com/jancassio/SweetHMAC) - a tiny and easy to use Swift class to encrypt strings using HMAC algorithms.
- [Swift-Sodium](https://github.com/jedisct1/swift-sodium) - Swift interface to the Sodium library for common crypto operations for iOS and OS X.
- [SwiftSSL](https://github.com/SwiftP2P/SwiftSSL) - an Elegant crypto toolkit in Swift.

## Resources

### Web-tools

- [Crypo](http://crypo.bz.ms/encryptors) - Best encryption for network security.Encrypt or Decrypt sensitive data using AES/DES/RCA encryptors (security tools).
- [Cryptolab](http://manansingh.github.io/Cryptolab-Offline/cryptolab.html) - is a set of cryptography related tools.
- [CrypTool](http://www.cryptool-online.org/) - A great variety of ciphers, encryption methods and analysis tools are introduced, often together with illustrated examples.
- [keybase.io](https://keybase.io/) - Keybase maps your identity to your public keys, and vice versa.

### Web-sites

- [Cryptography Stackexchange](http://crypto.stackexchange.com/) - Cryptography Stack Exchange is a question and answer site for software developers, mathematicians and others interested in cryptography.
- [Garykessler Crypto](http://www.garykessler.net/library/crypto.html) - An Overview of Cryptography.
- [IACR](https://www.iacr.org/) - The International Association for Cryptologic Research is a non-profit scientific organization whose purpose is to further research in cryptology and related fields.
- [Learn Cryptography](https://learncryptography.com/) - is dedicated to helping people understand how and why the cryptographic systems they use everyday without realizing work to secure and protect their privacy.
- [Subreddit of Cryptography](https://www.reddit.com/r/cryptography/) - This subreddit is intended for links and discussions surrounding the theory and practice of strong cryptography.
- [WebCryptoAPI](https://www.w3.org/TR/WebCryptoAPI/) - This specification describes a JavaScript API for performing basic cryptographic operations in web applications, such as hashing, signature generation and verification, and encryption and decryption.

### Blogs

- [A Few Thoughts on Cryptographic Engineering](http://blog.cryptographyengineering.com/) - Some random thoughts about crypto.
- [Bristol Cryptography Blog](http://bristolcrypto.blogspot.co.uk/) - The official blog for the University of Bristol cryptography research group. It's a group blog, primarily targeted towards cryptographers and crypto students.
- [Charles Engelke's Blog](https://blog.engelke.com/tag/webcrypto/) - WebCrypto Blog Posts.
- [Root Labs rdist](https://rdist.root.org/) - Nate Lawson and his co-authors write on a variety of topics including hardware implementation, cryptographic timing attacks, DRM, and the Commodore 64.
- [Schneier on security](https://www.schneier.com/) - One of the oldest and most famous security blogs. Bruce covers topics from block cipher cryptanalysis to airport security.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/sobolevn/awesome-cryptography/blob/master/CONTRIBUTING.md) first.

## License

`awesome-cryptography` by sobolevn

To the extent possible under law, the person who associated CC0 with
`awesome-cryptography` has waived all copyright and related or neighboring
rights to `awesome-cryptography`.

You should have received a copy of the CC0 legalcode along with this
work.  If not, see <http://creativecommons.org/publicdomain/zero/1.0/>.
