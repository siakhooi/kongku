# kongku

[![License](https://img.shields.io/github/license/siakhooi/kongku)](https://github.com/siakhooi/kongku/blob/main/LICENSE)
[![Release](https://img.shields.io/github/v/release/siakhooi/kongku)](https://github.com/siakhooi/kongku/releases/latest)
[![Build](https://img.shields.io/github/actions/workflow/status/siakhooi/kongku/build.yaml?label=build)](https://github.com/siakhooi/kongku/actions/workflows/build.yaml)
[![Go Reference](https://pkg.go.dev/badge/github.com/siakhooi/kongku.svg)](https://pkg.go.dev/github.com/siakhooi/kongku)
[![Quality Gate](https://sonarcloud.io/api/project_badges/measure?project=siakhooi_kongku&metric=alert_status)](https://sonarcloud.io/project/overview?id=siakhooi_kongku)
[![Coverage](https://qlty.sh/gh/siakhooi/projects/kongku/coverage.svg)](https://qlty.sh/gh/siakhooi/projects/kongku)
[![Funding](https://img.shields.io/badge/Funding-Wise-33cb56.svg?logo=wise)](https://wise.com/pay/me/siakn3)
![visitors](https://hit-tztugwlsja-uc.a.run.app/?outputtype=badge&counter=ghmd-kongku)

build descriptive story site

## Usage

```
kongku --help
kongku --version
```

`--version` prints the version, commit, and build date injected by `scripts/build.sh` and GoReleaser.

## Development

```
just ci
just build
```

`just build` writes binaries to `bin/` and snapshot packages to `dist/`. `just release` creates a GitHub release from `release.env`.
