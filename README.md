# electrumx-installer
This is a fork from [Bauerj](https://github.com/bauerj/electrumx-installer)'s electrumx-installer that supports Ubuntu 22.04 with Python 3.8 installation.

## Usage
This installs electrumx using the default options:

    wget https://raw.githubusercontent.com/bauerj/electrumx-installer/master/bootstrap.sh -O - | bash

You can also set some options if you want more control:

| -d --dbdir | Set database directory (default: /db/) |
|------------|----------------------------------------|
| --update   | Update previously installed version    |
| --leveldb  | Use LevelDB instead of RocksDB         |

For example:

    wget https://raw.githubusercontent.com/bauerj/electrumx-installer/master/bootstrap.sh -O - | bash -s - -d /media/ssd/electrum-db


If you prefer a different operating system that's not listed here, see
[`distributions/README.md`](https://github.com/bauerj/electrumx-installer/blob/master/distributions/README.md) to find out how to add it.
Or open an [issue](https://github.com/bauerj/electrumx-installer/issues/new) if you'd rather not do that yourself.
