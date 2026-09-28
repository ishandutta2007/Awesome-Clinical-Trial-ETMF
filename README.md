# Awesome-Clinical-Trial-ETMF

# Top Clinical Trial eTMF Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Electronic Trial Master File, Regulatory Document Management, TMF Reference Model Compliance, Inspection Readiness & Clinical Content Governance*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Clinical Trial eTMF** (electronic Trial Master File). These systems manage the essential documents of a clinical trial, support the TMF Reference Model, enable inspection readiness, and provide controlled workflows for sponsors, CROs, and sites.

**Examples** include Veeva Vault eTMF, Medidata eTMF, MasterControl eTMF, Phlexglobal, Ennov eTMF, Florence eBinders, SureClinical, TransPerfect Trial Interactive, IQVIA eTMF, and Montrium (the category leaders).

**Open-source emphasis**: Fully validated, inspection-ready commercial eTMF platforms dominate regulated clinical research. Open-source options are limited and mostly emerging or complementary (document filing backbones, general DMS, or experimental TMF projects). This section is realistic about the commercial gap while highlighting relevant open efforts.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Veeva Vault eTMF](https://www.veeva.com/)**  
  Market-leading enterprise eTMF within the Veeva Vault clinical suite—strong compliance, workflows, AI-assisted classification, and deep integration with CTMS, quality, and regulatory modules.

- **[Medidata eTMF](https://www.medidata.com/)**  
  eTMF capabilities integrated with the Medidata clinical cloud for document management aligned with study execution and analytics.

- **[MasterControl eTMF](https://www.mastercontrol.com/)**  
  Quality and clinical document management platform offering eTMF functionality within a broader GxP compliance suite.

- **[Phlexglobal](https://www.phlexglobal.com/)**  
  Specialized eTMF and TMF services/platform focused on inspection readiness and TMF Reference Model alignment.

- **[Ennov eTMF](https://www.ennov.com/)**  
  Clinical and regulatory document management platform including eTMF capabilities for life sciences organizations.

- **[Florence eBinders / Florence eTMF](https://florencehc.com/)**  
  Site-centric and sponsor eTMF/eISF platform known for strong research site collaboration and document exchange.

- **[SureClinical](https://www.sureclinical.com/)**  
  Clinical trial document and eTMF-oriented solutions for regulated content management.

- **[TransPerfect Trial Interactive](https://www.trialinteractive.com/)**  
  Clinical content and eTMF platform supporting document management, collaboration, and trial processes.

- **[IQVIA eTMF](https://www.iqvia.com/)**  
  eTMF and clinical document management capabilities within IQVIA’s broader clinical technology and services portfolio.

- **[Montrium](https://www.montrium.com/)**  
  Cloud eTMF and clinical content management platform aimed at mid-size biotech and adaptive trial needs.

## Open-Source GitHub Projects
- **[ctms-core](https://github.com/tgerke/ctms-core)**  
  Emerging open-source sponsor/CRO-side regulatory-document backbone for clinical trials—CDISC TMF Reference Model filing, Part 11-oriented controls, and hash-chained audit trail (AGPL-3.0; verify maturity and validation status).

- **[edc-core related TMF filing](https://github.com/tgerke/edc-core)**  
  Open-source clinical EDC project that includes reference integration patterns for filing study artifacts into an eTMF-style structure.

- **[SureETMF / Clin.net open clinical document projects](https://clin.net/)**  
  Community and open-source oriented electronic Trial Master File content management efforts (check current availability and licensing).

- **[General open document management systems (DMS)](https://github.com/)**  
  Self-hosted DMS platforms (e.g., Mayan EDMS, Paperless-ngx, or similar) that can be adapted for controlled clinical document storage with strong caveats around validation.

- **[TMF Reference Model open resources](https://tmfrefmodel.com/)**  
  Industry reference model and community materials used by both commercial and any open TMF implementations.

- **[CDISC standards and open tooling](https://www.cdisc.org/)**  
  Open standards (including related exchange models) that underpin modern eTMF and clinical data exchange.

- **[Audit trail and compliance open libraries](https://github.com/)**  
  Components for immutable logging and electronic signature support that can be composed into custom document systems (not full eTMF products).

- **[Open clinical trial collaboration and site portals](https://github.com/)**  
  Experimental or academic projects for document exchange between sponsors and sites.

- **[Self-hosted content repositories with access control](https://github.com/)**  
  Open object storage + metadata approaches used when building internal controlled document systems.

- **[Documentation and regulatory open playbooks](https://github.com/)**  
  Guides on TMF Reference Model structure, inspection readiness, and the challenges of validating open-source systems for clinical use.

### Additional Strong Open-Source Options
- Exploring **ctms-core** and related AGPL clinical document backbones for research or non-validated internal pilots.
- Using open DMS tools only with full awareness that they are not drop-in replacements for validated commercial eTMF systems.
- Accepting that 21 CFR Part 11, inspection readiness, TMF Reference Model maturity, site connectivity, and vendor validation still drive sponsors and CROs to commercial platforms (Veeva Vault eTMF, Medidata, Florence, Montrium, IQVIA, etc.).
- Focusing open-source efforts on transparency, standards alignment, and reducing vendor lock-in for non-regulated or early research contexts.

**Frameworks for building custom systems**: Map documents to the TMF Reference Model → enforce versioning and audit trails → control access and electronic signatures → export for inspection. In practice, most regulated trials rely on commercial eTMF platforms. Open approaches require significant validation investment and are rarely used as primary systems of record for GCP trials.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- eTMF systems are regulated under GCP and related requirements (e.g., 21 CFR Part 11). Open-source software is generally not validated for use as a primary Trial Master File. Always follow regulatory guidance and quality systems. This list is not regulatory or clinical advice.

---
**Made for clinical operations, quality, and open-standards advocates in life sciences.**
Let's keep trial documentation inspection-ready, standards-aligned, and as transparent as practical.
