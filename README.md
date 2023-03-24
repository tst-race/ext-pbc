# PBC for RACE

This repo provides scripts to custom-build the
[PBC library](https://crypto.stanford.edu/pbc/) for RACE.

## License

The PBC library is licensed under the LGPL license

Only the build scripts in this repo are licensed under Apache 2.0.

## Dependencies

PBC has no dependencies on any custom-built libraries.

## How To Build

The [ext-builder](https://github.com/tst-race/ext-builder) image is used to
build PBC.

```
git clone https://github.com/tst-race/ext-builder.git
git clone https://github.com/tst-race/ext-pbc.git
./ext-builder/build.py \
    --target linux-x86_64 \
    ./ext-pbc
```

## Platforms

PBC is built for the following platforms:

* `linux-x86_64`
* `linux-arm64-v8a`

## How It Is Used

PBC is used by the <TO-BE-NAMED> plugin.
