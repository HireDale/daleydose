---
title: "Daley Dose - Version History"
description: ""
layout: default
---

# **DALEY DOSE VERSION HISTORY**
---
This page provides a complete record of changes to the Daley Dose application, organized by release.  
Each version lists updates under three categories:

- **New Features** – Capabilities introduced for the first time in that release.
- **Enhancements** – Improvements to existing functionality, performance, or usability.
- **Bug Fixes** – Corrections to defects, errors, or unexpected behaviors.

Versions are presented in reverse chronological order, with the most recent release at the top.

## **VERSION 1.3**  
---

**RELEASE DATE**: 2024-09-15

This release introduces auto-complete functionality, note and medication deletion, handwritten prescription scanning, expanded user roles, increased limits for prescriptions and notes, and critical bug fixes.

![Daily Dose user interface version 1.3](/assets/images/daley-dose-home-window.1.3.png)  
<p style="text-align:center;"><em>The Daley Dose user interface for version 1.3</em></p>

### **NEW FEATURES**  
---

- **Auto-complete medication names**  
  You can now receive generic and brand name suggestions when entering medication details in the **Add Medication** window.
  - Added the **Auto-Complete Status** field with the following indicators:  
    - Green – auto-complete is enabled  
    - Red – auto-complete is disabled  
    - Purple – auto-complete is disabled for all accounts by an administrator  
  - This feature is enabled by default and can be turned off in the **Options** window.  
  - See Figure 1: The **Add Medication** window with the newly added **Auto-Complete Status** field  
  - **REFERENCE NUMBERS:** DD-1543 / DD-1545 / DD-1556

![Figure 1](/assets/images/daley-dose-add-meds.png)  
<p style="text-align:center;"><em><strong>Figure 1</strong>: The Add Medication window with the newly added <strong>Auto‑Complete Status</strong> field</em></p>

---

- **Delete existing medications and notes**  
  You can now delete medications and notes directly from the current prescription.
  - Added the **Medication Number** and **Note Number** fields  
  - Double-clicking either field deletes the corresponding item  
  - The application displays the confirmation message **"Are you sure you want to delete this from the prescription?"** before deletion  
  - Deleted items cannot be restored; re-entry must be done manually using the **+ Med** or **+ Note** buttons  
  - Deletion is not available for transcribed prescriptions  
  - **REFERENCE NUMBERS:** DD-1523 / DD-1525 / DD-1526

---

- **Digitize handwritten prescriptions**  
  You can now scan handwritten notes using your webcam or smartphone to create digital prescriptions.
  - Added the **Scan** button (desktop and mobile)  
  - Desktop version requires a connected webcam; mobile version always displays the button  
  - Scanned prescriptions cannot be edited  
  - See Figure 2: The **Home** window with the newly added **Scan** button  
  - **REFERENCE NUMBERS:** DD-1585 / DD-1586

![Figure 2](/assets/images/daley-dose-scan-button.png)  
<p style="text-align:center;"><em><strong>Figure 2</strong>: The Home window with the newly added <strong>Scan</strong> button</em></p>

---

- **Additional user profile roles**  
  You can now assign roles to users in the **User Profile** window.
  - Added the **Role** field with the following options:  
    - Administrator  
    - Support  
    - Prescriber  
    - Pharmacist  
    - Spectator  
  - Only **Administrator** and **Support** roles can assign or edit roles  
  - Only **Prescriber** role can prescribe medication  
  - **REFERENCE NUMBERS:** DD-1500 / DD-1501

### **ENHANCEMENTS**  
---

- **Increased medication limit per prescription**  
  You can now add up to 5 medications per prescription (previous limit was 3).
  - **REFERENCE NUMBER:** JIRA-DD-1562

---

- **Increased note limit per medication**  
  You can now add up to 5 notes per medication (previous limit was 3).
  - Increased note length from 10 words to 25 words  
  - The application displays the error message **"Note Too Long"** if a note exceeds 25 words  
  - **REFERENCE NUMBERS:** DD-1563 / DD-1564

### **BUG FIXES**  
---

- **DD-1510**  
  Resolved a known issue where the application incorrectly recognized *Potion of Minor Healing* as the generic name for cough medication.

- **DD-1511**  
  Resolved a known issue where the application incorrectly recognized *Thoughts and Prayers* as a type of chemotherapy medication.

- **DD-1514**  
  Fixed a rare bug where the application sent multiple copies of the same Schedule II Narcotics prescription to different pharmacy outlets when you selected **Send**.  
  - The application now assigns a serial number per prescription to prevent duplicates.

- **DD-1515**  
  Resolved an issue where the application incorrectly approved the prescription of Schedule II Narcotics for minor pain diagnoses.

- **DD-1519**  
  Fixed a common bug that duplicated the **Doctor** title when applying an **MD Signature**.

- **DD-1520 / DD-1521 / DD-1524**  
  Fixed a rare bug that incorrectly classified Schedule II Narcotics as over-the-counter (OTC) medication.

- **DD-1525 / DD-1526 / DD-1527**  
  Resolved an issue where the application erased all progress when the internet connection disconnected during prescription creation.  
  - The application now saves current progress, allowing you to continue building the prescription.  
  - An active internet connection is still required to finalize, send, or print the draft.

---
## **VERSION 1.2**  
---

**RELEASE DATE**: 2024-06-15

This release introduces the ability to add alternative medications, apply prescription restrictions, and includes critical bug fixes to improve reliability and patient safety.

### **NEW FEATURES**  
---

- **Add alternative medication**  
  You can now add an alternative option to a prescribed medication when the original is unavailable at the pharmacy. This ensures patients can receive their medication without returning for a refill. *(All platforms)*  
  - Added the **+ Alt** button, which opens the **Add Alternative** window.  
  - You can enter a different brand or generic name for the selected medication.  
  - The application uses the alternative when the pharmacy reports the original medication is out of stock on a patient’s refill date.  
  - **REFERENCE NUMBERS:** DD‑1467 / DD‑1468

---

- **Add prescription restrictions**  
  Administrators can now set prescription restrictions for Prescriber users in **Home > Profile**. *(All platforms)*  
  - Added the **Prescription restriction** drop‑down list with the following options:  
    - No restrictions  
    - Restrict Schedule II  
    - Restrict Schedule II and III  
    - Restrict Schedule II, III, and IV  
    - Only OTCs  
  - Only Administrators can set this option for Prescriber users.  
  - Contact your company’s tech support for more information.  
  - **REFERENCE NUMBER:** JIRA‑DD‑1471

### **BUG FIXES**  
---

- **DD‑1402**  
  Resolved an issue where the application incorrectly recognized *Just Be Happy* as an antidepressant medication.

- **DD‑1405**  
  Fixed a critical issue where pharmacies received notifications for all patients, causing repeated alerts until devices were turned off.

- **DD‑1406**  
  Fixed an authentication issue that required users to re‑enter their information every minute.

- **DD‑1409**  
  Resolved a bug that disabled prescription features on phones older than five years.

---

## **VERSION 1.1**  
---

**RELEASE DATE**: 2024-03-16

This release introduces the ability to continue writing a prescription from a previous session and includes critical bug fixes to improve stability and prevent unintended QR code behavior.

### **NEW FEATURES**  
---

- **Continue previous session**  
  You can now resume writing a prescription from where you left off in a previous session. *(All platforms)*  
  - Modified Daley Dose to save the last unfinalized session before you closed the application.  
  - Upon starting the application, you can view and continue from the last saved instance of a previous prescription (if any).  
  - This feature is enabled by default and can be disabled in the **Options** window.  
  - **REFERENCE NUMBERS:** DD‑1333 / DD‑1334

### **BUG FIXES**  
---

- **DD‑1316**  
  Fixed a minor bug that closed the application when it idled for more than 30 seconds.

- **DD‑1317**  
  Resolved an extremely rare bug where the finalized prescription’s QR code sent pharmacies a link to the Rickroll YouTube page.

- **DD‑1318**  
  Resolved an extremely rare bug where the finalized prescription’s QR code sent pharmacies the entire opening monologue to the *Bee Movie*, causing devices to crash due to the amount of lines and text.

## **SEE ALSO**
---
- [**Version 1.5 Release Notes**](/daleydose/release-notes-v1.5)
- [**Access the Help Files**](/daleydose/help-files)
