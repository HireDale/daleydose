---
title: "Daley Dose - Version 1.5"
description: ""
layout: default
---

# **DALEY DOSE VERSION 1.5 RELEASE NOTES**
---
**RELEASE DATE**: 2025-09-12

This document provides an overview of the changes introduced in version 1.5 of the **Daley Dose** application.

This release includes a major overhaul of the application's user interface and functionality, alongside updates to the medication database, cloud coverage, and prescription management features. The following release notes summarize the new features, enhancements, and bug fixes delivered in this version.

![Daily Dose user interface](/assets/images/featured-updates-v1-5-2.png)

## **NEW FEATURES**
---
The following features were introduced in version 1.5 of the Daley Dose application:

---

### Redesigned Application Interface

**Purpose**

To provide users with a redesigned interface that improves navigation and enables faster access to commonly used tools and patient records.

**Changes**

- Introduced the **Information** and **Action** sidebars for easier access to application tools.
- Added the **Undo**, **Redo**, **Save**, **Clear**, **Help**, **Delete**, **Refresh**, **MIMS**, and **Finalize** buttons.
- Added the **Drug History** and **Med History** tabs for quick access to patient prescription and medication records.

**Reference Numbers**

DD-536/537/538/539/540/542/545

---
<!-- -->

![Daily Dose user interface](/assets/images/featured-updates-v1-5.png)

## **ENHANCEMENTS**
---
The following enhancements were introduced in version 1.5 of the Daley Dose application:

### Desktop Application Interface

**Purpose**

To improve the application's usability on desktop devices and transition toward a browser-based application.

**Change**

Rebuilt the entire interface for desktop use, moving toward a browser-based application.

**Reference Numbers**

DD-541

### Prescription Creation

**Purpose**

To streamline prescription creation by providing direct access to medication and note entry within the Prescription tab.

**Change**

Moved the **Add Medication** and **Add Note** buttons from the sidebar to the **Prescription** tab for faster prescription creation.

**Reference Numbers**

DD-543/544

### Patient and Medical History Information

**Purpose**

To improve access to patient and doctor information while providing a more organized workspace for prescription and medical history management.

**Changes**

- Moved the **Patient**, **Doctor**, and **Prescription Date** fields to the **Information** sidebar.
- Updated the work area to provide direct access to both **Prescription** and **Medical History**.
- Renamed the **Prescription Pad** area to the **Prescription** tab.

**Reference Numbers**

DD-546/547/548

### Patient Name Fields

**Purpose**

To standardize patient and doctor name entry by using separate first and last name fields.

**Change**

Split the **Patient Name** field into **First Name** and **Last Name** fields to match the **Doctor** field format.

**Reference Numbers**

DD-549

### Alternative and Medical Signature Actions

**Purpose**

To centralize alternative medication and medical signature actions within the **Action** sidebar.

**Change**

Moved the **Add Alternative** and **Add Medical Signature** buttons to the **Action** sidebar.

**Reference Numbers**

DD-551/552

### Document and Prescription Actions

**Purpose**

To consolidate document and prescription-related actions within the **Action** sidebar for easier access.

**Change**

Moved the **Create New**, **Scan**, **Send**, and **Print** buttons to the **Action** sidebar.

**Reference Numbers**

DD-554

### Scan and Send Button Labels

**Purpose**

To clarify the functions of the Scan and Send actions through more descriptive button labels.

**Change**

Renamed **Scan** to **Scan Physical Copy** and **Send** to **Send Online** for clarity.

**Reference Numbers**

DD-555/556

## **BUG FIXES**
---
The following bugs and issues were addressed in version 1.5 of the Daley Dose application:

- **DD-525**  
  Fixed an issue where adding Vicodin as an alternative bypassed restrictions and diagnostic checks.

- **DD-526**  
  Corrected a rare bug allowing Schedule II narcotics for rhinovirus diagnoses.

- **DD-529**  
  Removed incorrect recommendation of Garlic Bread as a prophylactic antibiotic.

- **DD-530**  
  Corrected classification of Coffee as an FDA-approved cardiac stimulant.

- **DD-533**  
  - Removed invalid prescription option for Narcan as a cure for World of Warcraft addiction.
  - Removed **World of Warcraft** from the available **Addiction Category** options.

<!-- -->

- **DD-535**  
  Fixed an issue allowing prescription of 100,000 pseudoephedrine tablets for rhinovirus.

- **DD-557/558/559/560/561**  
  Removed the following diseases and conditions from the list of accepted medical conditions:
  - Ataxia
  - Black Heart Blight
  - Bone Break Fever
  - Brain Rot
  - Droops
  - Rattles
  - Rockjoint
  - Sanguinare Vampiris
  - Witbane
  - Lycanthropy

<!-- -->

## **SEE ALSO**
---
- [**Access the Help Files**](/daleydose/help-files)
- [**Version History**](/daleydose/release-note-version-history)
