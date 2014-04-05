What is Helixcoin?
==============

An alternative cryptocurrency disrupting the already rather disrupting crypto market.

Technical Information

+ 120,000,000 coins
+ 151 coins rewarded per block, halving every ~6 months
+ 40 second block times
+ difficulty retargeting using Kimoto Gravity Well

Notable differences from Bitcoin
-----------------------------

+ replacement of ECDSA with Schnorr signing
+ use of secp256r1 curve over secp256k1
+ requirement for public key when verifying transactions
+ modification to RPC interface s.t. public keys are Base64 encoded

Modifications to the RPC API
+ verifymessage <helixcoinaddress> <publickey> <signature> <message>

rpcport=9504 
port=9505

Forked from Bitcoin reference wallet 0.8.5 and MaxCoin

-----------------------------
helixcoin.conf

server=1 
listen=1 
daemon=1 
rpcport=9504
port=9505
rpcallowip=127.0.0.1
rpcconnect=127.0.0.1
rpcallowip=localhost
rpcconnect=localhost
rpcuser=helix
rpcpassword=coin
addnode=107.170.69.245
addnode=198.199.85.33
addnode=107.170.233.189
addnode=188.226.156.210


License
------

Helixcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.
