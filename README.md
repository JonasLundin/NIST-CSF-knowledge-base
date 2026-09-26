# NIST CSF Knowledge Base

An English-language [Open Knowledge Format (OKF)](https://github.com/GoogleCloudPlatform/knowledge-catalog/blob/main/okf/SPEC.md) bundle covering the NIST Cybersecurity Framework 2.0 (NIST CSWP 29): its six functions, 22 categories and 106 subcategories, organizational and community profiles, tiers, the informative references and implementation examples NIST publishes, and labelled crosswalks to the EU instruments covered by the sibling bundles.

The bundle will contain concise original summaries with provision-level citations to primary sources. It does not reproduce full legal instruments, rules, guidance documents, or standards.

Current release: **none yet** (`VERSION` 0.0.0)

> **Scaffold:** the manifest, section structure, validator and registers are in place. No concepts have been ingested yet; every section index describes what will go there.

> **General orientation only:** once populated, do not rely on this knowledge base for decisions that determine, demonstrate, or materially affect legal or regulatory compliance. Verify the current primary sources and obtain qualified professional advice before making control-selection, risk-acceptance, profile, audit, or other compliance-impacting decisions.

## Use With Meerkat

[Meerkat](https://github.com/zegit-zoo/meerkat) can serve the bundle as CLI, MCP, or HTTP without conversion:

```sh
mk --kb-dir . search "asset inventory"
mk --kb-dir . show framework/subcategories/id-am-01
mk --kb-dir . list --category outcome
mk --kb-dir . mcp serve
mk --kb-dir . http serve --port 4004
```

Run these commands from the repository root. The knowledge bundle itself is under `wiki/`; Meerkat's `--kb-dir` reads that content-repository layout. The paths above are the planned concept IDs and resolve once ingestion has reached them.

The Markdown remains usable without Meerkat or any other tool.

## Coverage

The intended corpus includes:

- the 6 functions, 22 categories and 106 subcategories of CSF 2.0;
- Organizational and Community Profiles and the four tiers;
- NIST's informative references and implementation examples, summarised and linked;
- labelled crosswalks to the CRA, NIS2, ISO/IEC 27001 identifiers and IEC 62443 identifiers;
- Quick Start Guides, CPRT and OLIR;
- the framework's timeline and glossary.

Coverage is measured in `coverage.yaml`. Each gate names a glob over `wiki/`, the expected number of concepts where the corpus is finite, and the count actually present. A missing official source is recorded as a research gap rather than filled by inference.

## Structure

`kb.yaml` declares the bundle's slug, extension key (`x-nist-csf`), categories and sections. Every section has an `index.md` describing what belongs there.

| Section | Contents |
|---|---|
| [`framework/`](wiki/framework/index.md) | The CSF Core: one page per function, category and subcategory, with the identifier used verbatim and the gaps in numbering preserved. |
| [`profiles/`](wiki/profiles/index.md) | How organisations use the Core. |
| [`informative-references/`](wiki/informative-references/index.md) | NIST's OLIR mappings from subcategories to SP 800-53 Rev. 5, SP 800-221A, CIS Controls, ISO/IEC 27001 clause identifiers, CSF 1.1 and others, with the NIST IR 8477 relationship type recorded. |
| [`crosswalks/`](wiki/crosswalks/index.md) | This bundle's own mappings from subcategories to EU instruments, labelled inferred until an official mapping exists, using NIST IR 8477 relationship styles. |
| [`guidance/`](wiki/guidance/index.md) | NIST resources around the framework. |
| [`timeline/`](wiki/timeline/index.md) | Executive Order 13636, CSF 1.0, 1.1 and 2.0 publication, informative-reference updates, Quick Start Guide releases. |
| [`glossary/`](wiki/glossary/index.md) | Terms as defined in CSWP 29 and NIST IR 8477. |

## Source And Publication Policy

- Binding claims cite NIST's official publications and datasets (CSWP 29, the CPRT and OLIR catalogues).
- Official guidance is labelled non-binding.
- A standard provides presumption of conformity only when its reference is cited in the OJEU for the requirements concerned.
- Publicly accessible drafts are linked, not copied.
- Subcategory identifiers are used verbatim, including the deliberate gaps in numbering; tooling that renumbers is wrong.
- ISO, IEC and other paywalled standards appear only as clause or control identifiers with a link to the publisher.
- Crosswalks authored here are labelled `inferred` until NIST or the EU publishes an official mapping.
- Agent-generated content stays `status: draft` until a human verifies it against the cited source.
- Superseded material is retained and marked rather than silently deleted.

This repository is not legal advice, is not a conformity assessment, does not certify any product or organisation, and must not be used as the basis for compliance-impacting decisions.

## Validate

```sh
python3 -m pip install -r requirements-dev.txt
python3 -m unittest tools/test_validate.py
python3 tools/validate.py wiki
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Corrections with exact primary-source citations are welcome. Do not submit copied standards text, private compliance evidence, or confidential information.

## Related Knowledge Bases

- [CRA-knowledge-base](https://github.com/JonasLundin/CRA-knowledge-base): Regulation (EU) 2024/2847, the Cyber Resilience Act
- [NIS2-knowledge-base](https://github.com/JonasLundin/NIS2-knowledge-base): Directive (EU) 2022/2555 and its national transpositions
- [CVD-knowledge-base](https://github.com/JonasLundin/CVD-knowledge-base): coordinated vulnerability disclosure, the CVE Program, CSAF, VEX and scoring
- [AI-Act-knowledge-base](https://github.com/JonasLundin/AI-Act-knowledge-base): Regulation (EU) 2024/1689 as amended
- [Conformity-Assessment-knowledge-base](https://github.com/JonasLundin/Conformity-Assessment-knowledge-base): the New Legislative Framework, modules, accreditation and notified bodies
- [Software-Supply-Chain-knowledge-base](https://github.com/JonasLundin/Software-Supply-Chain-knowledge-base): SBOM formats, attestation, provenance and VEX
- [knowledge-base-template](https://github.com/JonasLundin/knowledge-base-template): the shared template every bundle in the series is built from

## Licence

Original summaries, structure, and metadata are licensed under [CC BY 4.0](LICENSE). Source documents, rules, specifications and standards retain their own terms; see [NOTICE](NOTICE).

This project is independent and is not affiliated with or endorsed by the National Institute of Standards and Technology, the United States Department of Commerce, the European Commission, ENISA, ISO, IEC, Google Cloud, or Meerkat. Repository: https://github.com/JonasLundin/NIST-CSF-knowledge-base
