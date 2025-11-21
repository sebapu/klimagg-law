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

```text
current/
  klimagg-entwurf.md   # canonical current version of the law (plain text / markdown)
history/
  YYYY-MM-DD-vX.Y.Z/
    klimagg-entwurf.md # snapshot of the law at that date / version
    notes.md           # optional notes on what changed and why
annex/
  stories/             # narrative examples, stories, non-normative material
  background/          # background papers, references, analyses
