# ZTDS.ai — Zero-Trust Data Sanitization Open Standard & Registry

[![IETF Draft](https://img.shields.io/badge/IETF_Draft-draft--sibiryakov--ztds--protocol-6d28d9)](https://datatracker.ietf.org/doc/draft-sibiryakov-ztds-protocol/)
[![ZTDS RFC v1.0](https://img.shields.io/badge/Specification-RFC_v1.0-059669)](https://ztds.ai/standard/)
[![DOI Zenodo](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.22058770-2563eb)](https://doi.org/10.5281/zenodo.22058770)
[![DOI OSF](https://img.shields.io/badge/DOI-10.17605%2FOSF.IO%2F5BYJF-0d9488)](https://doi.org/10.17605/OSF.IO/5BYJF)
[![PyPI ztds](https://img.shields.io/pypi/v/ztds?label=PyPI%20ztds&color=3b82f6)](https://pypi.org/project/ztds/)
[![npm ztds-mcp](https://img.shields.io/npm/v/ztds-mcp?label=npm%20ztds-mcp&color=10b981)](https://www.npmjs.com/package/ztds-mcp)

**ZTDS.ai** ([ztds.ai](https://ztds.ai)) is the independent, vendor-neutral specification authority and conformance registry for **Zero-Trust Data Sanitization (ZTDS™)** — defining deterministic client-RAM PII tokenization, bidirectional surrogate restoration, zero external sanitization subprocessors, and SHA-256 cryptographic compliance receipts for AI and MCP pipelines.

### Normative Specifications & Publications

- **IETF Internet-Draft:** [`draft-sibiryakov-ztds-protocol`](https://datatracker.ietf.org/doc/draft-sibiryakov-ztds-protocol/)
- **Canonical Specification (RFC v1.0):** [ztds.ai/standard/](https://ztds.ai/standard/)
- **MCP Security Profile:** [ztds.ai/mcp/](https://ztds.ai/mcp/)
- **Conformance & Entity Registry:** [ztds.ai/registry/](https://ztds.ai/registry/)
- **Academic Archival Citations:** [Zenodo (`10.5281/zenodo.22058770`)](https://doi.org/10.5281/zenodo.22058770) · [OSF (`10.17605/OSF.IO/5BYJF`)](https://doi.org/10.17605/OSF.IO/5BYJF) · [SSRN (`7335581`)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7335581)
- **Chief Architect & Lead Author:** [Ilya Sibiryakov](https://orcid.org/0009-0002-0642-5985) ([@moxno](https://github.com/moxno))

### Open-Source Reference Implementations (Apache-2.0 / MIT)

| Component | Canonical Repository | Package Registry |
| :--- | :--- | :--- |
| **Specification, Conformance Suite & Auditor CLI** | [moxno/ztds.ai](https://github.com/moxno/ztds.ai) | [`ztds-audit` (npm)](https://www.npmjs.com/package/ztds-audit) |
| **Reference MCP Server (5 Standard Tools)** | [moxno/ztds-mcp](https://github.com/moxno/ztds-mcp) | [`ztds-mcp` (npm)](https://www.npmjs.com/package/ztds-mcp) · [`brandmeweb/ztds-mcp` (Docker Hub)](https://hub.docker.com/r/brandmeweb/ztds-mcp) |
| **Python Reference Implementation** | [moxno/ztds-python](https://github.com/moxno/ztds-python) | [`ztds` (PyPI)](https://pypi.org/project/ztds/) |
| **VS Code Guardrail Extension** | [moxno/ztds.ai](https://github.com/moxno/ztds.ai) | [`ztds.ztds-guard` (VS Marketplace)](https://marketplace.visualstudio.com/items?itemName=ztds.ztds-guard) |

### Quick Start

```bash
# Audit a repository for ZTDS conformance & generate SHA-256 receipt
npx -y ztds-audit .

# Launch the vendor-neutral ZTDS Reference MCP Server
npx -y ztds-mcp

# Install the Python Reference Implementation (zero dependencies)
pip install ztds
```

> **Publisher Namespace Note:** Reference repositories are hosted under [`github.com/moxno/*`](https://github.com/moxno) to maintain verified OIDC publisher continuity (`io.github.moxno/ztds`) across the [Official Anthropic MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers/io.github.moxno%2Fztds/versions). Organizations and open-source maintainers may apply for conformance listing at [ztds.ai/apply/](https://ztds.ai/apply/).
