# klimagg-law

> Public, read-only repository for the text of the Klima Generations Act (KlimaGG)  
> Öffentlich einsehbares, schreibgeschütztes Repository für den Text des Klima-Generationen-Gesetzes.

---

## Purpose

This repository contains the **legal text** of the Klima Generations Act (KlimaGG)
and its development history:

- current working draft(s),
- older versions and milestones,
- selected explanatory material and background notes.

It is meant as a **transparent, versioned record** of the law’s evolution, not
as a collaborative editing space. External contributions are welcome as issues,
comments or forks, but write access to the main branch is restricted.

---

## Relationship to other repositories

- **`klimagg-tech`** – technical backbone and reference architecture for
  implementing the digital infrastructure required by KlimaGG.

- **`klimagg-web`** – website and frontend content; may display or reference
  specific versions of the law.

The **authoritative public presentation** of the law may live on a website
(e.g. `klimagg.de`). This repository is a **versioned backup and transparency
artifact**.

---

## Repository structure (suggested)

text
current/
  klimagg-entwurf.md   # canonical current version of the law (plain text / markdown)
history/
  YYYY-MM-DD-vX.Y.Z/
    klimagg-entwurf.md # snapshot of the law at that date / version
    notes.md           # optional notes on what changed and why
annex/
  stories/             # narrative examples, stories, non-normative material
  background/          # background papers, references, analyses
  
You can refine this structure over time, but keep:

 - a single clear "current" version, and
 - stable historical snapshots for reference, citation and comparison.

## Versioning and tags

At this stage, we do not accept direct pull requests into main by default,
to keep the legal development path coherent. For now, submit comments to klimagg.de, 
this repository is merely a public lookup. This may change later.

## Disclaimer

This repository:

 - may contain drafts, not legally enacted norms,
 - does not represent an official publication in any jurisdiction,
 - is provided for discussion, analysis and transparency.

For any legally binding version of a future climate law, the relevant official
gazette(s) of the respective jurisdiction will remain authoritative.
  
