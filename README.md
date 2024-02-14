# Secured_Health_Record_System
Secured Health Record System Built Using Netbeans & Java - Security (SHA1 Algorithm)

This project provides a secured interface for the confidential information present in Electronic Health Record (EHR) which are vital and requires maximum security. An
Electronic Health Record (EHR) is an electronic version of a patient’s medical history, that is maintained by the provider over time, and may include all of the key
administrative clinical data relevant to that persons care under a particular provider, including demographics, progress notes, problems, medications, vital signs, past medical
history, immunizations, laboratory data and radiology reports   The EHR automates access to information and has the potential to streamline the clinician&#39;s workflow.  The
EHR also has the ability to support other care-related activities directly or indirectly through various interfaces, including evidence-based decision support, quality
management, and outcomes reporting.

The EHR system in this project is secured using SHA3 algorithm which involves unique “SALT KEY” for every encryption of data. In cryptography, a salt is random data that is used as an additional input to a one-way function that "hashes" data, a password or passphrase. Salts are closely related to the concept of nonce. The primary function of salts is to defend against dictionary attacks or against its hashed equivalent, a pre-computed rainbow table attack.

Salts are used to safeguard passwords in storage. Historically a password was stored in plaintext on a system, but over time additional safeguards developed to protect a user's password against being read from the system. A salt is one of those methods.

A new salt is randomly generated for each password. In a typical setting, the salt and the password (or its version after Key stretching) are concatenated and processed with a cryptographic hash function, and the resulting output (but not the original password) is stored with the salt in a database. Hashing allows for later authentication without keeping and therefore risking the plaintext password in the event that the authentication data store is compromised.
