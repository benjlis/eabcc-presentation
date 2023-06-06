---
marp: true
theme: gaia
class:
  - invert
paginate: true
---
<!-- _class: lead -->
**Creating Email Archives from PDFS - The COVID-19 Corpus**
EA:BCC Email Archiving Symposium
June 14th, 2023

---
<!-- _class: lead -->
**This is an awardee presentation**
Thank you to EA:BCC and the Mellon Foundation!

---
# About Me
* Ben Lis 
* Data Engineer at the History Lab @ Columbia University
* Not an archivist
* Not a historian
* I do develop tools and infrastructure for historians and archivists
---
# Agenda
1. Background
2. Software Products
3. Subsequent & Future Work
4. Questions & Discussions 
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
# Collection Building with FOIAed Docs
* Excellent example: [Documenting COVID-19](documentingcovid19.io)
* Started by Derek Kravitz at the Brown Institute for Media Innovation
* Local, state and federal COVID-19 related documents including well over 35K emails
* Award-winning: 2022 National Headliners Award, 2021 Sunshine Award, 2020 Free Speech & Open Government Award  
---
# Email Formats for Archives
|Emails|NARA|LOC|
|----|---------|----------|
|Aggregated|**PST, MBOX**|PST, MBOX, PDF
|Individual|**EML, MBOX**, MSG, XML|EML, MSG, PDF|

* Preferred formats are bolded
* Email archiving systems generally support MBOX and/or IMAP  
* Sources: [NARA](https://www.archives.gov/records-mgmt/policy/transfer-guidance-tables.html#email2), [LOC](https://www.loc.gov/preservation/resources/rfs/email.html)

---
# PDF/email
* PDF has shortcomings as an email archiving format
  * Not addressed by PDF/A 
* A group is working to eliminated these shortcoming   
* Known originally as EA-PDF, now called PDF/mail
* Long term goal: PDF/M ISO standard 
* Check out Mike and Chris's [talk](https://emailarchivesgrant.library.illinois.edu/timetable/event/project-briefing-11/) tomorrow at 11:00 
---
# FOIAed Email Formats
* Predominant: PDF
* Occassionally: PST, MBOX
* Typical Example: (Fauci Emails)[]