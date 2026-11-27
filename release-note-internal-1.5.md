---
title: "Daley Dose - Version 1.5"
description: ""
layout: default
---

# **VERSION 1.5 RELEASE NOTES**
---
**RELEASE DATE**: 2026-12-01

---

This document provides an overview of the new features, enhancements, and bug fixes introduced in version 1.5 of the **Daley Dose** application. This release includes a major overhaul of the application's user interface and functionality, along with updates to the medication database and prescription management features.

For questions or clarification regarding specific changes, please contact the appropriate team:

- **Applications Team:** Application functionality, user interface changes, and general behavior.
- **Development Team:** Feature implementation and technical changes.
- **QA Team:** Bug fixes, testing results, and issue verification.
- **Database Team:** Medication database updates, medical classifications, and prescription validation.

Changes in this release are organized into three categories:

- **New Features:** Capabilities introduced for the first time.
- **Enhancements:** Improvements to existing functionality, performance, or usability.
- **Bug Fixes:** Corrections to defects, errors, or unexpected behavior.

<!-- -->

![Daily Dose user interface](/assets/images/featured-updates-v1-5-2.png)

## **NEW FEATURES**
---
The following features were introduced in version 1.5 of the Daley Dose application:

---

### **REDESIGNED APPLICATION INTERFACE**

**PURPOSE**  
To provide users with a redesigned interface that improves navigation and enables faster access to commonly used tools and patient records.

**CHANGES**

- Introduced the **Information** and **Action** sidebars for easier access to application tools.
- Added the **Undo**, **Redo**, **Save**, **Clear**, **Help**, **Delete**, **Refresh**, **MIMS**, and **Finalize** buttons.

  - **Undo:** Click to undo the last action performed in the current prescription.
  - **Redo:** Click to redo the last action undone in the current prescription.
  - **Save:** Click to save the current prescription. The application automatically displays the saved prescription the next time you log in. You can view a list of saved prescriptions using the **Open** button.

    **Note:** Saved prescriptions are removed from the system.
  - **Clear:** Click to clear the current prescription entry's contents.
  - **Help:** Click to access an in-app version of the latest **Daley Dose Help Files**.

    **Notes:**
    - The help files automatically open the entry about the current window.
    - You can also view the latest version of the help files on the **Daley Dose** website.
  - **Delete:** Click to open or close **Delete Mode**, which allows you to mark existing entries in the prescription for deletion.

    **Note:** The application displays the confirmation message "**Are you sure you want to delete these from the prescription?**" before removing the selected entries from the list.
  - **Refresh:** Click to refresh the contents of the current session to match any saved instances or records in the database. This includes the contents of the patient's **Drug History** and **Medical History** tabs.
  - **MIMS:** Click to access an in-app version of the latest **Monthly Index of Medical Specialities (MIMS)** digital handbook, the most common drug reference for healthcare professionals.

    **Note:** The **MIMS** version is updated along with every **Daley Dose** version.
  - **Finalize:** Click to finalize the current prescription. When you select this button, the application locks the contents of the current prescription and enables the **Add Medical Signature**, **Print Copy**, and **Send Online** buttons.

- Added the **Drug History** and **Med History** tabs for quick access to patient prescription and medication records.  
  - **Drug History:** Displays the patient's digitized prescription history from the past 20 years.
  - **Med History:** Displays the patient's digitized medical conditions and treatments from the past 20 years.

**REFERENCE NUMBERS**  
DD-536/537/538/539/540/542/545

<!-- -->

![Daily Dose user interface](/assets/images/featured-updates-v1-5.png)

## **ENHANCEMENTS**
---
The following enhancements were introduced in version 1.5 of the Daley Dose application:

---

### **ACCESSIBILITY MODES**

**PURPOSE**  
To improve application accessibility and usability for users with different accessibility requirements.

**CHANGES**

- Added **Colorblind Mode** to improve visibility and clarity of application interface elements for users with color vision deficiencies.
- Added **Dyslexia Mode** with adjusted typography and text spacing to improve readability.
- Added **Braille Mode** to support navigation and information access through compatible Braille display devices.

**REFERENCE NUMBERS**  
DD-578/584/591/601/608/618/626

---

### **ALTERNATIVE AND MEDICAL SIGNATURE ACTIONS**

**PURPOSE**  
To centralize alternative medication and medical signature actions within the **Action** sidebar.

**CHANGE**  
Moved the **Add Alternative** and **Add Medical Signature** buttons to the **Action** sidebar.

**REFERENCE NUMBERS**  
DD-631/632/633

---

### **ASYNCHRONOUS DATA RETRIEVAL AND PROGRESSIVE LOADING**

**PURPOSE**  
To improve application responsiveness when accessing **Patient Profiles** containing extensive medical histories.

**CHANGE**  
Implemented asynchronous data retrieval and progressive loading to prevent application freezes when accessing **Patient Profiles** with extensive medical histories.

**REFERENCE NUMBERS**  
DD-634/635/636

---

### **DATABASE SYNCHRONIZATION FREQUENCY**

**PURPOSE**  
To ensure patient information is updated more frequently by reducing the interval between database synchronization cycles.

**CHANGE**  
Increased the database synchronization frequency for patient information from once every 48 hours to once every 180 seconds.

**REFERENCE NUMBERS**  
DD-638/639

---

### **DESKTOP APPLICATION INTERFACE**

**PURPOSE**  
To improve the application's usability on desktop devices and transition toward a browser-based application.

**CHANGE**  
Rebuilt the entire interface for desktop use, moving toward a browser-based application.

**REFERENCE NUMBERS**  
DD-641/642/643/644

---

### **DOCUMENT AND PRESCRIPTION ACTIONS**

**PURPOSE**  
To consolidate document and prescription-related actions within the **Action** sidebar for easier access.

**CHANGE**  
Moved the **Create New**, **Scan**, **Send**, and **Print** buttons to the **Action** sidebar.

**REFERENCE NUMBERS**  
DD-646/647/648

---

### **EXPANDED APPLICATION FIELD SELECTION AREAS**

**PURPOSE**  
To improve field selection usability by making application fields easier to interact with.

**CHANGE**  
Expanded the interactive selection areas of application fields, allowing users to select them without clicking directly within their boundaries.

**REFERENCE NUMBERS**  
DD-650/651

---

### **LOCALIZATION AND LANGUAGE CUSTOMIZATION**

**PURPOSE**  
To expand application localization capabilities and provide users with greater flexibility in language selection and customization.

**CHANGES**

- Implemented database-driven localization to support dynamic language configuration within the application.
- Expanded the available language options to support additional languages.
- Added support for **Latin**, **High Valyrian**, **Elvish**, **Dothraki**, and **Binary**.

**REFERENCE NUMBERS**  
DD-582/587/595/605/612/622/630/640/649/658

---

### **PATIENT AND MEDICAL HISTORY INFORMATION**

**PURPOSE**  
To improve access to patient and doctor information while providing a more organized workspace for prescription and medical history management.

**CHANGES**

- Moved the **Patient**, **Doctor**, and **Prescription Date** fields to the **Information** sidebar.
- Updated the work area to provide direct access to both **Prescription** and **Medical History**.
- Renamed the **Prescription Pad** area to the **Prescription** tab.

**REFERENCE NUMBERS**  
DD-660/661/662

---

### **PATIENT NAME FIELDS**

**PURPOSE**  
To standardize patient and doctor name entry by using separate first and last name fields.

**CHANGE**  
Split the **Patient Name** field into **First Name** and **Last Name** fields to match the **Doctor** field format.

**REFERENCE NUMBERS**  
DD-664/665

---

### **PRESCRIPTION CREATION**

**PURPOSE**  
To streamline prescription creation by providing direct access to medication and note entry within the Prescription tab.

**CHANGE**  
Moved the **Add Medication** and **Add Note** buttons from the sidebar to the **Prescription** tab for faster prescription creation.

**REFERENCE NUMBERS**  
DD-667/668

---

### **SCAN AND SEND BUTTON LABELS**

**PURPOSE**  
To clarify the functions of the Scan and Send actions through more descriptive button labels.

**CHANGE**  
Renamed **Scan** to **Scan Physical Copy** and **Send** to **Send Online** for clarity.

**REFERENCE NUMBERS**  
DD-670/671

<!-- -->

## **BUG FIXES**
---
The following bugs and issues were addressed in version 1.5 of the Daley Dose application:

---

### **MEDICAL DATABASE ISSUES**

---
- **DD-529**  
  Removed the incorrect recommendation of **Garlic Bread** as a prophylactic antibiotic.

<!-- -->

- **DD-530**  
  Corrected the classification of **Coffee** as an FDA-approved cardiac stimulant.

<!-- -->

- **DD-533**  
  - Removed the invalid prescription option for **Narcan** as a cure for **World of Warcraft** addiction.
  - Removed **World of Warcraft** from the available **Addiction Category** options.

<!-- -->

- **DD-557/558/559/560/561**  
  Removed the following diseases and conditions from the list of accepted medical conditions:

  - **Ataxia**
  - **Black Heart Blight**
  - **Bone Break Fever**
  - **Brain Rot**
  - **Droops**
  - **Rattles**
  - **Rockjoint**
  - **Sanguinare Vampiris**
  - **Witbane**
  - **Lycanthropy**

<!-- -->

- **DD-564/565**  
  Resolved an intermittent issue preventing the application from updating saved **Patient Profiles** with the latest database information when requests were submitted after office hours.

<!-- -->

- **DD-566/567**  
  Fixed an issue preventing **Patient Profile** creation when a portion of the patient's name was flagged as offensive by the application's international reference sources.

<!-- -->

- **DD-568**  
  Removed **Gregory House, MD**, from the list of accepted primary physicians.

<!-- -->

- **DD-569/570**  
  Resolved an issue in which the application automatically changed the **Sanguinare Vampiris** diagnosis in a **Patient Profile** to **Vampirism** three days after profile creation.

<!-- -->

- **DD-571/572/573**  
  Removed the following invalid options from the medication browser:

  - **Minor Healing Potion**
  - **Minor Mana Potion**
  - **Rejuvenation Potion**
  - **Stamina Potion**
  - **Antidote**
  - **Thawing Potion**

<!-- -->

- **DD-574/575/576**  
  Removed the following invalid options from the radiation poisoning treatment browser:

  - **RadAway**
  - **RadX**
  - **First Aid Spray**
  - **Mixed Herb**
  - **Golden Oriole**
  - **Mekansm**
  - **Cure Disease Potion**

<!-- -->
---

### **PRESCRIPTION VALIDATION ISSUES**

- **DD-525**  
  Fixed an issue where selecting **Vicodin** as an **Aspirin** alternative bypassed restrictions and diagnostic checks.

<!-- -->

- **DD-526**  
  Corrected a rare bug allowing **Schedule II narcotics** for **rhinovirus** diagnoses.

<!-- -->

- **DD-535**  
  Fixed an issue allowing prescription of 100,000 **pseudoephedrine** tablets for **rhinovirus**.

<!-- -->

- **DD-577**  
  Fixed an issue preventing **Patient Profile** saves when the patient had a diagnosis of **Lupus**. Also corrected the error handling that prevented the error message **It's never Lupus** from displaying after an unsuccessful save.

<!-- -->

---
### **PERFORMANCE ISSUES**

- **DD-562/563**  
  Fixed intermittent stuttering when retrieving and loading information from the database.

<!-- -->

## **SEE ALSO**
---
- [**Access the Help Files**](/daleydose/help-files)
- [**Version History**](/daleydose/release-note-version-history)

<div style="height: 60px;"></div>
