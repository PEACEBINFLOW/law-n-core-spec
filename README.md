# Law-N Core Spec 🟪

Canonical specifications for **Law-N** — the Network Renaissance layer for signal-native computing.

This repo is the **source of truth** for:

- Law-N core concepts and abstractions
- LSIP – Law-N Signal Identity Protocol
- FBRP – Frequency-Based Routing Protocol
- GLCS – G-Layer Compatibility Standard (1G → 6G+)
- How Law-N feeds **CLSI** (Cloud Layer Signal Interface)
- How **N-SQL** reads live network state
- How future **N-LLMs** reason over signal patterns instead of plain text

If the manifestos and blog posts are the *story*,  
**this repo is the spec.**

---

## 📂 Structure

```text
specs/
  00-overview/             # What Law-N is and why it exists
  01-signal-identity/      # LSIP — identity for signals
  02-routing-and-patterns/ # FBRP — frequency & pattern routing
  03-g-layer-compatibility/# GLCS — 1G–6G harmonics
  04-clsi-bridge/          # How CLSI consumes Law-N state
  05-nsql-mapping/         # Mapping Law-N → N-SQL
  99-future-work/          # Open questions and roadmap

diagrams/
  mermaid/                 # Source .mmd diagrams
  exports/                 # Rendered SVG/PNGs (for now .gitkeep)

examples/
  # Narrative & technical examples

tools/templates/
  # Spec & RFC templates
