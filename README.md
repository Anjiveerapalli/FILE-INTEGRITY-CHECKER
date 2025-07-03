# FILE-INTEGRITY-CHECKER

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: VEERAPALLI ANJI

*INTERN ID*: CT08DM452

*DOMAIN*: CYBERSECURITY AND ETHICAL HACKING

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH
# DESCRIPTION:
A File Integrity Checker is a security tool designed to monitor changes in files by calculating their hash values and comparing them over time. This helps detect unauthorized modifications, accidental changes,
deletions, or new files in sensitive directories.

The tool works by:

->Creating a baseline snapshot of files and their hash values.

->Periodically recalculating hashes to detect differences.

It is especially useful for:

->Monitoring critical system files.

->Ensuring the integrity of application or configuration files.

->Detecting malware, tampering, or unintended edits.

# FEATURE:                                                    

->Calculates **SHA-256 hash** to detect even minor changes.            

->Monitors all files inside a given directory and its subfolders.      

->Saves file hashes to a baseline (`baseline.json`).                   

->Identifies **Modified**, **Deleted**, and **New files**.             

->Run with simple commands: `save` and `check`.                        

->Pure Python, no heavy dependencies.                                  

->Can be modified to include real-time monitoring, logging, or alerts. 

# WORKFLOW :

Workflow:

Create Baseline (save)

->Calculates SHA-256 hash for each file.

->Saves relative file paths and hashes to a JSON file.

Monitor Changes (check)

->Recalculates hashes.

->Compares to baseline.

->Reports any added, modified, or deleted files.

# Technologies Used :

->Python

->Hashlib

# OUTPUT:
![Image](https://github.com/user-attachments/assets/11685e1a-29c0-426e-b81f-87ff038e7dcb)
