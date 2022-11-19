# Sentinel OS base

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/sentinelos/pkgs)](https://github.com/sentinelos/base/releases)

## Getting Started

This repository contains the base files for each and every
Sentinel OS Containerfiles, along with the required patches and scripts,
if any.

It also contains some extra files and directories related to testing
(and therefore, building) those base on Github.

If you want to contribute, please read the
[contributor guide](CONTRIBUTING.md).
and feel free to either submit a [pull request](https://github.com/sentinelos/base/pulls) or a [issue](https://github.com/sentinelos/base/issues)

### Prerequisites

You can find some useful git hooks in the `.githooks` directory.
To use them, run the following command after cloning this repository:

```sh
git config --local core.hooksPath .githooks
```

## Versioning

We use [SemVer](http://semver.org/) for versioning. For all versions available, see the [tags on this repository](https://github.com/sentinelos/base/tags) or checkout the [release page](https://github.com/sentinelos/base/releases).

## License

This project is licensed under the Mozilla Public License Version 2.0 License - see the [LICENSE](LICENSE) file for details.

## Thank you

This project could not have been built without the following libraries or projects. They are either directly used in Sentinel OS or provided a lot of inspiration for the shape of the project:

- [The linux kernel](https://www.kernel.org/)
- [Git](https://git-scm.com/)
- [Alpine linux](https://www.alpinelinux.org/) and many others developers and companies.
