NiTriShape Converter (Optimizer)
================================

A command line tool to convert and optimize between NiTriShape and BSTriShape.

## Usage
```
nifopt.exe your.nif
```

### Optimize for Skyrim SE
Convert NiTriShape to BSTriShape.
Equivalent to SSE Nif Optimizer by ousnius.

Example:
```
$ nifopt.exe ankh_1-1.nif
NiVersion file: 0x14020007 user: 12 stream: 83
Optimize for Skyrim SE.
Save to ankh_1-1.opt.nif
```

### Revert for Skyrim LE
Convert BSTriShape to NiTriShape.

Example:
```
$ nifopt.exe ankh_1-2.nif
NiVersion file: 0x14020007 user: 12 stream: 100
Revert for Skyrim LE.
Save to ankh_1-2.rev.nif
```

## License
[GPLv3](https://github.com/opparco/nifopt/blob/master/LICENSE)

## Author
opparco
