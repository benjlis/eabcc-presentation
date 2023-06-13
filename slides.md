---
marp: true
theme: default
paginate: true
---
<!-- _class: lead -->
## **Creating Email Archives from PDFs - The COVID-19 Corpus**
EA:BCC Email Archiving Symposium
Ben Lis - History Lab, Columbia University
June 14th, 2023

---
## Creating Email Archives from PDFs -The COVID-19 Corpus Abstract

> This awardee project briefing provides an overview of the efforts to build a Python library that extracts individual email metadata and text from PDFs. We will also report our experiences using it to enhance a corpus of FOIAed documents, some thousands of pages long, regarding the response of public officials, mostly state and local, from the early days of the COVID-19 pandemic.
---
<!-- _class: lead -->

# Thank you to EA:BCC and the Mellon Foundation!

---
# Disclaimer
* I'm **not** an archivist
* I'm **not** a historian
* But I do develop software tools and infrastructure for historians and archivists
---
# Agenda
1. Background
2. Software Products
3. Subsequent & Future Work
4. Questions & Discussions 
---
<!-- _class: lead -->

# 1. Background

---

# The History Lab
* History as Data Science
* We turn documents into data and develop tools to explore history
* Home to the FOIArchive 
  * the world's largest database of declassified documents
* Focus on international relations and U.S. Foreign Policy
* http://history-lab.org
---
# History Lab & Emails
* Our PI, Matt Connelly, was a member of the task force that produced [The Future of Email Archives](https://www.clir.org/pubs/reports/pub175/) report.
* Ben Lis participates in the [EA-PDF Liaison Working Group (LWG)](https://pdfa.org/community/ea-pdf-lwg/)
* [Processed & Analyzed](http://history-lab.org/clinton) the Hillary Clinton's email
---
# FOIA 
* Freedom of Information Act
* Federal law requiring full or partial disclosure of U.S. Gov't documents
* Sunshine laws: state & local equivalents
* FOIAed, FOIAing: verb describing process of requesting documents
---
# LBJ on FOIA

> A democracy works best when the people have all the information that the security of the Nation permits. No one should be able to pull curtains of secrecy around decisions which can be revealed without injury to the public interest.

* h/t [Daniel DeFraia](https://daniel-defraia.squarespace.com/) 
---
# Collection Building with FOIAed Docs
* Excellent example: [Documenting COVID-19](https://documentingcovid19.io)
* Started by Derek Kravitz at the Brown Institute for Media Innovation
* Local, state and federal COVID-19 related documents including well over 35K emails
* Award-winning: 2022 National Headliners Award, 2021 Sunshine Award, 2020 Free Speech & Open Government Award  
---
# Challenges of FOIAed Document Collections
1. Long-term preservation
2. Document processing <-- This talk focuses on this
---
# Email Formats for Archives
|Emails|NARA|LOC|
|----|---------|----------|
|Aggregated|**PST, MBOX**|PST, MBOX, PDF
|Individual|**EML, MBOX**, MSG, XML|EML, MSG, PDF|

* Preferred formats are bolded
* Sources: [NARA](https://www.archives.gov/records-mgmt/policy/transfer-guidance-tables.html#email2), [LOC](https://www.loc.gov/preservation/resources/rfs/email.html)

---
# FOIAed Email Formats
* Predominant: PDF
* Occassional: PST, MBOX
* Typical Example: (Fauci Emails)[]
---
# PDF/email
* PDF has shortcomings as an email archiving format
  * Not addressed by PDF/A 
* A group is working to eliminate these shortcomings   
* Known originally as EA-PDF, now called PDF/mail
* Long term goal: PDF/M ISO standard 
* Check out Mike and Chris's [talk](https://emailarchivesgrant.library.illinois.edu/timetable/event/project-briefing-11/) tomorrow at 11:00 
---
<!-- _class: lead -->

# 2. Software we built with the grant

---
# pdf2mbox
![](https://history-lab.github.io/pdf2mbox/pdf2mbox_diagram.png)

* command-line utility and Python library
* input: PDF containing emails
* output: mbox and/or csv file
* available on [PyPI](https://pypi.org/project/pdf2mbox/)
---
# installation
* open-source, distributed under the MIT License
* requires Python 3.8 or higher
* available on [PyPI](https://pypi.org/project/pdf2mbox/)
* simple install, from you Python environment:
```
pip install pdf2mbox
```
---
# command-line usage

---
# how it works


---
<!-- _class: lead -->

# 3. Subsequent & Future Work

---
<!-- _class: lead -->

# 4. Questions & Discussions

