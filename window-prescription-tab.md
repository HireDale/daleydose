---
title: "Daley Dose - Prescription Tab"
description: ""
layout: default
---

# **PRESCRIPTION TAB**
---
The **Prescription** tab is the primary workspace for creating and managing prescriptions. This tab enables you to add medications, attach notes, and finalize the prescription for printing or online sending.

Each prescription can include up to 5 medications. This limit ensures accuracy and compliance with dispensing regulations, especially when prescriptions are processed across multiple pharmacies or remote setups.

The **Prescription** tab is one of three tabs featured in the **Work Area** of the Daley Dose application, alongside the [**Drug History**](/daleydose/window-drug-history-tab) and [**Med History**](/daleydose/window-med-history-tab) tabs.

## **RELATED TOPICS**
---
You can learn more about this tab in the [**How to create a new prescription**](/daleydose/prescription-create-new) topic.

## **INTERFACE DETAILS**
---

![Daily Dose Prescription Tab](/assets/images/daley-dose-home-window-tab-1-labels.png)

The following table describes the fields in the **Prescription** tab.

| **FIELDS**         | **DEFINITION** |
|--------------------|----------------|
| **SEQUENCE NUMBER** | Displays the sequence of entries.<br><br>**NOTES:**<br>- You can have up to 5 medications per prescription.<br>- You can have up to 5 notes per medication. |
| **MEDICATION**      | Displays the medication name and dose.<br><br>**NOTE:** This is a read-only field. To edit the contents of a **Medication** field, double-click the desired medication to re-open the [**Add Medication** window](/daleydose/window-add-medication). |
| **QUANTITY**        | Displays the quantity associated with the medication for the prescription. |
| **NOTE**            | Displays the note associated with the medication.<br><br>**NOTE:** This is a read-only field. To edit the contents of a **Note** field, double-click the desired medication to re-open the [**Add Note** window](/daleydose/window-add-notes). |
| **ERROR**           | Displays one of the following error messages for the associated medication entry:<br><br>- **INSUFF STOCK:** Indicates that the pharmacies associated with the patient or hospital do not have the entered quantity of the medication in stock.<br>- **DOSAGE ERROR:** Indicates that the entered dose is inconsistent with medical protocols.<br>- **RESTRICTED:** Indicates that the medication entry cannot be prescribed by the user because of their current [**Prescription Restrictions**](/daleydose/about-prescription-restrictions). |
| **ERROR INDICATOR** | Identifies the reason for the error message. The application highlights the affected field in red.<br><br>Existing fields identified as causing errors prevent you from finalizing the prescription. |

The following table describes the buttons in the **Prescription** tab.

| **BUTTONS**        | **DEFINITION** |
|--------------------|----------------|
| **ADD MEDICATION** | Select to add a medication entry to the current prescription.<br><br>When selected, the application opens the [**Add Medication** window](/daleydose/window-add-medication). |
| **ADD NOTE**       | Select to add a note entry to the selected medication.<br><br>When selected, the application opens the [**Add Notes** window](/daleydose/window-add-notes). |

### **DRUG HISTORY**
---
The **Drug History** tab enables you to check the current patient’s history of prescribed medication. The Daley Dose application syncs with the online database to provide the latest updates (within 1 hour) on the patient’s digital records.  

This tab is useful when checking for previous prescriptions from other doctors or hospitals. This includes local, national, and international records, as long as the previous prescribers used the Daley Dose application.  

Because the **Drug History** tab syncs with the database each time you view it, the application requires an internet connection to use this functionality. The loading time of the information also depends on the current internet speed.

### **MED HISTORY**
---
The **Med History** tab enables you to check the current patient’s history of medical conditions and treatments. The application divides this tab into two sections: **Current Status** and **Medical Records**.  

The **Current Status** section displays information about the patient’s ongoing or most recent medical issue. This enables prescribers to access quick context about the patient’s current prescription needs.  

The **Medical Records** section provides a detailed list of the patient’s medical conditions and treatments, going back up to 20 years. If earlier records have been digitized and uploaded to the database, the Daley Dose application can also provide that information.  

Because the **Med History** tab syncs with the database each time you view it, the application requires an internet connection to use this functionality. The loading time of the information also depends on the current internet speed.

## **SEE ALSO**
---
- [**How to create a new prescription**](/daleydose/prescription-create-new)  
- [**How to add medications to a prescription**](/daleydose/prescription-add-meds)
- [**How to add alternatives to medication entries**](/daleydose/prescription-add-alts)  
- [**How to delete medications from a prescription**](/daleydose/prescription-delete-meds)  
- [**How to add, edit, and delete medication notes**](/daleydose/prescription-manage)  
- [**How to finalize and send out a prescription**](/daleydose/prescription-finalize)  
- [**How to digitize a handwritten prescription**](/daleydose/prescription-digitize)
