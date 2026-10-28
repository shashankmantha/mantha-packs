# Mantha Packs

Signed YARA rule-pack bundles for [Mantha Ray](https://github.com/shashankmantha/Mantha-Ray), built and published by [Mantha Hermit](https://github.com/shashankmantha/mantha-hermit).

Each release holds `mantha-packs-<version>.tar.gz` and its minisign signature `.minisig`. Mantha Ray verifies the signature against its bundled public key, refuses older versions, and validates and compiles every rule before using a bundle. Don't install these by hand unless you are testing; use `mantha-ray packs install`.

Rules keep their upstream licences, which are recorded per rule in each bundle's `pack.json`.

Release public key: `RWQye8LeZTN8upsy6xQpmnCHReBOsz0ngBBUSjZYaSzgvf9lcvf4YNQi`
