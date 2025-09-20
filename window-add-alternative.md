---
title: "Daley Dose - Add Alternative"
description: ""
layout: default
---
# **ADD ALTERNATIVE WINDOW**

In the **Add Alternative** window, you can add an alternative option for the pharmacy in case the prescribed medication is not available.  

To view this window: **Prescription** tab > Select the medication you want to add an alternative option for > **Add Alternative** (**Alt +**)
  
![Daley Dose user interface alternative meds button](/assets/images/daley-dose-home-window-parts-alt.png)

## **NOTES**
---
- Your device must be connected to the internet to add medications. The Daley Dose database cross‑checks the entered patient’s diagnoses with the medications you are allowed to prescribe.  
- The application prevents you from adding alternative medication when the prescription is empty.  
- You cannot set the same medication as its alternative option.  
- The application auto‑completes generic and brand name suggestions for each medication by default. You can turn off this feature in the options.  

## **RELATED TOPICS**
---
- You must have the **Prescriber** role to view this window. See [**User Roles**](/daleydose/about-user-roles) for more information.  
- An **Administrator** or **Support** user can impose or remove a prescription restriction on a **Prescriber**. See [**Prescription Restrictions**](/daleydose/about-prescription-restrictions) for more information.

## **INTERFACE DETAILS**
---
![Daley Dose Add Alternative Window](/assets/images/daley-dose-add-alts-window.png)

The following table describes the fields in the **Add Alternative** window:

| **FIELD** | **DEFINITION** |
|-----------|----------------|
| **GENERIC NAME** | Enter the medication’s generic name. |
| **BRAND NAME** | Enter the medication’s brand name.<br><br>**NOTES:**<br>– This field is optional.<br>– When you enter a brand name while the **Generic Name** field is empty, the application automatically lists the entered brand name’s generic version in that field. |
| **DOSE** | Enter the medication’s dosage.<br><br>**NOTE:** The application disables this field when the entered medication does not include dosage instructions. |
| **UNIT** | Displays the most common unit of measurement for the entered medication.<br><br>**NOTE:** This is a read‑only field. The application disables this field when the entered medication does not include dosage instructions. |
| **AMOUNT** | Enter the medication quantity for the prescription. |

The following table describes the buttons available in the **Add Alternative** window:

| **BUTTON**         | **DEFINITION** |
|--------------------|----------------|
| **AUTO‑COMPLETE**  | Select to enable or disable the auto‑complete feature when entering medication names. **Green** indicates the feature is enabled; **red** indicates it is disabled. |
| **CANCEL**         | Select to close the **Add Medication** window without adding the entered information to the prescription.<br><br>**NOTE:** When selected, the application displays the confirmation message **"Are you sure you want to close this window without adding the medication?"** before closing. |
| **OK**             | Select to close the **Add Alternative** window and add the entered information to the prescription.<br><br>**NOTE:** This button is disabled if any of the following fields are empty: **Generic Name**, **Dose**, or **Amount**. |

## **SEE ALSO**
---
- [**How to add medications to a prescription**](/daleydose/prescription-add-meds)  
- [**How to delete medications from a prescription**](/daleydose/prescription-delete-meds) 
