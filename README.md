# Python Builder

This work is based on a script of @pleiszenburg.

## Usage

```sh
$ ./pyb build
```

For usage information run `./pyb help`.

## Requirements

- bash
- curl
- gpg
- GNU Make
- tar

## Troubleshooting

Make sure to import the python release signing GPG key:

```sh
$ gpg --search-keys <key-id>
```

Note that I had to run this `gpg --keyserver=keys.gnupg.net --search-keys 0D96DF4D4110E5C43FBFB17F2D347EA6AA65421D` on Raspbian.
