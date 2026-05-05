# firetiger-oss Homebrew tap

Homebrew tap for command-line tools maintained by [firetiger-oss](https://github.com/firetiger-oss).

## Install

```sh
brew tap firetiger-oss/tap
brew install <formula>
```

## Formulae

| Formula | Description | Source |
| --- | --- | --- |
| `t4` | CLI for object storage across S3, GCS, R2, HTTP, and the local filesystem. | [firetiger-oss/tigerblock](https://github.com/firetiger-oss/tigerblock) |

## Updating

```sh
brew update
brew upgrade <formula>
```

## How this tap is maintained

Formulae in this repository are generated automatically by
[GoReleaser](https://goreleaser.com/) when a new version of the corresponding
upstream project is tagged. Pull requests to edit `Formula/*.rb` directly are
generally not accepted — fixes belong in the upstream project's release
configuration.

## License

Formulae files in this repository are licensed under the
[Apache License 2.0](LICENSE). The software each formula installs retains
its own license; see the upstream project for details.
