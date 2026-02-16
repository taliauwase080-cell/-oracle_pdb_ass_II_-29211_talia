# Oracle Pluggable Database Assignment II  
**Student Name:** Talia Mugisha Uwase  
**Student ID:** 29211  
**Course:** Database Development with PL/SQL (INSY 8311)  
**Instructor:** Eric Maniraguha  
**Assignment Date:** February 9, 2026  

---

## Overview of Tasks  
This repository contains the work and documentation for the individual practical assignment focused on Oracle Pluggable Database (PDB) management. The tasks completed include:

1. Creation of a new Pluggable Database (PDB) with specified naming conventions.  
2. Creation of a user inside the PDB with required roles and permissions.  
3. Creation and deletion of a temporary PDB as per assignment instructions.  
4. Configuration and access of Oracle Enterprise Manager (OEM) to verify the environment and PDBs.  
5. Professional documentation of the process including screenshots and SQL scripts.

---

## Oracle Environment Used  
- Oracle Database 19c Enterprise Edition  
- Oracle Multitenant Architecture enabled  
- Oracle Enterprise Manager Database Express (OEM) version corresponding to Oracle 19c  
- SQL*Plus command-line interface  

---

## Explanation of Each Task  

### Task 1: Create a New Pluggable Database  
- Created PDB named `ta_pdb_29211` following the naming convention (FirstTwoLettersOfFirstName_pdb_StudentID).  
- Created user `talia_plsqlauca_29211` inside the PDB with DBA role and assigned proper tablespace quota.  
- Ensured PDB is opened and accessible.

### Task 2: Create and Delete a Temporary PDB  
- Created temporary PDB named `ta_to_delete_pdb_29211` following naming conventions.  
- Verified its existence using SQL queries.  
- Closed and dropped the temporary PDB completely including datafiles.

### Task 3: Oracle Enterprise Manager (OEM)  
- Accessed OEM Database Express through browser (`https://localhost:5500/em`).  
- Verified the PDBs and user accounts are visible and correctly configured.  
- Took screenshots of the OEM dashboard showing the environment and users.

### Task 4: Documentation and Reporting  
- Prepared this professional README file.  
- Uploaded all required screenshots in the `screenshots/` folder.  
- Ensured GitHub repository visibility is set to PUBLIC.  

---

## Challenges Faced and Solutions  
- Encountered permission errors when managing tablespaces and PDBs; resolved by ensuring connection as `SYSDBA` from root container (`CDB$ROOT`).  
- Learned to run multi-line SQL commands correctly by pasting whole blocks rather than line-by-line in SQL*Plus.  
- Accessing OEM required confirming the correct port and ensuring database listener was running.

---

## Integrity Statement  
I certify that this submission is entirely my own work and that I have not copied or collaborated with any other student. I fully understand the importance of academic integrity and commit to upholding it throughout my studies.

---

## Repository Structure  
- `README.md` — This documentation file.  
- `screenshots/` — Contains all screenshots required as evidence (PDB creation, user creation, temporary PDB deletion, OEM dashboard).  
- `sql_scripts/` — (Optional) Folder containing SQL scripts used for PDB and user management.

---

## Repository Link  
[Provide your public GitHub repository URL here]

---

## Additional Notes  
Feel free to contact me at [your email] for any questions regarding this assignment.

---

*Thank you for reviewing my work.*

