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
  title = "AI Residency"
  company = "Google Research"
  company_url = "research.google.com"
  location = "San Francisco, CA"
  date_start = "2021-02-01"
  date_end = ""
  description = """
Compression for Federated Learning  

* Designed a custom compression method for client updates in federated learning to reduce the communication cost from 32 bits per model parameter to 0.1 bits without degrading accuracy on several benchmarks.
*	Implemented [compression-based aggregation methods](https://github.com/google-research/federated/tree/1b31b84/compressed_communication) for federated learning in TensorFlow Federated. This involved: custom TF ops hosted in [TensorFlow Compression](https://github.com/tensorflow/compression), TensorFlow Federated logic, and robust integration tests for system compatibility.
*	Presented this work to internal and external audiences. Selected to give an oral presentation at the Google Research Conference. Submitted a paper to ICML 2022, currently under review.
*	Integrated custom compression method into Google’s federated learning production system (in flight)

  """
[[experience]]
  title = "Science Policy"
  company = "Baker Institute for Public Policy, Rice Univeristy"
  company_url = "https://www.bakerinstitute.org/research/apply-developing-civic-scientist-leaders/"
  location = "Houston, TX"
  date_start = "2020-01-01"
  date_end = "2020-08-30"
  description = """

Developing Civic Scientist Leaders Program  

* One of ten graduate students selected to participate in a weekly seminar to learn about the federal policymaking process and develop critical leadership skills to advance science as a public good
* [Published an op-ed](http://blog.bakerinstitute.org/2020/04/16/sears-once-your-ordinary-department-store-now-a-vehicle-for-tech-sector-gentrification-2/) on a public policy issue; [created one-pagers](https://nicolemitchell.github.io/files/HoustonResearchOnePager.png) advocating for funding basic scientific research to use in our upcoming congressional visits in Washington, D.C.

  """

[[experience]]
  title = "Graduate Research"
  company = "Kavraki Computational Robotics, AI and Biomedicine Lab, Rice Univeristy"
  company_url = "kavrakilab.org"
  location = "Houston, TX"
  date_start = "2019-01-01"
  date_end = "2020-05-16"
  description = """
Drug Metabolism Prediction Using Graph-based Learning

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
Anomaly Detection on Time-Series Metrics

* Built a data pipeline to query server logs and gather time-series metrics on our services
* Wrote a Spark job in Scala to process and aggregate raw data, storing the results in blob storage
* Developed and implemented an anomaly detection system in Python using Pandas, SciPy and Matplotlib to automatically detect regressions in quality of service among subsets of our network and generate reports to alert iCloud engineers. Deployed system surfaces one to two critical issues each day that otherwise went unnoticed.
* Presented work to ~30 engineers at iCloud and individually to the Vice President of iCloud
  """

[[experience]]
  title = "Undergraduate Research"
  company = "Kavraki Computational Robotics, AI and Biomedicine Lab, Rice Univeristy"
  company_url = "kavrakilab.org"
  location = "Houston, TX"
  date_start = "2018-01-01"
  date_end = "2018-12-16"
  description = """
Benchmarking an Incremental Docking Protocol

* Improved an incremental docking protocol (DINC) which computationally predicts how peptides bind to protein receptors. Experimented to identify unexpected behavior; strengthened the robustness of DINC by handling these edge cases. 
* Evaluated the latest version of DINC by designing re-docking experiments and writing scripts to automate these tests on the XSEDE Comet Supercomputer. Results published in Devaurs et al, 2019.
* Presented poster at the Rice Undergraduate Research Symposium, April 2018
  """

[[experience]]
  title = "Software Engineering Intern"
  company = "Appointments iOS, Square"
  company_url = "https://squareup.com/us/en/appointments"
  location = "San Francisco, CA"
  date_start = "2017-05-15"
  date_end = "2017-08-15"
  description = """
Improving Square's Appointment Scheduling Calendar

* Optimized the calendar in Square Appointments iOS app by identifying performance bottlenecks and improving the search algorithm. Made a 16-fold improvement in CPU time spent rendering events and UI features that restored calendar to 60 fps scrolling.
* Added a feature to notify users when their time zone differs from that of the business they are viewing

Using Word2Vec to Power a Recommendation Engine

* Developed a [customized market insights tool](https://developer.squareup.com/blog/using-word2vec-to-power-a-recommendation-engine) for merchants to compare their prices to those of nearby sellers
* Grouped similar transactions using the “word2vec” ML model
* Built a Python Flask app with D3 Visualization to display interactive reports
  """

[[experience]]
  title = "Software Engineering Intern"
  company = "FBU, Facebook"
  company_url = "https://www.facebook.com/careers/students-and-grads/students"
  location = "Cupertino, CA"
  date_start = "2016-06-01"
  date_end = "2016-08-15"
  description = """
Building an iOS Mobile Application

* Developed an iOS mobile app in Swift that helps users remember the people they’ve met by using location tracking to auto-log events
  """

+++
