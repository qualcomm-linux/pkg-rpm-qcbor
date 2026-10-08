# pkg-rpm-qcbor

RPM packaging for [`laurencelundblade/QCBOR`](https://github.com/laurencelundblade/QCBOR)
— A powerfull comprehensive commercial-quality CBOR encoder/decoder that is
suitable for Embedded and IOT devices.

This repo builds and publishes the `qcbor` RPM via the shared
[`qualcomm-linux/qcom-rpm-utils`](https://github.com/qualcomm-linux/qcom-rpm-utils)
reusable workflows — it follows the same one-package-per-repo template used
across `qualcomm-linux/pkg-rpm-*`.

## Branches

Following the Fedora/CentOS **dist-git** convention, each distro stream gets its
own branch, and the packaging files live at the branch root:

| Branch | Stream | Contents |
|---|---|---|
| `main` | — | Template docs, onboarding guide, community files. Nothing is built here. |
| **`c10s`** | CentOS 10 Stream | **This branch.** `qcbor.spec` + `sources` + workflows. |

Full onboarding guide, configuration reference, and troubleshooting live on
[`main`](../../tree/main) — see its `README.md` and `docs/workflows.md`.

## Installation Instructions

```
sudo rpm -i qcbor-x.aarch64.rpm
sudo rpm -i qcbor-devel-x.aarch64.rpm
sudo rpm -i qcbor-docs-x.aarch64.rpm
```

## Getting in Contact

How to contact maintainers. E.g. GitHub Issues, GitHub Discussions could be indicated for many cases. However a mail list or list of Maintainer e-mails could be shared for other types of discussions. E.g.

* [Report an Issue on GitHub](../../issues)
* [Open a Discussion on GitHub](../../discussions)

## License

pkg-rpm-qcbor is licensed under the [BSD-3-clause License](https://spdx.org/licenses/BSD-3-Clause.html). See [LICENSE.txt](LICENSE.txt) for the full license text.
