# oss-audit-24BCE10177
Capstone project containing shell scripts for the Open Source Software Audit of the Apache HTTP Server.

**Author:** Manvith Reddy Kandi (24BCE10177)
**Course:** Open Source Software Capstone Project

## Project Overview
This repository contains five custom Bash shell scripts written for an Ubuntu Linux environment as part of an open-source audit of the Apache HTTP Server. 

## Included Scripts
* **`script1.sh` (System Identity Report):** Dynamically retrieves core Linux host identity metrics.
* **`script2.sh` (FOSS Package Inspector):** Verifies the APT installation status and architecture of Apache.
* **`script3.sh` (Disk and Permission Auditor):** Loops through and audits system directories and the `/etc/apache2` configuration folder.
* **`script4.sh` (Log File Analyzer):** Parses error logs line-by-line using a conditional while-read loop to flag specific system errors.
* **`script5.sh` (Manifesto Generator):** An interactive prompt that generates a personalized open-source philosophy text file.

## How to Run
To execute any of these scripts on a Debian/Ubuntu system, first grant execution permissions:
```bash
chmod +x script_name.sh
./script_name.sh
