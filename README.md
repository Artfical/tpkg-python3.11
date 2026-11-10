# python3.11

Python 3.11.18 with pip (an older/other version beside python3): ssl, sqlite3, zlib, bz2, lzma, ctypes, readline, curses

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install python3.11
```

| | |
|---|---|
| Version | 3.11.18 |
| Licence | PSF-2.0 |
| Upstream | https://www.python.org |
| Needs | [`zlib`](https://github.com/Artfical/tpkg-zlib), [`openssl`](https://github.com/Artfical/tpkg-openssl), [`libffi`](https://github.com/Artfical/tpkg-libffi), [`bzip2`](https://github.com/Artfical/tpkg-bzip2), [`sqlite`](https://github.com/Artfical/tpkg-sqlite), [`readline`](https://github.com/Artfical/tpkg-readline), [`ncurses`](https://github.com/Artfical/tpkg-ncurses), [`ca-certificates`](https://github.com/Artfical/tpkg-ca-certificates) |
| Needs tOS build | 618 or newer |
| Size | 40653292 bytes (134265264 unpacked) |
| SHA-256 of the `.tpkg` | `b17d433b7d346d119e925ea5e48008f4b69cb7400cd7735ec375634b988d4777` |

## Commands it adds

| Command | Runs |
|---|---|
| `python3.11` | `bin/python3.11` |
| `pip3.11` | `bin/pip3.11` |
| `pydoc3.11` | `bin/pydoc3.11` |

## Download

The package file (`python3.11-3.11.18.tpkg`) and the sources it was built from are the assets of the
[v3.11.18 release](https://github.com/Artfical/tpkg-python3.11/releases/tag/v3.11.18).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `Python-3.11.18.tar.xz`

Check a download: `sha256sum python3.11-3.11.18.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: PSF-2.0. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
