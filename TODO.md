# TODO

Package development

[x] Review documentation
[x] remove inst/ directory
[x] review vignette
[x] 'Status' -> 'BiocStatus' in version_map()
[] update unit tests
[] BiocVersion should never be updated? (always two-digit number x.y?)

Adoption

## Package management
- BiocVersion to Bioconductor devel and relase, after release
- Test, including 'beta' for developer community
- Package to CRAN (immediately after our release)
  - supposed to work with all R-3.5?
- References to `biocLite` in other packages (AnnotationHub)
  - find more references/dependencies to biocLite/BiocInstaller
## Website changes
- Update landing pages
  - 'devel' pages spring release cycle, 'release' pages fall release cycle?
- Update developers/how-to/useDevel page
- Update docker images
- Update BBS; SPB
- Modify version bump script -- BiocVersion not even in release, odd in devel
  - propagating with wrong version would be a disaster!
- Deprecate BiocInstaller (after release)
  - BiocInstaller needs to be modified to support this release and
    next -- DCF, etc.
## Community updates
- Travis CI scripts
- Appveyor CI script
- Bioconductor docker containers

