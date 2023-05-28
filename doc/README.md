mnvip Core
=============

Setup
---------------------
[mnvip Core](https://masternode.vip/) is the original mnvip client and it builds the backbone of the network. However, it downloads and stores the entire history of mnvip transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run mnvip Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/mnvip-qt` (GUI) or
- `bin/mnvipd` (headless)

### Windows

Unpack the files into a directory, and then run mnvip-qt.exe.

### macOS

Drag mnvip-Qt to your applications folder, and then run mnvip-Qt.

### Need Help?

* See the documentation at the [mnvip Wiki](https://github.com/mnvip/mnvip)
for help and more information.
* Join our Discord server [Discord Server](https://discord.gg/2MYYCVPxeU)

Building
---------------------
The following are developer notes on how to build mnvip Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The mnvip repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://github.com/mnvip/mnvip)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [mnvip Homepage](https://github.com/mnvip/mnvip).
* Join the [mnvip Discord](https://discord.gg/2MYYCVPxeU).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
