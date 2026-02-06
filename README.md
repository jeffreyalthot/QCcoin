Bitcoin Core
=============

Setup
---------------------
Bitcoin Core is the original Bitcoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Bitcoin transactions, which requires several hundred gigabytes or more of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to several days or more.

To download Bitcoin Core, visit [bitcoincore.org](https://bitcoincore.org/en/download/).

Running
---------------------
The following are some helpful notes on how to run Bitcoin Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/bitcoin-qt` (GUI) or
- `bin/bitcoind` (headless)
- `bin/bitcoin` (wrapper command)

The `bitcoin` command supports subcommands like `bitcoin gui`, `bitcoin node`, and `bitcoin rpc` exposing different functionality. Subcommands can be listed with `bitcoin help`.

### Windows

Unpack the files into a directory, and then run bitcoin-qt.exe.

### macOS

Drag Bitcoin Core to your applications folder, and then run Bitcoin Core.

### Need Help?

* See the documentation at the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page)
for help and more information.
* Ask for help on [Bitcoin StackExchange](https://bitcoin.stackexchange.com).
* Ask for help on #bitcoin on Libera Chat. If you don't have an IRC client, you can use [web.libera.chat](https://web.libera.chat/#bitcoin).
* Ask for help on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Technical Support board](https://bitcointalk.org/index.php?board=4.0).

Building
---------------------
The following are developer notes on how to build Bitcoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](doc/dependencies.md)
- [macOS Build Notes](doc/build-osx.md)
- [Unix Build Notes](doc/build-unix.md)
- [Windows Build Notes](doc/build-windows-msvc.md)
- [FreeBSD Build Notes](doc/build-freebsd.md)
- [OpenBSD Build Notes](doc/build-openbsd.md)
- [NetBSD Build Notes](doc/build-netbsd.md)

Development
---------------------
The Bitcoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](doc/developer-notes.md)
- [Productivity Notes](doc/productivity.md)
- [Release Process](doc/release-process.md)
- [Source Code Documentation (External Link)](https://doxygen.bitcoincore.org/)
- [Translation Process](doc/translation_process.md)
- [Translation Strings Policy](doc/translation_strings_policy.md)
- [JSON-RPC Interface](doc/JSON-RPC-interface.md)
- [Unauthenticated REST Interface](doc/REST-interface.md)
- [BIPS](doc/bips.md)
- [Dnsseed Policy](doc/dnsseed-policy.md)
- [Benchmarking](doc/benchmarking.md)
- [Internal Design Docs](doc/design/)

### Resources
* Discuss on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Development & Technical Discussion board](https://bitcointalk.org/index.php?board=6.0).
* Discuss project-specific development on #bitcoin-core-dev on Libera Chat. If you don't have an IRC client, you can use [web.libera.chat](https://web.libera.chat/#bitcoin-core-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](doc/bitcoin-conf.md)
- [CJDNS Support](doc/cjdns.md)
- [Files](doc/files.md)
- [Fuzz-testing](doc/fuzzing.md)
- [I2P Support](doc/i2p.md)
- [Init Scripts (systemd/upstart/openrc)](doc/init.md)
- [Managing Wallets](doc/managing-wallets.md)
- [Multisig Tutorial](doc/multisig-tutorial.md)
- [Offline Signing Tutorial](doc/offline-signing-tutorial.md)
- [P2P bad ports definition and list](doc/p2p-bad-ports.md)
- [PSBT support](doc/psbt.md)
- [Reduce Memory](doc/reduce-memory.md)
- [Reduce Traffic](doc/reduce-traffic.md)
- [Tor Support](doc/tor.md)
- [Transaction Relay Policy](policy/README.md)
- [ZMQ](doc/zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
