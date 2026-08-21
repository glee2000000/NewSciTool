---
title: Home
---

# SciToolKG Reference Catalog

This site collects canonical paper citations, repository/website links, and agent-framework or benchmark associations for the scientific software tools, databases, and APIs referenced by the [SciToolAgent](https://github.com/HICAI-ZJU/SciToolAgent) knowledge graph (Ding et al., *Nature Computational Science* 5, 962–972, 2025, DOI [10.1038/s43588-025-00849-y](https://doi.org/10.1038/s43588-025-00849-y)).

## Scope and confidence policy

Every entry on this site was checked against a source citation (DOI, arXiv ID, or vendor page). **Entries that could not be verified — no traceable paper, no resolvable repository, or a citation the source research flagged as unconfirmed — are excluded rather than guessed.** That means this catalog is intentionally incomplete: a tool missing from these pages either has no canonical citation to give, or hasn't been verified yet, not that it doesn't exist or isn't used. See each page's note for the specific exclusions.

Two source documents fed this catalog:
1. A canonical-reference sweep across ~195 tools (agent frameworks, benchmarks, and chemistry/materials/biology tools).
2. A separate pass anchoring each tool to its most-recent-usage paper (2025–2026) and its benchmark/agent-framework associations, carrying an explicit Verified / UNSURE / UNKNOWN confidence tag per row. Only rows marked **Verified** are reproduced here.

## Pages

- [Agent Frameworks](agent-frameworks.html) — LLM-driven agents that orchestrate scientific tools (ChemCrow, Biomni, CRISPR-GPT, ChatMOF, …)
- [Benchmarks](benchmarks.html) — evaluation suites for tool-using agents (ScienceAgentBench, ChemBench, MatTools, …)
- [Chemistry Tools](chemistry-tools.html)
- [Materials Tools](materials-tools.html)
- [Biology Tools](biology-tools.html)
- [Verified Recent-Usage & Benchmark Anchors](recent-usage.html) — 2025–2026 papers confirming each tool is still in active use, and its dominant benchmark/framework association

## Caveats worth carrying forward

- **A-Lab** (*Nature* 624, 86–91, 2023) has an Author Correction (*Nature* 650, E1, 2026, DOI [10.1038/s41586-025-09992-y](https://doi.org/10.1038/s41586-025-09992-y)) that revised its headline novelty claim from "41 novel compounds from 58 targets" to "36 compounds from a set of 57 targets."
- **AlphaFold3** (*Nature* 630, 493, 2024) has an Addendum (*Nature* 636, E4, 2024, DOI [10.1038/s41586-024-08416-7](https://doi.org/10.1038/s41586-024-08416-7)) releasing inference code that was withheld at initial publication.
- **Biomni** and **CRISPR-GPT** both migrated from a preprint (bioRxiv / arXiv) to a peer-reviewed journal venue in 2025–2026; both DOIs are given where this catalog cites them.
- Reported tool counts for **ChemCrow** vary across sources (13, 17, or 18 "expert-designed tools"); the peer-reviewed *Nature Machine Intelligence* version and EPFL's press materials state 18, which is the figure used here.

*Last built from source research dated 2026-08-21.*
