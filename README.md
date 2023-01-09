[![Build Status](https://app.travis-ci.com/iwdgo/go-upon-ci.svg?branch=master)](https://app.travis-ci.com/iwdgo/go-upon-ci)
[![Build Status](https://api.cirrus-ci.com/github/iwdgo/go-upon-ci.svg)](https://cirrus-ci.com/github/iwdgo/go-upon-ci)
[![Go](https://github.com/iwdgo/go-upon-ci/actions/workflows/go.yml/badge.svg)](https://github.com/iwdgo/go-upon-ci/actions/workflows/go.yml)

# Build Go using toolchain on tip

Details on related branch:

- [Cirrus CI](https://github.com/iwdgo/go-upon-ci/tree/cirrusci)
- [Travis CI](https://github.com/iwdgo/go-upon-ci/tree/travisci)

## Github Actions

Toolchain runs Ubuntu on `amd64` which is the default image.
Artefact is available for download.

## Issue branch

To build a patched version using tip:
- Add a patch file to the `issue<#issue number>` branch using `git format-patch <your commit>` 
- Push to your published repository.