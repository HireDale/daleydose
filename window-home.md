---
title: Daley Dose - Home Window
description: ""
layout: default
---

# **HOME WINDOW**
---
The **Home** window appears when you start the **Daley Dose** application. 

By default, it opens with the last saved instance of a previous prescription (if any), allowing you to continue where you left off. You can disable this feature in the options.

Here, you can create medical prescriptions for your patients. Each prescription can include up to 5 medications. You can also scan physical prescriptions and convert them into a digital version.

![Daily Dose user interface](/assets/images/daley-dose-home-window-error.png)

## **NOTES**
---
- Access to the **Daley Dose** application requires an active subscription.  
- Your device must be connected to the internet to send digital prescriptions.

## **RELATED TOPICS**
---
- You must have a **Prescriber** role to create prescriptions.  
  + See [**User Roles**](/daleydose/about-user-roles) for more information.  
- An **Administrator** or **Support** user can impose or remove a prescription restriction on a **Prescriber**.  
  + See [**Prescription Restrictions**](/daleydose/about-prescription-restrictions) for more information.  

## **INTERFACE DETAILS**
---

The **Home** window is composed of the **Title Section**, **Profile Section**, **Work Area**, **Information Sidebar**, and **Action Sidebar**.  

Most of the interface remains the same throughout the prescription‑making process. Only the middle section, referred to as the **Work Area**, changes depending on the current window accessed.

## **TITLE SECTION**
---
The **Title Section** is located in the top‑left corner of the screen. 

It contains the **Daley Dose** name, logo, and version number.

![Daily Dose Title Section](/assets/images/daley-dose-home-window-section-1.png)

The following table describes the buttons in the **Title Section**:

| **BUTTONS**       | **DEFINITION** |
|-------------------|----------------|
| **DALEY DOSE ICON** | Select the **Daley Dose** icon to view the **System Information** pop‑up window.<br><br>The application displays detailed information about the program, including its complete version number, release date, and a list of developer notes added in the build. |


## **PROFILE SECTION**
---
The **Profile Section** is located in the top‑right corner of the screen.

You can view your profile information and access in‑app settings here. This section also displays a greeting during an active session, showing the current active **Prescriber** and their system‑assigned ID.  

![Daily Dose Profile Section](/assets/images/daley-dose-home-window-section-2.png)

The following table describes the buttons in the **Profile Section**:

| **BUTTONS**     | **DEFINITION** |
|-----------------|----------------|
| **PROFILE ICON** | Select to view the **Profile Summary** pop‑up window.<br><br>The application displays detailed information about the user currently logged in, such as their professional license number, specialization, and any prescription restrictions, as well as their duration. |
| **PROFILE**      | Select to view the active profile’s information, role, prescription restrictions, form templates, and saved security settings.<br><br>When you select this button, the application opens the **Profile** window.<br>
| **OPTIONS**      | Select to view the application’s options. |

## **INFORMATION SIDEBAR**
---
The **Information Sidebar** is located on the left side of the screen.  

It displays details about the patient, the prescribing doctor, and the current prescription. You cannot add medications to the current prescription while these fields are empty.  

![Daily Dose Information Sidebar](/assets/images/daley-dose-home-window-section-3.png)

The following table describes the fields in the **Information Sidebar**:

| **FIELDS**              | **DEFINITION** |
|-------------------------|----------------|
| **PATIENT LAST NAME**   | Displays the patient’s last name. Select to enter or edit the current patient’s name.<br><br>**NOTES:**<br>– The application prevents adding medications and notes when the **Patient Name** fields are empty.<br>– Entering a **Patient Last Name** restricts options for **Patient First Names** to those with an existing record in the database. |
| **PATIENT FIRST NAME**  | Displays the patient’s first name. Select to enter or edit the current patient’s name. |
| **PRESCRIPTION DATE**   | Displays the prescription’s issue date. Select to enter or edit the current prescription date.<br><br>**NOTE:** The application displays the date in [MM/DD/YYYY] format. |
| **NEXT REFILL DATE**    | Displays the prescription’s scheduled refill date. Select to enter or edit the current scheduled refill date.<br><br>**NOTE:** The application displays the date in [MM/DD/YYYY] format. |
| **PRESCRIBER LAST NAME**| Displays the prescribing user’s last name.<br><br>**NOTE:** This is a read‑only field. The prescriber information is based on the current user logged into the application. |
| **PRESCRIBER FIRST NAME**| Displays the prescribing user’s first name.<br><br>**NOTE:** This is a read‑only field. The prescriber information is based on the current user logged into the application. |

## **ACTION SIDEBAR**
---
The **Action Sidebar** is located on the right side of the screen.  

It displays the buttons to create and manage prescriptions. These buttons are divided into three categories: **Utility**, **Main**, and **Generate**.

For simplicity, this guide presents the button definitions by category.

![Daily Dose Action Sidebar](/assets/images/daley-dose-home-window-section-4.png)

### **UTILITY**
---
The **Utility** buttons enable you to manage individual prescription entries and access in‑app references, including the help files and the latest *Monthly Index of Medical Specialities (MIMS)* edition.

![Daily Dose Action Sidebar: Utility](/assets/images/daley-dose-home-window-section-4-1.png)

The following table describes the **Utility** buttons in the **Action Sidebar**:

| **BUTTONS**   | **DEFINITION** |
|---------------|----------------|
| **UNDO**      | Select to undo the last action performed in the current prescription. |
| **SAVE**      | Select to save the current prescription. The application automatically displays the saved prescription the next time you log in. You can view a list of saved prescriptions using the **Open** button.<br><br>**NOTE:** Saved prescriptions are removed from the system. |
| **REDO**      | Select to redo the last action undone in the current prescription. |
| **CLEAR**     | Select to clear the current prescription entry’s contents. |
| **HELP**      | Select to access an in‑app version of the latest **Daley Dose Help Files**.<br><br>**NOTES:**<br>– The help files automatically open the entry about the current window.<br>– You can also view the latest version of the help files on the **Daley Dose** website. |
| **DELETE**    | Select to access **delete mode**, which displays checkboxes next to existing entries in the prescription. <br><br>**NOTE:** The application displays the confirmation message “**Are you sure you want to delete these from the prescription?**” before removing the selected entries from the list. |
| **REFRESH**   | Select to refresh the contents of the current session to match any saved instances or records in the database. This includes the contents of the patient's **Drug History** and **Medical History** tabs. |
| **MIMS**      | Select to access an in‑app version of the latest *Monthly Index of Medical Specialities (MIMS)* digital handbook, the most common drug reference for healthcare professionals.<br><br>**NOTE:** The **MIMS** version is updated along with every **Daley Dose** version. |
| **ALT+**      | Select to add an alternative option for the pharmacy if the prescribed medication is not available.<br><br>When you select this button, the application opens the **Add Alternative** window.<br><br>**NOTE:** The application auto‑completes generic and brand name suggestions for each medication. You can turn off this feature in the options. |

### **MAIN**
---
The **Main** buttons enable you to add, edit, or finalize prescriptions. The application disables the **Finalize** button if it detects an issue with any of the current prescription items.

![Daily Dose Action Sidebar: Main](/assets/images/daley-dose-home-window-section-4-2.png)

The following table describes the **Main** buttons in the **Action Sidebar**:

| **BUTTONS**         | **DEFINITION** |
|---------------------|----------------|
| **CREATE NEW**      | Select to create a new prescription.<br><br>When you select this button while there are items on the current prescription, the application displays the confirmation message “**Are you sure you want to erase the current prescription?**”<br><br>The application erases all populated fields when you select **Yes**. |
| **EDIT**            | Select to open and edit a previously saved prescription. |
| **SCAN PHYSICAL COPY** | Select to scan a handwritten prescription and create a digital version in a new prescription window.<br><br>When you select this button, the application opens the [**Scan** window](/daleydose/window-scan).<br><br>**NOTES:**<br>– The application displays this button on the desktop version only when your computer has a confirmed connected webcam.<br>– The application always displays this button on the mobile app. |
| **FINALIZE**        | Select to finalize the current prescription.<br><br>When you select this button, the application locks the contents of the current prescription and enables the **Add Medical Signature**, **Print Copy**, and **Send Online** buttons. |

### **GENERATE**
---
The **Generate** buttons enable you to sign, print, and send the current prescription. These buttons are locked by the system to prevent errors when issuing prescriptions.

To unlock the **Generate** buttons, you must first select the **Finalize** button.

![Daily Dose Action Sidebar: Generate](/assets/images/daley-dose-home-window-section-4-3.png)

The following table describes the **Generate** buttons in the **Action Sidebar**:

| **BUTTONS**              | **DEFINITION** |
|--------------------------|----------------|
| **ADD MEDICAL SIGNATURE**| Select to add your official medical signature to the prescription.<br><br>This field is required to finalize the prescription.<br><br>**NOTE:** You must have a medical signature template saved in the **Profile** window to use this functionality. |
| **PRINT COPY**           | Select to print the current prescription on a local printer.<br><br>**NOTES:**<br>– This option is available only on devices with a confirmed connection to a printer.<br>– This feature is not available on the **Daley Dose** mobile app. |
| **SEND ONLINE**          | Select to send the prescription to the **Daley Dose** database for deployment.<br><br>**NOTE:** The application displays the confirmation message “**Finalize and send out this prescription?**” before sending. |

## **WORK AREA**
---
The **Work Area** occupies the central section of the screen.

It contains three tabs that serve as the main tools for creating a prescription: **Prescription**, **Drug History**, and **Med History**.

![Daily Dose Work Area](/assets/images/daley-dose-home-window-section-5.png)

### **PRESCRIPTION**
---
You will be doing most of your work on the **Prescription** tab.  

This tab enables you to create prescriptions by adding medications and notes. Each prescription can have up to 5 medications to ensure accuracy and compliance with regulations during the drug dispensing process.  

You can learn more about this tab in the [**How to create a new prescription**](/daleydose/prescription-create-new) topic.

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
| **ADD MEDICATION** | Select to add a medication entry to the current prescription.<br><br>When selected, the application opens the **Add Medication** window. |
| **ADD NOTE**       | Select to add a note entry to the selected medication.<br><br>When selected, the application opens the **Add Note** window. |

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
- [**How to delete medications from a prescription**](/daleydose/prescription-delete-meds)  
- [**How to add, edit, and delete medication notes**](/daleydose/prescription-manage)  
- [**How to finalize and send out a prescription**](/daleydose/prescription-finalize)  
- [**How to digitize a handwritten prescription**](/daleydose/prescription-digitize)
