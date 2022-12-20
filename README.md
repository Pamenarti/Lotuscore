PRW -  Lotuscoin Core integration/staging tree (yes tree)
=====================================
NOTE::  This repository is updated for OpenSSL 1.1.  
If your system runs older OpenSSL (run "openssl version" to see)  you will need to 
revert the changes in the commit for updated Openssl or run the repository at:  

https://github.com/funkshelper/woodcore-openssl-1.0

This project is a fully armed and operational bitcoin-core ported to the lotuscoin network.  

Dedicated to Sipa, Nullc, and Coblee.  Props and Kudos.  

Three tasks have made this port complete:

1) Skein hash function for Proof Of Work inserted
2) prime256r1 for ECDSA signatures (including backport to OpenSSL and removal of libsecp256k1)
3) Logarithmic supply curve for long-term economics

Voila - we now have a segwit-enabled lotuscoin client in place for those who would like to use it.


https://github.com/Pamenarti/lotuscoin.git

Other clients including Lotuscoin-minimal and Fo-Realz-Lotuscoin are also available.  





https://Lotuscoin.org


-------------------

Developer IRC can be found on Freenode at #Lotuscoin-dev and #Lotuscoin.

