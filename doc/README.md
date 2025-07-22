Mountaincoin Core 0.14.2
=====================

Setup
---------------------
Mountaincoin Core is the original Mountaincoin client and it builds the backbone of the network. However, it downloads and stores the entire history of Mountaincoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Mountaincoin Core, visit [mountaincoin.org](https://mountaincoin.org).

Running
---------------------
The following are some helpful notes on how to run Mountaincoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/mountaincoin-qt` (GUI) or
- `bin/mountaincoind` (headless)

### Windows

Unpack the files into a directory, and then run mountaincoin-qt.exe.

### OS X

Drag Mountaincoin-Core to your applications folder, and then run Mountaincoin-Core.

### Need Help?

* See the documentation at the [Mountaincoin Wiki](https://mountaincoin.info/)
for help and more information.
* Ask for help on [#mountaincoin](http://webchat.freenode.net?channels=mountaincoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=mountaincoin).
* Ask for help on the [MountaincoinTalk](https://mountaincointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Mountaincoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Mountaincoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/mountaincoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [MountaincoinTalk](https://mountaincointalk.io/) forums.
* Discuss general Mountaincoin development on #mountaincoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=mountaincoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
