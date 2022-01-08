# Gentoo-overlays

Tensorflow/Pytorch ebuilds optimized for Gentoo Linux.

Supported versions:
- tensorflow-2.2.0
- tensorflow-2.3.0
- pytorch-1.9.0
- python-1.10.2-rc2

# Workflow

1. download this project and save to, e.g., `/usr/local/portage`
2. run `sudo ebuild /usr/local/portage/sci-libs/{pkg}/{pkg}-{version}.ebuild manifest clean merge` to install the package

replace `{pkg}` and `{version}` to the package (e.g. pytorch-1.10.2) you're working on.
