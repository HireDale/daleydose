---
layout: default
title: ""
description: ""
---

# **ADD MEDICATION WINDOW**
In the **Add Medication** window, you can add medication to the patient’s current prescription.

To view this window:  
- On a new prescription: **Home** > **Create new** > **+ Meds**  
- On an existing prescription: **Home** > **+ Meds**  

To learn more about the tasks you can perform in this window, see the **User Interface Guides** section.

## **NOTES**
---
- You must have the **Prescriber** role to view this window.  
- See [**About User Roles**](/daleydose/about-user-roles) for more information.  
- Your device must be connected to the internet to add medications. The Daley Dose database cross‑checks the entered patient’s diagnoses with the medications you are allowed to prescribe.  
- The application prevents you from adding medication when the **Patient Name** field is empty.  
- You can add up to 5 medications per prescription.  
- The application auto‑completes generic and brand name suggestions for each medication by default. You can turn off this feature in the **Options** window.  
- An **Administrator** or **Support** user can impose or remove a prescription restriction on a **Prescriber**.  
- See [**Prescription Restrictions**](/daleydose/about-prescription-restrictions) for more information.

The following table describes the fields available in the Daley Dose **Add Medication** window:

| **FIELD** | **DEFINITION** |
|-----------|----------------|
| **GENERIC NAME** | Enter the medication’s generic name. |
| **BRAND NAME** | Enter the medication’s brand name.<br><br>**NOTES:**<br>– This field is optional.<br>– When you enter a brand name while the **Generic name** field is empty, the application automatically lists the entered brand name’s generic version in that field. |
| **DOSE** | Enter the medication’s dosage.<br><br>**NOTE:** The application disables this field when the entered medication does not include dosage instructions. |
| **UNIT** | Displays the most common unit of measurement for the entered medication.<br><br>**NOTE:** This is a read‑only field. The application disables this field when the entered medication does not include dosage instructions. |
| **AMOUNT** | Enter the medication quantity for the prescription. |
| **AUTO‑COMPLETE STATUS** | Displays whether the generic and brand name auto‑complete function is enabled. This feature is enabled by default. You can turn off this feature in the **Options** window.<br><br>**STATUS:**<br>– Green: The option is turned on.<br>– Red: The option is turned off.<br>– Purple: The option is turned off for all accounts by an **Admin** or the owner of the corporate account. |

The following table describes the buttons available in the Daley Dose **Add Medication** window:

| **BUTTON** | **DEFINITION** |
|------------|----------------|
| **CANCEL** | Select **Cancel** to close the **Add Medication** window without adding the currently entered information to the prescription.<br><br>**NOTE:** When you select this button, the application displays the confirmation message **"Are you sure you want to close this window without adding the medication?"** before closing. |
| **SAVE** | Select **Save** to close the **Add Medication** window and add the currently entered information to the prescription.<br><br>**NOTE:** The application disables this button when at least one of the following fields is empty: **Generic name**, **Dose**, or **Amount**. |

## SEE ALSO
---
- **How to add medications to a prescription**
- **How to delete medications from a prescription**
