# **Secured Health Record System**  

A **secure Electronic Health Record (EHR) system** built using **Java (NetBeans IDE)** with advanced cryptographic security, including **AES encryption** and **SHA-1 hashing with salting** for enhanced data protection.  

## **Overview**  
This project provides a **secured interface for confidential Electronic Health Records (EHRs)**, ensuring maximum protection for sensitive patient data.  

An **Electronic Health Record (EHR)** is a digital version of a patient’s medical history, maintained over time by healthcare providers. It typically includes:  
- **Patient demographics**  
- **Progress notes**  
- **Medical history**  
- **Medications & prescriptions**  
- **Vital signs**  
- **Immunization records**  
- **Laboratory data & radiology reports**  

The EHR system **automates access to patient data**, streamlining workflows for healthcare providers. Additionally, it supports care-related activities such as **evidence-based decision support, quality management, and outcomes reporting**.  

## **Security Implementation**  
### **AES Encryption & Cryptographic Verification**  
To safeguard patient records, this system employs **AES (Advanced Encryption Standard) encryption** along with **cryptographic verification** using a **unique "SALT KEY" for each data verification request**.  

### **How Salting & Hashing Work**  
- **Salting**: A unique salt is generated for each password or sensitive data entry.  
- **Hashing**: The salted value is processed using a **one-way cryptographic hash function (SHA-1)**.  
- **Protection Against Attacks**: This technique prevents **dictionary attacks** and **precomputed rainbow table attacks**, making brute-force decryption highly impractical.  
- **Data Security in Storage**: Even if an attacker gains access to the stored data, they cannot retrieve the original passwords without the unique salts.  

### **Why Salting & Hashing Matter?**  
Traditionally, passwords were stored in plaintext, posing a huge security risk. With **salting and hashing**, passwords remain protected even if the database is compromised, ensuring that sensitive information remains unreadable.  

## **Technologies Used**  
- **Java** (NetBeans IDE)  
- **AES Encryption** (Data Protection)  
- **SHA-1 Hashing** (Password Security)  
- **Salting Mechanism** (Prevention of Attack Vectors)  

## **Installation & Usage**  
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/rrishi0309/Secured_Health_Record_System.git
   cd Secured_Health_Record_System
   ```  
2. **Open in NetBeans**  
   - Import the project into **NetBeans IDE**  
   - Build and run the project  

3. **Set Up Database**
   - Ensure a secure database is configured to store encrypted health records  
   - Follow security best practices for database access control  

## **Future Enhancements**  
- Upgrade encryption to **AES-256** for stronger security  
- Implement **multi-factor authentication (MFA)** for login verification  
- Introduce **role-based access control (RBAC)** for better user permissions  

## **License**  
This project is **open-source** and available under the **MIT License**.  

