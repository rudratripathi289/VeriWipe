# 🔐 Secure Data Wiping for Trustworthy IT Asset Recycling

## 📌 Overview
This project is a **secure, cross-platform data wiping tool** designed to eliminate all user data from devices before recycling or disposal.  

It addresses the growing **e-waste problem in India** by ensuring that users can safely erase sensitive data and confidently recycle their devices.

---

## 🚨 Problem
- Users hesitate to recycle devices due to **fear of data breaches**.
- Existing tools are:
  - Complex to use
  - Expensive
  - Lack **proof of data erasure**
- Hidden storage areas like **HPA (Host Protected Area)** and **DCO (Device Configuration Overlay)** are often ignored.

---

## 💡 Solution
Our application provides:
- ✅ One-click secure data wiping
- ✅ Cross-platform support (Windows, Linux, Android)
- ✅ Wiping of **hidden areas (HPA/DCO)**
- ✅ SSD secure erase support
- ✅ Offline functionality (Bootable USB/ISO)
- ✅ Digitally signed **tamper-proof wipe certificates**
- ✅ Third-party verification support

---

## ⚙️ Features
- 🔹 Complete data sanitization (visible + hidden storage)
- 🔹 NIST SP 800-88 compliant wiping methods
- 🔹 Simple and user-friendly interface
- 🔹 Works without internet connection
- 🔹 Generates:
  - 📄 PDF certificate
  - 📂 JSON audit log
- 🔹 Digital signature for authenticity

---

## 🧠 Tech Stack

### Frontend
- Electron
- React

### Backend
- Node.js
- System-level commands (hdparm, diskpart, shred, etc.)

### Certificate Generation
- PDFKit / jsPDF
- Node Crypto (for digital signatures)

### Database (Optional)
- MongoDB (for logs and tracking)

### Bootable Environment
- Linux Live ISO (Ubuntu/Debian based)

---

## 🔄 Workflow

1. User launches the application or boots via USB
2. Tool detects available storage devices
3. User selects device and initiates wipe
4. Application:
   - Overwrites data
   - Clears HPA/DCO hidden areas
   - Performs SSD secure erase
5. Verification step ensures data is erased
6. System generates:
   - Signed PDF certificate
   - JSON log file
7. Certificate can be verified by third parties

---

## 🔐 NIST SP 800-88 Compliance
The tool follows industry-standard data sanitization methods:
- **Clear** → Overwriting data
- **Purge** → Secure erase for SSDs
- Ensures data cannot be recovered

---

## 📜 Certificate of Erasure
After wiping, the system generates:
- Device details
- Timestamp
- Wipe method used
- Digital signature

This ensures:
- ✔ Tamper-proof proof
- ✔ Trust for recyclers
- ✔ Auditability

---

## 🌍 Impact
- Encourages safe **device recycling**
- Reduces **e-waste hoarding**
- Prevents **data theft**
- Supports **circular economy**

---

## 🚀 Future Scope
- Cloud-based verification system
- Blockchain-based certificate validation
- Support for more devices (IoT, servers)
- Enterprise dashboard for bulk wiping

---

## 👨‍💻 Team
- Add your team member names here

---

## 📎 License
This project is developed for **Smart India Hackathon (SIH)**.