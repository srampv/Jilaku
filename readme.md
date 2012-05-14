Bitcoin JavaScript Miner
========================

**Current Status**: Alpha


What is it?
-----------

This is a Bitcoin Miner implemented in JavaScript. 
Originally by [progranism](https://github.com/progranism/Bitcoin-JavaScript-Miner), improved by [kr105rlz](https://github.com/kr105rlz)
and [cmaclell](https://github.com/cmaclell/Bitcoin-JavaScript-Miner), here modified by me to work on [GAE](http://appengine.google.com).

It is intended for use
in a [Bitcoin Mining Pool](https://en.bitcoin.it/wiki/Pooled_mining), but
its main purpose is to act as a learning tool and micro web miner. Feel free to browse the commented source-code
and learn more about how Bitcoins are mined.

[Learn more about Bitcoin](http://www.bitcoin.org/ "Bitcoin")


How do I use it?
----------------

Download the full source code. You need a Google App Engine application defined and ready for code to be uploaded.
Modify the app.yaml according to your application name, modify the config file to use your pool credentials and you're off to mine.



Does It Really Mine Bitcoins?
-----------------------------

Yes, though it isn't very good at mining! It operates much slower
than even a standard CPU miner, and so it is unlikely to generate much income. However it can be loaded on a website so your visitors can calculate bitcoins for you.


***Important***
---------------

***Please read***, this miner doesn't implement any long-polling or chaching techniques to minimize unnecessary connections too the pool server.
Please use it only on a local bitcoin installation while those features are implemented.


Current Development Status
--------------------------

Currently being heavily worked on.


Thank You
---------

If you like this project, feel free contribute code, comments, and even Bitcoin donations.

*Donation Address for cmaclell*: 19ZhyDExua1b6ZzMMfvPdGpQTRnjkWZTYj
*Donation Address for kr105rlz*: 16TUsJ6ToAxp1a9RmTCGnox99MocGSYLaD

