+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 50  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

[[experience]]
  title = "Research Scientist"
  company = "Google Research"
  company_url = "research.google.com"
  location = "San Francisco, CA"
  date_start = "2022-06-01"
  date_end = ""
  description = """
  **Longitudinal Risks**

  * Wrote a position piece advocating for longitudinal studies of human-AI interactions to better understand and mitigate risks that develop over time. Submitted [paper](https://arxiv.org/abs/2608.02491) to EMNLP 2026.


  **Privacy Auditing and Data Provenance**

  * Improved privacy auditing methods for LLMs to better detect data leakage and inform practical understanding of model risk.
  * Proposed a simple and effective canary design that leverages high-temperature sampling to yield highly sensitive synthetic probes for detecting privacy leakage.
  * Presented and evaluated an improved approach for auditing synthetically generated data.
  * Investigated memorization properties of language models using privacy-auditing techniques.
  * Carried out implementation and experimentation.
  * Submitted [paper](https://arxiv.org/abs/2606.10481) to EMNLP 2026.


  **Models that Forget**

  * Led a research effort leveraging modularity and unlearning to control data influence and address privacy and policy challenges. 1 of 4 proposals of bold new research directions selected from 56 submissions across the organization.
  * Built team of collaborators, drew connections across orgs, charted out research roadmap, secured buy-in from leadership.
  * Proposed data compartmentalization as a strategy for AI Governance, presenting a taxonomy mapping governance needs to technical requirements and relevant strategies. Presented [paper](https://blog.genlaw.org/pdfs/genlaw_icml2024/94.pdf) at GenLaw@ICML 2024.
  * Documented internal use cases for unlearning and scoped out partnerships through discussions with product teams.
  * Hosted 3 student researchers, investigating approximate unlearning for robustness ([paper](https://arxiv.org/abs/2505.17730)) and certifiable unlearning for privacy ([paper](https://openreview.net/pdf?id=dfh0RrNbC8)).
  * Contributed to an internal effort on modular continual learning.


  **User-level Differential Privacy**

  * Investigated how to best scale user-level DP training to LLMs under fixed compute budgets.
  * Helped define and execute on experiments for the [paper](https://arxiv.org/pdf/2407.07737).


  **Function-Space Aggregation of Models in Federated Learning**

  * Led a student researcher project to explore new algorithms for merging models in federated learning, drawing upon ideas in meta-learning.
  * Scoped and drafted a proposal; received funding.
  * Implemented federated model training and evaluation infrastructure to enable running large-scale experiments on various algorithms.
  * [Paper](https://arxiv.org/abs/2311.10291) accepted to TMLR 2024.


  **Building a Scalable Dataset Pipeline for Group-Structured Learning**

  * Developed infrastructure to support scaling up federated learning simulation to datasets and models orders of magnitudes larger than previously used.
  * Released an open source library, [Dataset Grouper](https://github.com/google-research/dataset_grouper), for partitioning existing flat datasets into group-structured datasets.
  * [Paper](https://arxiv.org/abs/2307.09619) accepted to NeurIPS Benchmarks & Datasets 2023.


  **Federated Learning AI Explorable**

  * Published an [interactive blog post](https://pair.withgoogle.com/explorables/federated-learning/) on how federated learning. Through interactive visualizations the piece allows readers to wrestle with data privacy concerns, learning how FL aims to mitigate them while introducing trade-offs.

  """

[[experience]]
  title = "AI Residency"
  company = "Google Research"
  company_url = "research.google.com"
  location = "San Francisco, CA"
  date_start = "2021-02-01"
  date_end = "2022-06-01"
  description = """

**Compression for Federated Learning**  

* Designed a custom compression method for client updates in federated learning to reduce the communication cost from 32 bits per model parameter to 0.1 bits without degrading accuracy on several benchmarks.
*	Implemented [compression-based aggregation methods](https://github.com/google-research/federated/tree/1b31b84/compressed_communication) for federated learning in TensorFlow Federated. This involved: custom TF ops hosted in [TensorFlow Compression](https://github.com/tensorflow/compression), TensorFlow Federated logic, and robust integration tests for system compatibility.
*	Presented this work to internal and external audiences. Selected to give an oral presentation at the Google Research Conference. [Paper](https://arxiv.org/abs/2201.02664) accepted at ICLR 2022 TinyPapers.
*	Integrated custom compression method into Google’s federated learning production system.

  """
[[experience]]
  title = "Science Policy"
  company = "Baker Institute for Public Policy, Rice University"
  company_url = "https://www.bakerinstitute.org/research/apply-developing-civic-scientist-leaders/"
  location = "Houston, TX"
  date_start = "2020-01-01"
  date_end = "2020-08-30"
  description = """

**Developing Civic Scientist Leaders Program**  

* One of ten graduate students selected to participate in a weekly seminar to learn about the federal policymaking process and develop critical leadership skills to advance science as a public good
* Published an [op-ed](http://blog.bakerinstitute.org/2020/04/16/sears-once-your-ordinary-department-store-now-a-vehicle-for-tech-sector-gentrification-2/) on a public policy issue; [created one-pagers](https://nicolemitchell.github.io/files/HoustonResearchOnePager.png) advocating for funding basic scientific research to use in our upcoming congressional visits in Washington, D.C.

  """

[[experience]]
  title = "Graduate Research"
  company = "Kavraki Computational Robotics, AI and Biomedicine Lab, Rice University"
  company_url = "kavrakilab.org"
  location = "Houston, TX"
  date_start = "2019-01-01"
  date_end = ""
  description = """
**Drug Metabolism Prediction Using Graph-based Learning**

* Built a deep graph convolutional network (GCN) using Pytorch to predict drug metabolism
* Proposed the use molecular representations learned through GCNs to identify metabolically labile atoms. Compared to traditional feature extraction methods.
* Presented poster at the Rice Data Science Conference, Oct 2019, and the 29th Annual Keck Research Conference, Oct 2019
* Completed written thesis and oral defense in April 2020
  """

[[experience]]
  title = "Software Engineering Intern"
  company = "iCloud Storage Analytics, Apple"
  company_url = "https://www.apple.com/icloud/"
  location = "Cupertino, CA"
  date_start = "2018-05-15"
  date_end = "2018-08-15"
  description = """
**Anomaly Detection on Time-Series Metrics**

* Built a data pipeline to query server logs and gather time-series metrics on our services
* Wrote a Spark job in Scala to process and aggregate raw data, storing the results in blob storage
* Developed and implemented an anomaly detection system in Python using Pandas, SciPy and Matplotlib to automatically detect regressions in quality of service among subsets of our network and generate reports to alert iCloud engineers. Deployed system surfaces one to two critical issues each day that otherwise went unnoticed.
* Presented work to ~30 engineers at iCloud and individually to the Vice President of iCloud
  """

[[experience]]
  title = "Undergraduate Research"
  company = "Kavraki Computational Robotics, AI and Biomedicine Lab, Rice University"
  company_url = "kavrakilab.org"
  location = "Houston, TX"
  date_start = "2018-01-01"
  date_end = "2018-12-16"
  description = """
**Benchmarking an Incremental Docking Protocol**

* Improved an incremental docking protocol (DINC) which computationally predicts how peptides bind to protein receptors. Experimented to identify unexpected behavior; strengthened the robustness of DINC by handling these edge cases. 
* Evaluated the latest version of DINC by designing re-docking experiments and writing scripts to automate these tests on the XSEDE Comet Supercomputer. Results published in Devaurs et al, 2019.
* Presented poster at the Rice Undergraduate Research Symposium, April 2018
  """

+++
