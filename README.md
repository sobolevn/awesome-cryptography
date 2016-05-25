# Awesome Cryptography [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of cryptography resources and links

- [Theory](#theory)
    - [Books](#books)
    - [Courses](#courses)
    - [Articles](#articles) 
- [Frameworks and Libs](#frameworks-and-libs)
    - [C](#c-libs)
    - [C++](#cpp-libs)
    - [C#](#csharp-lib)
    - [Clojure](#clojure-libs)
    - [Common Lisp](#common-lisp-libs)
    - [Delphi](#delphi-libs)
    - [Elixir](#elixir-libs)
    - [Golang](#go-libs)
    - [Haskell](#haskell-libs)  
    - [Haxe](#hexe-libs)
    - [Java](#java-libs)
    - [Julia](#julia-libs)
    - [Lua](#lua-libs)
    - [Objective-C](#objective-c-libs)
    - [PHP](#php-libs)
    - [Python](#python-libs)
    - [Ruby](#ruby-libs)
    - [Rust](#rust-libs)
    - [Scala](#scala-libs)
    - [Swift](#swift-libs)
- [Resources](#resources)
    - [Websites](#websites)
    - [Weekly](#weekly)
    - [Twitter](#twitter)
- [Web Apps](#other-awesome-lists)
    - [...]()

- [Contributing](#contributing)
    - [...]()

- - -

## Theory
* Books
    * [An Introduction to Mathematical Cryptography](http://www.math.brown.edu/~jhs/MathCryptoHome.html) -  is an introduction to modern cryptography.
    * [Security Engineering](http://www.cl.cam.ac.uk/~rja14/book.html) - There is an extraordinary textbook written by Ross Anderson, professor of computer security at University of Cambridge.
    * [OpenSSL Cookbook](https://www.feistyduck.com/library/openssl-cookbook/) - The book about OpenSSL.
    * [Crypto101](https://www.crypto101.io/) - Crypto 101 is an introductory course on cryptography.
    * [Handbook of Applied Cryptography](http://cacr.uwaterloo.ca/hac/index.html) - This book is intended as a reference for professional cryptographers
    * [Introduction to Modern Cryptography](http://www.cs.umd.edu/~jkatz/imc.html) -  is an introductory-level treatment of cryptography written from a modern, computer science perspective.
    * [The Cryptoparty Handbook](https://unglue.it/work/141611/) - This book provides a comprehensive guide to the various topics of the computer and internet security
    * [Cryptography Engineering](https://www.schneier.com/books/cryptography_engineering/) - Learn to build cryptographic protocols that work in the real world    

* Courses
    * [Cryptography I](https://www.coursera.org/learn/crypto)
    * [Cryptography - Stanford University](http://online.stanford.edu/course/cryptography)
    * [Cybrary Cryptography](https://www.cybrary.it/course/cryptography/)
    * [Applied Cryptography](https://www.udacity.com/course/applied-cryptography--cs387)


## Frameworks and Libs
* C
    * [cryptlib](http://www.cryptlib.com/) -  is an open source cross-platform software security toolkit library
    * [retter](https://github.com/maciejczyzewski/retter) - a collection of hash functions, ciphers, tools and libraries.
    * [xxHash](https://github.com/Cyan4973/xxHash) - Extremely fast hash algorithm
    * [libtomcrypt](https://github.com/libtom/libtomcrypt) - is a fairly comprehensive, modular and portable cryptographic toolkit
    * [libgcrypt](http://directory.fsf.org/wiki/Libgcrypt) - is a cryptographic library developed as a separated module of GnuPG.
    * [NaCl](https://nacl.cr.yp.to/) - high-speed library for network communication, encryption, decryption, signatures, etc.
    * [tiny-AES128-C](https://github.com/kokke/tiny-AES128-C) - Small portable AES128 in C.

* C++
    * [Crypto++](https://www.cryptopp.com/) - Crypto++ Library is a free C++ class library of cryptographic schemes.
    * [Bcrypt](http://bcrypt.sourceforge.net/) - a cross platform file encryption utility.
    * [Botan](https://botan.randombit.net/) - is a cryptography library written in C++11
    * [libsodium](https://github.com/jedisct1/libsodium) - a modern and easy-to-use crypto library.
    * [Nettle](http://www.lysator.liu.se/~nisse/nettle/) -a low-level cryptographic library.
    * [s2n](https://github.com/awslabs/s2n) - an implementation of the TLS/SSL protocols

* Clojure
    * [buddy-core](https://funcool.github.io/buddy-core/latest/) - Cryptographic Api.

* Common Lisp
    * [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts) - Collection of common cryptography functions.
    * [ironclad](http://method-combination.net/lisp/ironclad/) - Collection of common crypto shortcuts.
    * [trivial-ssh](https://github.com/eudoxia0/trivial-ssh) - an SSH client library for Common Lisp (Built on libssh2)

* Delphi
    * [DelphiEncryptionCompendium](https://github.com/winkelsdorf/DelphiEncryptionCompendium/releases) - Cryptographic library for Delphi.
    * [LockBox](https://sourceforge.net/projects/tplockbox/) - LockBox 3 is a Delphi library for cryptography.
    * [SynCrypto](https://github.com/synopse/mORMot/blob/master/SynCrypto.pas) - Fast cryptographic routines (hashing and cypher), implementing AES, XOR, RC4, ADLER32, MD5, SHA1, SHA256 algorithms, optimized for speed.
    * [TForge](https://bitbucket.org/sergworks/tforge) - TForge is open-source crypto library written in Delphi, compatible with FPC.

* Elixir
    * [cipher](https://github.com/rubencaro/cipher) - Elixir crypto library to encrypt/decrypt arbitrary binaries.
    * [cloak](https://github.com/danielberkompas/cloak) - Cloak makes it easy to use encryption with Ecto.
    * [comeonin](https://github.com/elixircnx/comeonin) - Password authorization (bcrypt) library for Elixir.
    * [elixir_tea](https://github.com/keichan34/elixir_tea) - TEA implementation in Elixir.
    * [elixir-rsa](https://github.com/trapped/elixir-rsa) - `public_key` cryptography wrapper for Elixir.
    * [ex_crypto](https://github.com/ntrepid8/ex_crypto) - Elixir wrapper for Erlang `crypto` and `public_key` modules. Provides sensible defaults for many crypto functions to make them easier to use.
    * [exgpg](https://github.com/rozap/exgpg) - Use gpg from Elixir.
    * [pot](https://github.com/yuce/pot) - Erlang library for generating one time passwords compatible with Google Authenticator.
    * [siphash-elixir](https://github.com/zackehh/siphash-elixir) - Elixir implementation of the SipHash hash family.

* Go
    * [crypto](https://golang.org/pkg/crypto/) - Official Website Resources.
    * [cryptoballot](https://github.com/cryptoballot/cryptoballot) - Cryptographically secure online voting.
    * [dedis/crypto](https://github.com/dedis/crypto) - Advanced crypto library for the Go language
    * [gocrypto](https://github.com/kisom/gocrypto) - Example source code for the Practical Crypto with Go book.

* Haskell
    * [Cryptography & Hashing](https://wiki.haskell.org/Applications_and_libraries/Cryptography) - Official Website of Haskell
    * [Crypto](http://hackage.haskell.org/packages/#cat:Crypto) - a collaborative Hackage list.
    * [Cryptography](http://hackage.haskell.org/packages/#cat:Cryptography) - a collaborative Hackage list.

* Hexe
    * [haxe-crypto](http://lib.haxe.org/p/haxe-crypto/) - Haxe Cryptography Library.

* Java
    * [Apache Shiro](http://shiro.apache.org/) - Performs authentication, authorization, cryptography and session management.
    * [Bouncy Castle](https://www.bouncycastle.org/java.html) - All-purpose cryptographic library. JCA provider, wide range of functions from basic helpers to PGP/SMIME operations.
    * [Google Keyczar](https://github.com/google/keyczar) - Easy to use, yet safe encryption framework with key versioning.
    * [pac4j ](https://github.com/pac4j/pac4j) - Security engine.

* Julia
    * [Crypto.jl](https://github.com/danielsuo/Crypto.jl) - A library that wraps OpenSSL, but also has pure Julia implementations for reference.

* Lua
    * [LuaCrypto](https://github.com/mkottman/luacrypto) - Lua bindings to OpenSSL.
    * [lua-lockbox ](https://github.com/somesocks/lua-lockbox) - A collection of cryptographic primitives written in pure Lua.

* Objective-C
    * [Themis](https://github.com/cossacklabs/themis) - High-level crypto library, providing basic asymmetric encryption.

* PHP
    * [halite](https://paragonie.com/project/halite) - A simple library for encryption using [libsodium](https://github.com/jedisct1/libsodium).
    * [PHP Encryption](https://github.com/defuse/php-encryption) - This is a library for encrypting data with a key or password in PHP.
    * [TCrypto](https://github.com/timoh6/TCrypto) - TCrypto is a simple and flexible PHP 5.3+ in-memory key-value storage library.

* Python
    * [cryptography](https://cryptography.io/en/latest/) - is a Python library which exposes cryptographic recipes and primitives.
    * [pycrypto](https://github.com/dlitz/pycrypto) - The Python Cryptography Toolkit
    * [hashids](https://github.com/davidaurelio/hashids-python) - Implementation of [hashids](http://hashids.org) in Python.
    * [paramiko](http://www.paramiko.org/) - a Python implementation of the SSHv2 protocol, providing both client and server functionality.
    * [pynacl](https://github.com/pyca/pynacl) - Python binding to the Networking and Cryptography (NaCl) library

* Ruby
    * [RbNaCl](https://github.com/cryptosphere/rbnacl) - Ruby binding to the Networking and Cryptography (NaCl) library.

* Rust
    * [ring](https://github.com/briansmith/ring) - Safe, fast, small crypto using Rust & BoringSSL's cryptography primitives.
    * [webpki](https://github.com/briansmith/webpki) - Web PKI TLS X.509 certificate validation in Rust.
    * [rust-crypto](https://github.com/DaGenix/rust-crypto) - A (mostly) pure-Rust implementation of various cryptographic algorithms.
    * [sodiumoxide](https://github.com/dnaq/sodiumoxide) - Sodium Oxide: Fast cryptographic library for Rust (bindings to libsodium).
    * [suruga](https://github.com/klutzy/suruga) - TLS 1.2 implementation in Rust.
    * [octavo](https://github.com/libOctavo/octavo) - Highly modular & configurable hash & crypto library.
    * [common.rs](https://github.com/seb-m/common.rs) - Common Rust crypto utilities.
    * [rust-openssl](https://github.com/sfackler/rust-openssl) - OpenSSL bindings for Rust.

* Scala
    * [scrypto](https://github.com/ScorexProject/scrypto) - Cryptographic primitives for Scala.

* Swift
    * [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - Crypto related functions and helpers for Swift implemented in Swift programming language.
    * [IDZSwiftCommonCrypto](https://github.com/iosdevzone/IDZSwiftCommonCrypto) - A wrapper for Apple's Common Crypto library written in Swift.
    * [OpenSSL](https://github.com/Zewo/OpenSSL) - Swift OpenSSL for OS X and Linux.
    * [SweetHMAC](https://github.com/jancassio/SweetHMAC) - A tiny and easy to use Swift class to encrypt strings using HMAC algorithms.
    * [Swift-Sodium](https://github.com/jedisct1/swift-sodium) - Swift interface to the Sodium library for common crypto operations for iOS and OS X.
    * [SwiftSSL](https://github.com/SwiftP2P/SwiftSSL) - An Elegant crypto toolkit in Swift.


# Contributing