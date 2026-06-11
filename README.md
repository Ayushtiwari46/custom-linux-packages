# custom-linux-packages

Custom RPM packages, spec files, and build scripts for RHEL / Rocky / Alma.

## Suggested layout

```text
custom-linux-packages/
├── specs/             # .spec files
├── sources/           # Source tarballs and patches
├── scripts/           # build-rpm.sh helpers
└── README.md
```

## Build flow (example)

```bash
rpmbuild -ba specs/my-package.spec
```
