# json-yang

How to validate JSON against a YANG module.

## Why

The need for some automated tool was expressed in the IETF CCAMP Transport
NBI Design Team (https://github.com/danielkinguk/transport-nbi).

## Getting started

See `validation.md` for a description of the process.

Prerequisites on Linux:

- `bash 4.3.11`
- `python 2.7.6`
- `pyang 1.7.1` exactly, not later
- `jing 20131210`
- `xmllint`
- `rfcstrip 0.2` patched to accept `-f`
- `perl 5.18` for testing only
-  the folding/unfolding script is downloaded from (https://tools.ietf.org/html/draft-kwatsen-netmod-artwork-folding-08)

## Thanks

Many thanks to all the design team and in particular to Carlo Perocchio.
