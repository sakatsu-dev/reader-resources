# Sakatsu Reader resources

Versioned resource snapshots for Sakatsu Reader. Downloaded bytes remain fixed for each
release, and the application verifies their exact size and SHA-256 before use.

## KANJIDIC2

The snapshot is an unmodified copy published by the Electronic Dictionary Research and
Development Group (EDRDG) on 2026-10-18, distributed under CC BY-SA 4.0.

- [KANJIDIC2 project](https://www.edrdg.org/wiki/index.php/KANJIDIC_Project)
- [EDRDG licence](https://www.edrdg.org/edrdg/licence.html)
- [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
- [Snapshot](https://github.com/sakatsu-dev/reader-resources/releases/download/kanjidic2-2026-10-18/kanjidic2-20261018.xml.gz)
- [Checksums](https://github.com/sakatsu-dev/reader-resources/releases/download/kanjidic2-2026-10-18/SHA256SUMS)
- [Attribution](https://github.com/sakatsu-dev/reader-resources/releases/download/kanjidic2-2026-10-18/ATTRIBUTION.md)

Size: 1,488,573 bytes. SHA-256:

```text
6182a700e08a8f6a6646529b77f84f0d963ed33cd5c7516ff19e4ee642345446
```

## Release policy

Binary snapshots belong in release assets, not Git history. Enable immutable releases before
publishing. Prepare a draft, verify every asset, then publish it. Published assets and tags must
remain unchanged. New upstream data receives a new dated release and a separately reviewed
application catalog update. Keep previous releases available for existing installations.

The publisher's original download URL is updated in place; use the dated asset above for a
reproducible installation. Every redistributed resource retains its original attribution and
licence. This repository does not change those terms.
