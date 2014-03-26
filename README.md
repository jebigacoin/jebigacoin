JebigaCoin Client v1.0.0
=======================

JebigaCoin - a fork of Litecoin & Luckycoin version with random bonus blocks. Like Litecoin it uses scrypt as a proof of work scheme.

Specs:
- 1 min block target
- Difficulty retargets every 240 min or 240 blocks
- Initially 69 coins per block, halves every 2 years (1,036,800 blocks)
- Total around 188 millions coins
- connection port is 6970, RPC-port 6996

Random Super-blocks: (based on LKY)
    For the 1st 50000 blocks
     - 15% chances 169 coins/block
     - 5% chances 6996 coins/block
     - 0.01% chances 69996 coins/block (expect 5 such blocks)


After 50000 blocks
    - 15% chances 2 times the normal coins (i.e. if normal is 69 coins, you get 138 coins)
    - 5% chances 5 times the normal coins
    - 0.01% chance 69 times the normal coins

Development process
===================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Litecoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'. 
