# ITSupport247-Patch-Deployment-Report-Guide
Diagnose failed patch installations, by obtaining a report
# ITSupport247: Patch Deployment Report Guide

**Version 1.1** | **Luis Lazo** | **CMIT Solutions Santiago**  
**Purpose:** Diagnose failed patch installations by customer

## 📋 Step-by-Step Instructions

### Step 1: Access ITSupport247 Dashboard
- ConnectWise Login → Click **"Asio"**  

![Login](/Doc/login.png)  

### Step 2: Navigate to Reports
- ITSupport247 Dashboard → **"Reports"** section  

### Step 3: Patch Deployment Report
- Reports → **"Disclose Patches"** → **"Patch Deployment Report"**  

![select](/DoC/select.png)  

### Step 4: Filter by Customer
- **Customer Selection Dropdown** → Choose target(s):
  - Individual client
  - Customer group
  - All customers
![filter](/Doc/filter.png)

### Step 5: View Results & Diagnose

![results](/Doc/results.png)  


## 🔍 Common Failure Reasons & Fixes

| Error | Cause | Fix |
|-------|-------|-----|
| **0x80070643** | .NET Framework conflict | Manual uninstall |
| **1603** | MSI conflict | Reboot + retry |
| **Pending Reboot** | Reboot required | Force reboot policy |
| **WSUS Sync Issue** | Sync failure | "Windows Patch Troubleshooter"

## 📊 Pro Tips
- ✅ Export to CSV for Jackson/tickets
- ✅ Filter by "Failed" status only
- ✅ Schedule weekly for compliance
- ✅ Screenshot → ConnectWise ticket

**Author:** Luis Lazo 
