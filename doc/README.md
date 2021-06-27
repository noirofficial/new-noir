Noir Core
=============

Setup
---------------------
[Noir Core] (https://noirofficial.org/) is the original Noir client and it builds the backbone of the network. However, it downloads and stores the entire history of Noir transactions (which is currently several hundreds MBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

Running
---------------------
The following are some helpful notes on how to run Noir Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/noir-qt` (GUI) or
- `bin/noird` (headless)

### Windows

Unpack the files into a directory, and then run noir-qt.exe.

### macOS

Drag Noir Core to your applications folder, and then run Noir Core.

### Need Help?

* Ask for help on Discord: https://discord.gg/J3qquSz

Building
---------------------
The following are developer notes on how to build Noir Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/noirofficial/docs/blob/master/gitian-building.md)

Development
---------------------
The Noir repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss project-specific development on #general on our Discord. https://discord.gg/J3qquSz

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
