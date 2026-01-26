# Access PoD — Volume 2 Artifact Pack (Version A)

Document ID: APOD-TR-002  
Status: Public Review Draft (Standards Exploration)

This repository hosts the **canonical Version A artifact pack** referenced by the Volume 2 Public Review Draft.

Scope: **Version A** — model-agnostic, execution-independent governance artifacts supporting the Volume 2 paper.

The original Version A publication is included in the Version A artifact pack ZIP as:  
APOD-TR-002_A-WEB-of-Sharing-Trust-Responsibility_Vol2_Version-A_Public-Review.pdf

This repository contains machine-readable artifacts supporting:

- **Simulation AI-Powered Policies (SAPP)**
- **Access Policy-on-Demand (PoD) runtime governance**
- **Compliance Star Certificate (CSC)** schema and scoring support files

These artifacts are provided for:

- standards exploration and technical review
- research and comparative analysis
- implementation study and interoperability discussion

They are **not a certification program** and do **not** constitute regulatory guidance or legal advice.

------------------------------------------------------------

Folder Structure

schemas/  
  JSON schemas used to validate certificates and catalogs.

catalogs/  
  Metric catalogs used by CSC scoring and telemetry mapping.

profiles/  
  Sector weighting profiles and gate thresholds.

examples/  
  Example certificates and sample artifacts for integration testing.

docs/  
  Supporting documentation, including README files for the following releases:  
  **v1b, v1c, v1d, v1.0-workshop, and workspace.**

_future_extensions/  
  Reserved for Version B (architecture-specific extensions, e.g., Q-Pathformer + UGCCMT).

------------------------------------------------------------

Included Artifacts (Version A)

- **CSC certificate schema** (csc-certificate.schema_v1a.json)
- **CSC metric catalog schema** (csc_metric_catalog_schema_v1a.json)
- **CSC metric catalog** (csc_metric_catalog_v1a.json)
- **CSC sector profiles** (csc_sector_profiles_v1a.json)
- **Example CSC certificate** (example_csc_certificate_v1a.json)
- **Access PoD JSON Instructions PDF** (docs/Access_PoD_JSON_Instructions_v1a.pdf)
- **Version A publication PDF**:  
  APOD-TR-002_A-WEB-of-Sharing-Trust-Responsibility_Vol2_Version-A_Public-Review.pdf
- **Pack manifest** (manifest_v1a_pack.json) — includes integrity hashes

------------------------------------------------------------

Integrity and Versioning

Releases include a **pack manifest file** (manifest_v1a_pack.json) that enumerates all normative artifacts and their associated **SHA-256 checksums**.

Integrity verification must be performed against the **artifact pack ZIP** and the hashes listed in the embedded manifest.

The **v1a release is anchored to a tagged commit**. Subsequent commits on the main branch are **non-normative** and are intended only for clarification, documentation improvements, or preparation for future revisions (e.g., v1b).

Normative scope for **Version A** is defined **exclusively** by the artifact pack and its manifest.

Do **not** change the meaning of an existing metric_id.  
If a change in semantics is required, deprecate the existing identifier and introduce a new metric_id.

Version A artifacts are intended to remain **stable for the duration of the public review cycle**.  
Version B and later revisions must extend functionality via the _future_extensions/ directory **without modifying Version A artifacts**.

------------------------------------------------------------

Source Archives and Verified Packs

**GitHub-generated source archives (ZIP / TAR.GZ) are provided for convenience only and are not normative.**  
They must **not** be relied upon for validation or integrity checking.

For verified distributions, reviewers should **use release assets that include a pack ZIP and published SHA-256 hashes** (e.g., access-pod-artifacts-v1a-pack.zip).

------------------------------------------------------------

Contact / Feedback

This pack supports a public review process.  
Feedback should focus on:

- clarity and interpretability
- interoperability
- alignment with standards-oriented governance

------------------------------------------------------------

License

These artifacts are released under the **MIT License** to support standards exploration, research review, and implementation study.

Use of these materials does **not** imply certification, endorsement, or regulatory approval.
