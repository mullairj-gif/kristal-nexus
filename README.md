# Kristal Nexus — Cross-Domain Research Collision Engine

An experimental research intelligence tool that systematically discovers where two research fields collide. Enter two domains — Nexus finds the gaps, overlaps, bridge papers, and cross-domain hypotheses across the intersection.

## What It Does

Nexus takes two research domains as input and scans major academic databases to identify:

- **Shared Concepts** — Vocabulary and topics that appear in both fields
- **Bridge Papers** — Published research that references both domains
- **Bridge Researchers** — Scientists who publish across both fields
- **Collision Zones** — Five types of cross-domain intersection points
- **Research Gaps** — Per-domain gaps detected from literature analysis
- **Nexus Score™** — A composite metric quantifying collision potential (concept overlap, citation deficit, researcher bridges, collision density)
- **AI Hypotheses** — Optional AI-generated cross-domain research questions (requires Claude API key)

## Data Sources

- [OpenAlex](https://openalex.org/) — Open scholarly metadata
- [arXiv](https://arxiv.org/) — Preprint server
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/) — Biomedical literature via NCBI E-utilities

All data retrieval runs client-side. No backend server required.

## How to Use

1. Open `kristal_nexus_v2.html` in any modern browser
2. Enter two research domains (e.g., "gut microbiome" and "machine learning")
3. Click **⚡ COLLIDE**
4. Explore results across tabs: Collisions, Concepts, Bridge Papers, Bridge Researchers, Hypotheses, Domain Gaps

Or click **🎲 Surprise Me** for a random cross-domain pairing.

### Optional: AI Hypotheses

To enable AI-generated collision hypotheses, expand the API Keys panel and enter a Claude API key. All other features work without any keys.

## Features

- **Zero dependencies** — Single HTML file, runs in any browser
- **No account required** — No signup, no login, no data collection
- **Export** — CSV export of all papers, collisions, and shared concepts
- **Copy Citation** — One-click citation copy for bridge papers
- **Collision Report** — Markdown report with full analysis, downloadable
- **Score Transparency** — Click the Nexus Score to see component breakdown
- **Deterministic** — Same inputs produce same scores (no randomization)

## Collision Types

Nexus detects five types of cross-domain collisions:

| Type | Description |
|------|-------------|
| Concept Bridge | Shared vocabulary across fields |
| Methodological Transfer | Techniques from one field applicable to another |
| Shared Problem | Both fields addressing the same underlying challenge |
| Tool/Resource Bridge | Shared datasets, instruments, or infrastructure |
| Theoretical Bridge | Common theoretical frameworks |

## Example Collision Pairs

- Cancer immunotherapy × Space radiation biology
- Gut microbiome × Machine learning
- Quantum computing × Drug discovery
- Game theory × Antibiotic resistance
- Origami mathematics × Cardiac stents
- Ocean acoustics × Neuroscience
- Mycology × Architecture
- Behavioral economics × Vaccine hesitancy

## Background

Cross-domain research produces disproportionately high-impact science. Papers combining conventional and atypical knowledge pairings achieve the highest citation impact (Uzzi et al., *Science*, 2013). Yet researchers lack systematic tools for discovering where their field intersects with distant domains.

Nexus was built to make cross-domain discovery accessible — no paywalls, no institutional access required, no specialized training needed.

## Related Tools

- **[Kristal Pathfinder](https://github.com/mullairjeudi/kristal-pathfinder)** — Single-domain research gap scanner (DOI: [10.5281/zenodo.18497788](https://doi.org/10.5281/zenodo.18497788))
- **[PrepEnfermería](https://prepenfermeria.com)** — Multilingual nursing certification platform

## Built By

**Mullair Jeudi, MD** — Medical graduate completing clinical internship in Puerto Rico. Built with AI collaboration tools and no formal CS background.

**Kristal Labs** — Named after my niece Kristal.

## License

MIT License — free to use, modify, and distribute.

## Citation

If Nexus contributes to your research, you can cite it:

```
Jeudi, M. (2026). Kristal Nexus: Cross-Domain Research Collision Engine. 
Zenodo. https://doi.org/[DOI_HERE]
```

## Acknowledgments

Inspired by research on atypical combinations and scientific impact, the science of science, and the principle that cross-domain collisions are where breakthroughs happen.
