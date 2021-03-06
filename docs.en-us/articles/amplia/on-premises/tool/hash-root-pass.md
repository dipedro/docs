﻿# Amplia command: **hash-root-pass**

## Name

`hash-root-pass` - Computes a salted hash for a given root password

## Syntax

```sh
dotnet Lacuna.Amplia.Site.dll -- hash-root-pass
```

Or, on Docker:

```sh
docker run -i lacunasoftware/amplia:3.8 -- hash-root-pass
```

## Description

The `hash-root-pass` command is meant to be used with *root authentication mode*. Use it to compute a salted hash of the desired
root password, and then *set the hash on the configuration file*.

The password is read from the `stdin`.

## See also

* [Amplia command-line tool](index.md)
* Root authentication mode
