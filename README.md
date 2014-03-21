Spartancoin integration/staging tree
================================

http://www.spartancoin.org

Copyright (c) 2009-2013 Bitcoin Developers
Copyright (c) 2011-2013 Litecoin Developers
Copyright (c) 2014 Spartancoin Developers


What is Spartancoin?
----------------

Spartancoin is a version os Litecoin using scrypt as a proof-of-work algorithm.
 - 1 minute block targets
 - subsidy halves in 500,000 blocks
 - ~109 billions total coins
 - 100,000 coins per block
 - Difficulty Retarget: Every block using Kimoto's gravity well.

For more information, as well as an immediately useable, binary version of
the Spartancoin client sofware, see http://www.spartancoin.org.

License
-------

Spartancoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Spartancoin
development team members simply pulls it.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/spartancoin/spartancoin) are created
regularly to indicate new official, stable release versions of Spartancoin.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money.
