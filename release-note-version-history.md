---
layout: default
title: ""
description: ""
---

# **DALEY DOSE VERSION HISTORY**
The following are the Release Notes of previous versions for the **Daley Dose** application.

# **DALEY DOSE – VERSION 1.3 – RELEASE DATE: 2024-09-15**  
---

This release introduces auto-complete functionality, note and medication deletion, handwritten prescription scanning, expanded user roles, and increased limits for prescriptions and notes.

## **NEW FEATURES**  
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

## **ENHANCEMENTS**  
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

## **KNOWN ISSUES**  
---



- 
# **VERSION 1.2**
---

# **VERSION 1.1**
---

## **SEE ALSO**
---
- [**Version 1.4 Release Notes**](/daleydose/release-notes-v1.4)
- [**Product Overview**](https://hiredale.github.io/daleydose/)
- [**Help Files and Online Support**](/daleydose/help-files)
- [**HireDale.com**](https://hiredale.github.io)
