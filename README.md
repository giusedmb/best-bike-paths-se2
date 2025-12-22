# Best Bike Paths (BBP)

## About this repository

This repository contains the **Requirement Analysis and Specification Document (RASD)** and the **Design Document (DD)**
for the project **“Best Bike Paths (BBP)”**, developed as part of the  
**Software Engineering II course at **Politecnico di Milano** during the **Academic Year 2025/2026**.

The project follows the official *Requirement Engineering and Design Project* specification provided by the course staff
and aims at applying rigorous software engineering methodologies to the analysis and design of a complex software system.

According to the course guidelines, this repository is used not only to deliver the final versions of the documents,
but also to track intermediate versions and the evolution of the project over time.

Pre-built PDF versions of the documents can be found in the `DeliveryFolder` directory in the root of the repository.

---

## Repository structure

The repository is organized as follows:

```
.
├── RASD/
│   ├── sources/          # LaTeX sources for the RASD
│   └── ...
├── DD/
│   ├── sources/          # LaTeX sources for the DD
│   └── ...
├── DeliveryFolder/
│   ├── RASDv1.pdf
│   ├── DDv1.pdf
│   └── ...
└── README.md
```

---

## Building the documents locally

Both documents are written in **LaTeX** and can be built locally using the `pdflatex` compiler.

### Build the RASD

```bash
cd RASD/sources
pdflatex main.tex
```

### Build the DD

```bash
cd DD/sources
pdflatex main.tex
```

---

## Collaborative writing and project history

The **RASD and DD were developed collaboratively on Overleaf** to support parallel editing, versioning,
and clear tracking of individual contributions, as allowed by the course rules.

The following links provide access to the full editing history and evolution of the documents:

- [RASD – Overleaf project]((link removed))  

- [DD – Overleaf project]((link removed))

Through these links, it is possible to inspect:
- the complete version history,
- individual contributions by each group member,
- the progressive refinement of requirements, models, and design decisions.

Final PDF releases are periodically committed to this GitHub repository to comply with the official
delivery guidelines.

---

## About the project

**Best Bike Paths (BBP)** is a software system designed to support cyclists in creating, publishing, and exploring
bike paths based on real usage data and community feedback.

The system allows registered users to:
- record personal biking trips,
- manually or automatically collect information about bike paths,
- report path conditions and obstacles (e.g., potholes),
- validate and publish collected data for the benefit of the community.

BBP integrates data from multiple users, considering freshness and confirmation frequency, to compute path scores and
provide optimized route suggestions between an origin and a destination.
Unregistered users can also browse available paths and visualize them on a map, ranked by quality and effectiveness.

The project focuses on the **requirements analysis** and **architectural and detailed design** of BBP, without
implementing the system itself.

---

## Authors

- **Giacomo**
- **Giuseppe**
- **Lorenzo**

---

## Course information

- **Course:** Software Engineering II  
- **University:** Politecnico di Milano  
- **Academic Year:** 2025/2026  

---

## Final grade

*(To be filled after project evaluation)*

