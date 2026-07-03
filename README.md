# custom-linux-packages

Custom RPM packages, spec files, and build scripts for RHEL, Rocky, and Alma Linux.

## Structure

```text
custom-linux-packages/
├── specs/     # .spec files
├── sources/   # Source tarballs and patches
├── scripts/   # build-rpm.sh helpers
└── README.md
```

## Build flow

```bash
# Install build deps (RHEL example)
sudo dnf install rpm-build rpmdevtools

# Build from a spec file
rpmbuild -ba specs/my-package.spec
```

## Related repos

- [linux-bootstrap](https://github.com/Ayushtiwari46/linux-bootstrap) — host baseline setup
- [Custom_Packages](https://github.com/Ayushtiwari46/Custom_Packages) *(private)* — internal package work

## Status

Work in progress — add specs and build scripts as packages are created.
