


# Build Go using toolchain on tip

Architecture is set `amd64`.
Zipped `go` and `gofmt` is available for download (except on Travis-CI).

Platforms:
- [Github Actions - Linux](https://github.com/iwdgo/go-upon-ci) [![Go](https://github.com/iwdgo/go-upon-ci/actions/workflows/go.yml/badge.svg)](https://github.com/iwdgo/go-upon-ci/actions/workflows/go.yml)
- [Github Actions - Windows](https://github.com/iwdgo/go-upon-ci/tree/master-windows) [![Go](https://github.com/iwdgo/go-upon-ci/actions/workflows/go.yml/badge.svg?branch=master-windows)](https://github.com/iwdgo/go-upon-ci/actions/workflows/go.yml?query=branch%3Amaster-windows)
- [Github Actions - Windows](https://github.com/iwdgo/go-upon-ci/tree/master-macos) [![Go](https://github.com/iwdgo/go-upon-ci/actions/workflows/go.yml/badge.svg?branch=master-macos)](https://github.com/iwdgo/go-upon-ci/actions/workflows/go.yml?query=branch%3Amaster-macos)
- [Cirrus CI](https://github.com/iwdgo/go-upon-ci/tree/cirrusci) [![Build Status](https://api.cirrus-ci.com/github/iwdgo/go-upon-ci.svg)](https://cirrus-ci.com/github/iwdgo/go-upon-ci)
- [Travis CI](https://github.com/iwdgo/go-upon-ci/tree/travisci) [![Build Status](https://app.travis-ci.com/iwdgo/go-upon-ci.svg?branch=master)](https://app.travis-ci.com/iwdgo/go-upon-ci)


## Issue branch

A patch in git format is added on tip of the go repository.

Steps could be:
- `git clone github.com/iwdgo/go-upon-ci`
- `cd go-upon-ci`
- `git checkout issue...` to one of the issue branch
- Duplicate branch with something like `git checkout -b issue<#issue number>`
- Move patch created with something like `git format-patch master` 
- Push branch to your published repository.
