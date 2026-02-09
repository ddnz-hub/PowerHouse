# Field‑Native AI — Research (Data Room)

This folder holds **research artefacts recontextualised into markdown** so they can be inspected, cited, diffed, and versioned without relying on PDFs.

These documents are **source material**, not canonical spine. Canonical documents live one level up:

- `Operating Companies/Field-Native AI/Constitution.md` (spine; authoritative)
- `Operating Companies/Field-Native AI/Investor Memorandum_v0.2.md` (projection; must not contradict)
- `Inverse/Pilot Playbook.md` (pilot posture; boundaries)
- `Operating Companies/Field-Native AI/Field-Native White Paper.md` (technical posture + edge‑case implications)

---

## Taxonomy

- **`Risk Research/`**: structural risks and mitigation postures (authority, capture, drift, thresholds, harm).
- **`Market Research/`**: market/competitive/regulatory/underwriting research (kept separate from spine to avoid narrative theatre).
- **Root (`research/`)**: general research artefacts that inform architecture, pilots, or epistemic posture.

---

## How to add a new paper (the “no drift” procedure)

1. **Place the source** (temporarily) in this folder as a PDF or other original format.
2. **Create a markdown recontextualisation** alongside it:
   - Keep the source filename in the **`Source:`** line.
   - Add a short **Constitutional context** section (orientation/stewardship/execution).
   - Add a short **Placement in the Field‑Native system** section (why it’s here; what it supports).
   - Then include a **reflowed rewrite** of the content for legibility (no new claims).
3. **Classify**:
   - If it’s primarily risk framing → move the `.md` into `Risk Research/`.
   - If it’s primarily market framing → move the `.md` into `Market Research/`.
4. **Delete the PDF** once the markdown version exists and is readable.
5. **Update** `Operating Companies/Field-Native AI/Data Room Index.md` if the artefact should be directly linked.

