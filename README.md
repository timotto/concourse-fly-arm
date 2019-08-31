# Concourse fly CLI for ARM

This is a Concourse pipeline to build the fly CLI for ARM.

It uses [xgo](https://github.com/karalabe/xgo) to cross compile the binaries as since version 5.4.0 a plain go cross compile is not possible any longer.
