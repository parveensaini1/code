Perfectcoin integration/staging tree
================================

http://perfectcoininfo.com/

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Perfectcoin Developers

What is Perfectcoin?
----------------

Perfectcoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 35 minute block targets
 - subsidy halves in 30k blocks (~4 years)
 - ~10 million total coins

The rest is the same as Bitcoin.
 - 50 coins per block
 - 2016 blocks to retarget difficulty

For more information, as well as an immediately useable, binary version of
the Perfectcoin client sofware, see http://perfectcoininfo.com/

License
-------

Perfectcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Perfectcoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/perfectcoin-project/perfectcoin/tags) are created
regularly to indicate new official, stable release versions of Perfectcoin.
