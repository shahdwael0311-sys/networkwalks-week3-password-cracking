Password Cracking Lab — Week 3 Project (Networkwalks Academy)
Overview

This repository documents my completion of the Week 3 project modules from the Cybersecurity & Ethical Hacking course by Networkwalks Academy. The goal was to recover the password of a protected PDF file using two different approaches.

Modules Completed
Module 1 — Password Cracking with JTR (John the Ripper)
Installed John the Ripper (JTR) and the Johnny GUI on Windows.
Extracted the password hash from a locked PDF using an online PDF-hash extractor (pdf2john equivalent).
Loaded the hash into Johnny and ran a dictionary attack.
Result: password cracked successfully, PDF unlocked.
Module 2 — Password Cracking with Networkwalks Tools
Used Networkwalks' own browser-based Hash Calculator to extract the PDF hash (no installation required).
Used the Networkwalks Password Cracker tool to run a dictionary attack against the hash.
Result: password cracked successfully, PDF unlocked.
Tools Used
John the Ripper (JTR) — offline password/hash cracking
Johnny — GUI frontend for JTR
Online PDF Hash Extractor — extracts crackable hash from encrypted PDF
Networkwalks Hash Calculator — browser-based hash extraction
Networkwalks Password Cracker — browser-based dictionary attack tool
Key Takeaway

Weak, common passwords can be cracked in seconds using freely available tools. This lab reinforced why strong, unique passwords and proper hashing/salting practices are essential for real-world security.

Credit

Lab materials, project tasks, and the Networkwalks Hash Calculator / Password Cracker tools were provided by Networkwalks Academy as part of their Cybersecurity & Ethical Hacking training program.
