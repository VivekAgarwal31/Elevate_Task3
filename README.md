# 🛡️ Vulnerability Assessment Task
**By:** Vivek Agrawal  
**Date:** October 26, 2025  
**Tools Used:** OpenVAS (Greenbone Vulnerability Management), Nessus  
**Environment:** Kali Linux VM  

---

## 🧠 Overview
This project documents a comprehensive vulnerability assessment performed on two target systems using **OpenVAS (Greenbone Vulnerability Management)**.  
It covers the complete workflow — from **target identification** and **tool setup** to **executing scans** and **submitting final reports**.  

---

## 🚀 Phase-Wise Working (OpenVAS)

### **Phase 1: Target Identification**
Two pre-configured vulnerable systems were selected for testing:
- **IP 1:** `10.10.148.71`  
- **IP 2:** `192.168.1.98`  
✅ *Basic connectivity was confirmed to ensure both systems were reachable before scanning.*

---

### **Phase 2: OpenVAS Setup**
Configured and prepared **Greenbone/OpenVAS** for use:
1. Launched OpenVAS on the assessment machine.  
2. Updated the **vulnerability feed** to ensure accurate scan results.  
3. Verified the availability of **Full and Fast** scan configuration.

---

### **Phase 3: Creating Scan Tasks**
1. Navigated to `Scans → Tasks → New Task`.  
2. Set the targets to the two IP addresses.  
3. Selected the **Full and Fast** configuration.  
4. Saved the task and prepared it for execution.  

---

### **Phase 4: Running the Scan**
1. Started the scan by clicking the **▶️ Play** icon.  
2. Monitored progress (average duration: **30–60 minutes per target**).  
3. Verified successful completion with no errors.  

---

### **Phase 5: Reviewing the Report**
After the scan:
1. Opened the final report.  
2. Reviewed vulnerabilities by **severity** — Critical, High, Medium, and Low.  
3. Examined recommended fixes and mitigation strategies.  
4. Captured screenshots of major findings for documentation.  

---

### **Phase 6: Report Submission**
1. Exported the scan results as **PDF reports**:  
   - `OpenVAS_Scan_10.10.148.71.pdf`  
   - `OpenVAS_Scan_192.168.1.98.pdf`  
2. Submitted the final reports for review and archival.  

---

## 📊 Summary

| Phase | Description | Output |
|:--|:--|:--|
| 1 | Target Identification | Selected two vulnerable IPs |
| 2 | Setup | Installed and updated OpenVAS |
| 3 | Task Creation | Configured Full and Fast scans |
| 4 | Execution | Completed scans successfully |
| 5 | Review | Analyzed vulnerabilities and fixes |
| 6 | Submission | Exported and submitted reports |

---

## 🧾 Conclusion
The vulnerability assessment was executed successfully on both targets.  
Using **OpenVAS** and **Nessus**, the analysis provided a clear view of potential exposures, categorized risks by severity, and suggested appropriate mitigation strategies.  
This project reinforces the importance of **routine vulnerability assessments** in maintaining strong cybersecurity posture.

---

> ✨ *Prepared by Vivek Agrawal as part of the Vulnerability Assessment Project — October 2025.*
