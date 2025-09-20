---
title: "Daley Dose - Add Medication"
description: ""
layout: default
---

# **ADD MEDICATION WINDOW**
In the **Add Medication** window, you can add medication to the patient’s current prescription.

To view this window: **Prescription** tab > **Add Medication** (green **Plus** button) 

![Daley Dose user interface screenshot](/assets/images/daley-dose-home-window-parts-add-meds.png)

## **NOTES**
---
- Your device must be connected to the internet to add medications. The Daley Dose database cross‑checks the entered patient’s diagnoses with the medications you are allowed to prescribe.  
- The application prevents you from adding medication when the **Patient Name** fields are empty.  
- You can add up to 5 medications per prescription.  
- The application auto‑completes generic and brand name suggestions for each medication by default. You can permanently turn off this feature in the options.

## **RELATED TOPICS**
---
- You must have the **Prescriber** role to view this window.  
  + See [**User Roles**](/daleydose/about-user-roles) for more information.  
- An **Administrator** or **Support** user can impose or remove a **Prescription Restriction** on a **Prescriber**.  
  + See [**Prescription Restrictions**](/daleydose/about-prescription-restrictions) for more information.

![Daley Dose user interface screenshot](/assets/images/daley-dose-add-medication-window.png)

## **INTERFACE DETAILS**
---
The following table describes the fields available in the **Add Medication** window:

| **FIELD** | **DEFINITION** |
|-----------|----------------|
| **GENERIC NAME** | Enter the medication’s generic name. |
| **BRAND NAME** | Enter the medication’s brand name.<br><br>**NOTES:**<br>– This field is optional.<br>– When you enter a brand name while the **Generic name** field is empty, the application automatically lists the entered brand name’s generic version in that field. |
| **DOSE** | Enter the medication’s dosage.<br><br>**NOTE:** The application disables this field when the entered medication does not include dosage instructions. |
| **UNIT** | Displays the most common unit of measurement for the entered medication.<br><br>**NOTE:** This is a read‑only field. The application disables this field when the entered medication does not include dosage instructions. |
| **AMOUNT** | Enter the medication quantity for the prescription. |

The following table describes the buttons available in the **Add Medication** window:

| **BUTTON**         | **DEFINITION** |
|--------------------|----------------|
| **AUTO‑COMPLETE**  | Select to enable or disable the auto‑complete feature when entering medication names. **Green** indicates the feature is enabled; **red** indicates it is disabled. |
| **CANCEL**         | Select to close the **Add Medication** window without adding the entered information to the prescription.<br><br>**NOTE:** When selected, the application displays the confirmation message **"Are you sure you want to close this window without adding the medication?"** before closing. |
| **OK**             | Select to close the **Add Medication** window and add the entered information to the prescription.<br><br>**NOTE:** This button is disabled if any of the following fields are empty: **Generic name**, **Dose**, or **Amount**. |

## **SEE ALSO**
---
- [**How to add medications to a prescription**](/daleydose/prescription-add-meds)  
- [**How to delete medications from a prescription**](/daleydose/prescription-delete-meds) 
- [**How to add, edit, and delete medication notes**](/daleydose/prescription-manage)  
