---

 Secure File Sharing System (Flask + AES Encryption)

 Project Overview

This project is part of my internship assignment and demonstrates the development of a secure file sharing system. The application allows users to upload and download files safely, ensuring all files are encrypted before storage and decrypted upon retrieval.

The system focuses on **data security**, applying **AES encryption** to protect sensitive information — simulating real-world scenarios where secure data handling is critical (e.g., healthcare, legal, or corporate environments).

---
Features

* ✅ Secure **file upload & download** via a web portal
* ✅ **AES encryption** for files at rest
* ✅ Decryption during download (ensures integrity)
* ✅ Simple and user-friendly **HTML interface**
* ✅ Basic **encryption key management**
* ✅ Documented architecture and security considerations

---

Tech Stack

* **Backend:** Python (Flask)
* **Encryption:** PyCryptodome (AES)
* **Frontend:** HTML, CSS
* **Version Control:** Git & GitHub

---

 Security Considerations

* All files are encrypted with **AES symmetric encryption** before being saved.
* Files are decrypted only at the point of download.
* **Key management**: For demonstration, a static key is used. In real-world use, keys should be stored securely (e.g., environment variables, vault services).
* Protects against unauthorized file access at rest.

---


Author

OLUWATOSIN RUTH OLUBOWALE
Internship Project | 2025


