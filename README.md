# alphadocker

Experimental fork of [docker-on-lima](https://github.com/levsha/docker-on-lima) adapted for my specific use-case.

# Installation

```sh
brew install docker lima
sudo git clone https://github.com/Dan-Q/alphadocker /usr/local/lib/docker-on-lima
sudo ln -s /usr/local/lib/alphadocker/alphadocker /usr/local/bin/alphadocker
```

# Usage
```sh
alphadocker start
```

Takes a while to warm up. Then run `docker-compose up` or `docker ...` commands as usual.
