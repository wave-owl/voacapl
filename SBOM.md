# Source SBOM

**Initial source snapshot, not a release report.** Source commit `c12a98b348c39f36f2659b8b3aa97b86284c8a1d` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/voacapl `c12a98b348c39f36f2659b8b3aa97b86284c8a1d`

- sbom:role: source-root
- sbom:git-commit: c12a98b348c39f36f2659b8b3aa97b86284c8a1d
- sbom:git-tree: 4b43adf1499ece4938c66ce766e22184a209a231
- sbom:source-repository: https://github.com/wave-owl/voacapl
- sbom:release-tags: []
- sbom:license-evidence: [{"path": "COPYING", "sha256": "befc5397f28ba16e63e12858bc474c6cfbf287dec1faaf8a5c66a79ffab9890e"}, {"path": "LICENSE", "sha256": "91cafdb49e4766d79aa3b5c8bbfe5d2ddc287e96e563f11eae779e72354a549c"}]
- sbom:license-resolution: unresolved; manual review required

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/voacapl | c12a98b348c39f36f2659b8b3aa97b86284c8a1d | source-root | unresolved; manual review required |
| Conditional source requirements declared by configure.ac | unresolved | conditional-build-runtime-requirement | unresolved |
| Fortran compiler and Autotools; math runtime | unresolved | conditional-build-runtime-requirement | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
