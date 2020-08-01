# Gentoo-overlays

Gentoo ebuilds optimized for myself or not available in official portage.

- tensorflow-2.2.0
- tensorflow-2.3.0

# Workflow

1. download this project and move ebuild files to, e.g., `/usr/local/portage`
2. move patches `sci-libs/tensorflow/files/tensorflow-{version}*` to `/etc/portage/patches/sci-libs/tensorflow-{version}/`
3. run `sudo ebuild /usr/local/portage/sci-libs/tensorflow/tensorflow-{version}.ebuild manifest clean merge` to build the package
4. run `sudo ebuild /usr/local/portage/sci-libs/tensorflow/tensorflow-{version}.ebuild install` to install the package

replace `{version}` to the version (e.g. 2.3.0) you're working on.
