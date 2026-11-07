# Mantha Packs

Signed YARA rule-pack bundles for [Mantha Ray](https://github.com/shashankmantha/Mantha-Ray), built and published by [Mantha Hermit](https://github.com/shashankmantha/mantha-hermit).

Each release holds `mantha-packs-<version>.tar.gz` and its minisign signature `.minisig`. Mantha Ray verifies the signature against its bundled public key, refuses older versions, and validates and compiles every rule before using a bundle. Don't install these by hand unless you are testing; use `mantha-ray packs update`.

Release public key: `RWQye8LeZTN8upsy6xQpmnCHReBOsz0ngBBUSjZYaSzgvf9lcvf4YNQi`

## Licences and attribution

The rules in these bundles were written by others and are redistributed under their own licences. Mantha Hermit's MIT licence covers Hermit's code only, not the rules.

- **Per rule:** every rule's licence and upstream repository are recorded in its pack's `pack.json`, and its author and reference stay in the rule's own metadata.
- **Per release:** the release notes list every upstream repository, how many of its rules are included, and its licence.
- **Rules without a known licence are never published.**

Rules are taken from [YARA Forge](https://github.com/YARAHQ/yara-forge), which collects them from their upstream repositories, prefixes their names and adds metadata. Hermit ships the rule text as YARA Forge publishes it.

### Malpedia

These bundles include rules from [Malpedia](https://malpedia.caad.fkie.fraunhofer.de/) by Fraunhofer FKIE, generated with YARA-Signator ([malpedia/signator-rules](https://github.com/malpedia/signator-rules)) and licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Those rules are marked `CC BY-SA 4.0` in `pack.json`. YARA Forge renamed them with a `MALPEDIA_` prefix and added metadata. Any redistribution of those rules, modified or not, must keep this attribution and the same licence.

## Corrections

If you are the author of a rule in these bundles and want its attribution or licence corrected, or want it removed, please open an issue.
