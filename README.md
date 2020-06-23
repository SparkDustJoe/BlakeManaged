# BlakeManaged
Blake 2 &amp; 3 (all flavors) ported to C# .Net Core

A C# Port of the Blake family of hashing algorithms (this is mostly a fork of Christian Winnerlein's work / CodesInChaos)

Includes Blake2b (64b) and Blake2s (32b), and the new Blake3

__THIS SHOULD NOT BE USED FOR PASSWORD HASHING!! Use Argon2 for passwords or login credential hashing!__

These hashes are meant for SPEED, mainly for data and file integrety checking (where speed and collision resistance are king).  Can be Keyed. 

Password hashing should NOT be fast, and should be memory hardened, which Argon2 does (Argon2 uses BLAKE2 operations internally).  

==================

Some code originally written in 2012 by Christian Winnerlein codesinchaos@gmail.com

Rewritten and expanded in 2015, and 2020 by Dustin J Sparks sparkdustjoe@gmail.com

"To the extent possible under law, the author(s) have dedicated all copyright and related and neighboring rights to this software to the public domain worldwide. This software is distributed without any warranty.

You should have received a copy of the CC0 Public Domain Dedication along with this software. If not, see http://creativecommons.org/publicdomain/zero/1.0/.

Based on BlakeSharp by Dominik Reichl dominik.reichl@t-online.de Web: http://www.dominik-reichl.de/ If you're using this class, it would be nice if you'd mention me somewhere in the documentation of your program, but it's not required.

BLAKE was designed by Jean-Philippe Aumasson, Luca Henzen, Willi Meier and Raphael C.-W. Phan. BlakeSharp was derived from the reference C implementation."
