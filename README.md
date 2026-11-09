# PULSEmech Q3 runtime inputs

<!-- SPDX-License-Identifier: Apache-2.0 -->

Preservation and planned delivery of the exact runtime input selected for
PULSEmech Q3, together with its source archives and license notices.

## Setup status

Documentation prepared on 2026-11-09 for
`HKati/pulsemech-q3-runtime-inputs`.

- The target repository was read at
  `a69c525ec676ad05135d47e6a25cfc54b84f5574`, with only its initial README.
- No published release was returned by the repository's release listing.
- Release immutability was shown enabled in the owner's setup screenshot.
- The runtime transport in the main project remains unconfigured. Its existing
  `github-repository-parts-v0` route has no selected commit or prefix; a Releases
  asset source is not implemented by this documentation.
- Actual runner retrieval is unverified. No preflight, capture or measurement
  is authorized or completed by creating this repository or adding these files.

These observations describe setup, not a permanent claim about later releases.

## Where the payload belongs

Small documentation and identity records belong in this repository's file tree.
The runtime fragments, source archives and notice companion are intended as
**GitHub Releases attachments**, outside Git history.

Proposed release tag: `q2-runtime-37148637546-1-v1`.

Proposed title: `Q3 runtime input — Q2 preparation 37148637546/1`.

Prepare the complete release as a draft. Verify its exact attachment set before
publishing it with release immutability enabled. Creating the repository and
preparing a draft do not constitute approval to publish the runtime contents.
No public asset URL, release ID or asset ID is assigned by this README.

## Exact original runtime

| Field | Recorded value |
| --- | --- |
| Filename | `q2-runtime-preparation-37148637546-1.zip` |
| Bytes | `508460811` |
| SHA-256 | `b3a2b4db54816dd6f40171c221947d942ca63f3e9883f76de8455ad66037f4b9` |
| Original run / attempt | `37148637546 / 1` |
| Original Actions artifact | `11282419957` |
| Original source commit | `77fc5d51896568db50a2a87f650711a65db8fe8c` |

The selected delivery uses the existing twenty fragments, without repacking
the original archive. The unavailable original Actions artifact is an origin
identifier, not the download endpoint for this proposed delivery.

## Planned release attachments

| Asset | Count | Bytes |
| --- | ---: | ---: |
| `q2-runtime-preparation-37148637546-1.zip.001` through `.020` | 20 | 508460811 total |
| `Q3_RUNTIME_RESZEK.json` | 1 | 7014 |
| `Q3_RUNTIME_SOURCE_NOTICE_COMPANION_v1.zip` | 1 | 30470832 |
| `gcc-8.5.0-26.el8_10.alma.1.src.rpm` | 1 | 65714006 |
| `gcc-libraries-8.3.1-2.1.1.el7.src.rpm` | 1 | 137336608 |
| `gcc-4.8.5-44.el7.src.rpm` | 1 | 79314655 |

The planned set is **25 uploaded assets, totaling 821303926 bytes**.
The complete original runtime ZIP is reconstructed from the twenty fragments;
it is not an additional attachment in this plan.

The original split manifest records each part's filename, order, size and hash.
Its exact copy is retained inside the companion at
`baseline/Q3_RUNTIME_RESZEK.json`.

| Non-fragment asset | SHA-256 |
| --- | --- |
| `Q3_RUNTIME_RESZEK.json` | `67eff809f8cf000f82b8365f1fc535ca82ffea167e2834488166915454c87f37` |
| `Q3_RUNTIME_SOURCE_NOTICE_COMPANION_v1.zip` | `7a72828947d276060b28b3668ad6a569771aefe837e8c50f94833c6f4f2ff54c` |
| `gcc-8.5.0-26.el8_10.alma.1.src.rpm` | `0911864c260a75ae030f3144616e7e5e1359e04ce1c9730ab83906486e3bc79f` |
| `gcc-libraries-8.3.1-2.1.1.el7.src.rpm` | `cf2a1d2c2e5a56eb2e495c2638e64769b73db07555e1f7ce34cbd9feff6891f5` |
| `gcc-4.8.5-44.el7.src.rpm` | `642c4085f6af9565e39583e54a9d7a5d9e6b93dd8c8e9474aec8a892d6c7aa36` |

The companion and three complete source RPMs are distinct files. The full
source RPMs are not included inside the companion ZIP.

## Integrity and use

Any future runner integration must identify the exact repository, release,
tag commit and assets, then check the recorded sizes and SHA-256 values.
A moving `latest` release reference is not a sufficient source binding.

Check every fragment before joining them in the manifest order. The resulting
archive must match the original byte count and whole-archive hash above, then
pass the existing independent archive verification.

A visible asset list or successful documentation commit does not prove runner
retrieval. The Releases retrieval adapter and its evidence bindings still need
implementation and offline verification, followed by separately authorized
retrieval from the actual runner.

## Licensing

The **project-authored text of this README** is provided under the
[Apache License, Version 2.0](LICENSE). The accompanying [NOTICE](NOTICE)
preserves the main project's attribution. These two files are exact copies
from the main project at the source revision linked below.

This scope does not assign a single license to the release attachments.
Runtime components, model-related material, source packages, historical project
files and retained notices keep their applicable original terms and
attributions. The Apache license for this README does not replace, remove
or expand those terms.

The prepared companion supplies the retained license and notice texts and
their component bindings. Its notice files, source material and unchanged
historical records retain their own applicable terms. The original runtime
bytes and accompanying source archives must remain tied to that material.

The recorded preparation covers the explicitly inspected component catalog.
It is not a claim of a complete native SBOM, a source-to-binary rebuild,
cryptographic verification of RPM public-key signatures, or blanket
publication clearance. Separate CPython/bootstrap obligations remain outside
the selected runtime-archive inspection.

The owner's publication decision must cover the exact 78 inventoried runtime
ZIP members and the exact companion/source delivery set. Documentation
licensing and publication of those attachments are separate decisions.

## Source records

This README is a new adaptation of the main project's source-and-notice
preparation documentation for this separate delivery repository. It was
prepared on 2026-11-09; the historical records it cites are not rewritten.

Inspected main-project revision: `7e8d24e19ebbe8de32a2b00e1e2b22b5aa8b10bf`.

- [Source and notice preparation README](https://github.com/HKati/pulse-release-gates-0.1/blob/7e8d24e19ebbe8de32a2b00e1e2b22b5aa8b10bf/docs/compute/q3_runtime_source_notice_v1/README.md)
- [Exact evidence and source archive index](https://github.com/HKati/pulse-release-gates-0.1/blob/7e8d24e19ebbe8de32a2b00e1e2b22b5aa8b10bf/docs/compute/q3_runtime_source_notice_v1/EVIDENCE_INDEX.json)
- [Retained preparation result](https://github.com/HKati/pulse-release-gates-0.1/blob/7e8d24e19ebbe8de32a2b00e1e2b22b5aa8b10bf/docs/compute/q3_runtime_source_notice_v1/RESULT.json)
- [Original project license](https://github.com/HKati/pulse-release-gates-0.1/blob/7e8d24e19ebbe8de32a2b00e1e2b22b5aa8b10bf/LICENSE)
- [Original project attribution](https://github.com/HKati/pulse-release-gates-0.1/blob/7e8d24e19ebbe8de32a2b00e1e2b22b5aa8b10bf/NOTICE)

## Measurement boundary

Git LFS, paid storage and new spending are outside this delivery plan.
Owner-local downloads are reported; owner-machine hashes are not verified.

A fresh zero-generation preflight requires separate authorization after
delivery is implemented and verified. Internal/external checks and a separate
owner capture decision still precede at most 204 one-shot responses,
response-bound Q1 inputs, Q3 calculation and independent recomputation.

No automatic reruns, retries, top-ups or silent runtime substitutions are
authorized. Local custody does not authorize local model execution or access
to the owner's computer.

`runtime_transport_ready=false`; `actual_runner_retrieval_verified=false`;
`label_correctness=not_verified`; `authority_effect=none`.

[Main-project issue #2879](https://github.com/HKati/pulse-release-gates-0.1/issues/2879)
remains open.
