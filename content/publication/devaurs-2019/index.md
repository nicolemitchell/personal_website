---
title: "Using parallelized incremental meta-docking can solve the conformational sampling issue when docking large ligands to proteins"
date: 2019-09-01
publishDate: 2019-11-23T20:14:27.039959Z
authors: ["Didier Devaurs", "Dinler A Antunes", "Sarah Hall-Swan", "Nicole Mitchell", "Mark Moll", "Gregory Lizée", "Lydia E Kavraki"]
publication_types: ["2"]
abstract: "Background: Docking large ligands, and especially peptides, to protein receptors is still considered a challenge in computational structural biology. Besides the issue of accurately scoring the binding modes of a protein-ligand complex produced by a molecular docking tool, the conformational sampling of a large ligand is also often considered a challenge because of its underlying combinatorial complexity. In this study, we evaluate the impact of using parallelized and incremental paradigms on the accuracy and performance of conformational sampling when docking large ligands. We use ﬁve datasets of protein-ligand complexes involving ligands that could not be accurately docked by classical protein-ligand docking tools in previous similar studies.  Results: Our computational evaluation shows that simply increasing the amount of conformational sampling performed by a protein-ligand docking tool, such as Vina, by running it for longer is rarely beneﬁcial. Instead, it is more eﬃcient and advantageous to run several short instances of this docking tool in parallel and group their results together, in a straightforward parallelized docking protocol. Even greater accuracy and eﬃciency are achieved by our parallelized incremental meta-docking tool, DINC, showing the additional beneﬁts of its incremental paradigm. Using DINC, we could accurately reproduce the vast majority of the protein-ligand complexes we considered.  Conclusions: Our study suggests that, even when trying to dock large ligands to proteins, the conformational sampling of the ligand should no longer be considered an issue, as simple docking protocols using existing tools can solve it. Therefore, scoring should currently be regarded as the biggest unmet challenge in molecular docking.  Keywords: molecular docking; protein-ligand docking; protein-peptide docking; conformational sampling; scoring; parallelism; incremental protocol"
featured: false
publication: "*BMC Molecular and Cell Biology*"
tags: ["proteins and drugs"]
doi: "10.1186/s12860-019-0218-z"
---

