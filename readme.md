# Hybrid Backup Sync decipher (go)

![go-snapshot-build](https://github.com/Soontao/hbsdecipher-go/workflows/go-snapshot-build/badge.svg)
[![codecov](https://codecov.io/gh/Soontao/hbsdecipher-go/branch/master/graph/badge.svg?token=DOR3AOSCDH)](https://codecov.io/gh/Soontao/hbsdecipher-go)

This is a port of the Java version of [Hybrid Backup Sync](https://github.com/Mikiya83/hbs_decipher) entirely
written in go, small in size (< 3MB) and fast.
It currently supports only QNAP HBS version 2 and OpenSSL ciphered files.

## Usage

```bash
hbsdec (options) file1 directory2 ...
Options:
-o string
      output directory (optional)
-p string
      password for decryption
-r    traverse directories recursively
-v    verbose
```

## License:

Tool under GNU version 3 license.
