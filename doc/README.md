Linuxcoin Core 0.13.2
=====================

Setup
---------------------
[Linuxcoin Core](http://linuxcoin.org/en/download) is the original Linuxcoin client and it builds the backbone of the network. However, it downloads and stores the entire history of Linuxcoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

Running
---------------------
The following are some helpful notes on how to run Linuxcoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/linuxcoin-qt` (GUI) or
- `bin/linuxcoind` (headless)

### Windows

Unpack the files into a directory, and then run linuxcoin-qt.exe.

### OS X

Drag Linuxcoin-Core to your applications folder, and then run Linuxcoin-Core.

### Need Help?

* See the documentation at the [Linuxcoin Wiki](https://linuxcoin.info/)
for help and more information.
* Ask for help on [#linuxcoin](http://webchat.freenode.net?channels=linuxcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=linuxcoin).
* Ask for help on the [LinuxcoinTalk](https://linuxcointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Linuxcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Linuxcoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [LinuxcoinTalk](https://linuxcointalk.io/) forums.
* Discuss project-specific development on #linuxcoin on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=linuxcoin).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
