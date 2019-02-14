# Python Builder

This work is based on a script of [@pleiszenburg](https://github.com/pleiszenburg).

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
$ gpg --search-keys <public-key>
```

Note that I had to run this `gpg --keyserver=keys.gnupg.net --search-keys <public-key>` on Raspbian.
