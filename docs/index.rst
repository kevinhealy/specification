=============================
The Scrypt Language Reference
=============================

Scrypt is a high-level smart contract language for Bitcoin SV.
Bitcoin supports smart contract with its Forth-like stack based Script language. 
However writing smart contract in native Script is cumbersome and error-prone.
It quickly becomes intractable when the contract size and complexity grow.

Script is designed to facilitate writing smart contract running on chain.

* It is easy to learn. Syntactically, Scrypt is similar to Solidity, making it easier to be adopted by existing smart contract developers. However, the resemblance is only superficial, since Scrypt is compiled into Bitcoin Script by the underlying compiler, instead of EVM bytecode.
* It is statically typed. Type checking can help detect many errors at compile time
* It comes with a full-fledged IDE, including editor, compiler, and debugger. The first version is web based, no installation required to start playing immediately.


.. Warning:: Scrypt is still in experimental phase and not ready for production use.

.. toctree::
   :maxdepth: 2
   :caption: Introduction

   intro

.. toctree::
   :maxdepth: 2
   :caption: Language Specification

   syntax
   loop
   functions

.. toctree::
   :maxdepth: 1
   :caption: Scrypt by Example

   p2pkh
   rpuzzle
   ackermann
