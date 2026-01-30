# Digital Forensics Investigation: Insider Threat 🔍

## Objective Summary
This investigation was conducted to determine if an employee, John Smith, engaged in the theft and unauthorized sale of proprietary company information. Through tactical forensic analysis, evidence was uncovered showing the collection of confidential data and research into anonymous transaction methods.

## Tools & Environment
* **Forensic Software:** Autopsy 4.19.1.
* **Data Source:** Disk Image (JSmit_Q1.001).
* **Methodology:** NIST-based forensic process (Collection, Examination, Analysis, Reporting).

---

## 🛠️ Investigation Workflow

### 1. Case Initialization & Evidence Integrity
* **Case Setup:** Initiated a unique case file in Autopsy to ensure all gathered data was correctly identified under a unique ID.
* **Directory Management:** Linked the case file to a secure directory (C:\Users\LabUser\Desktop\Evidence Files) for centralized access and maintenance.
* **Documentation:** Recorded investigator details and a summary of the forensic exam justification to ensure legal and technical integrity.

### 2. Data Ingestion & Analysis
* **Source Selection:** Identified and authenticated the disk image as the primary evidence type for analysis.
* **Ingest Modules:** Utilized default ingestion parameters to extract valuable information from the data source, including recent activity and file metadata.
* **Keyword Search:** Conducted targeted searches for material implying malicious activity, specifically focusing on "bitcoin" and "anonymous transactions".

### 3. Evidence Identification
* **File Recovery:** Successfully retrieved data from multiple directories, including **deleted files** and hidden data artifacts.
* **Artifact Discovery:** Analyzed directories to uncover:
    * Research on "How to hide data in plain sight".
    * Documentation on "Making untraceable bitcoin transactions".

---

## 🚩 Summary of Findings
Based on the metadata and file analysis, there is strong evidence of malicious intent:
* **Data Collection:** Unauthorized access and collection of company proprietary information.
* **Exfiltration Planning:** Evidence of the subject researching methods to sell data to unknown entities using non-traceable Bitcoin transaction.

## Skills Demonstrated
* **Evidence Preservation:** Maintaining data integrity through proper case and directory setup.
* **Forensic Analysis:** Navigating complex directory structures to recover deleted security files.
* **Reporting:** Producing structured findings that detail malicious timelines and user intent.
