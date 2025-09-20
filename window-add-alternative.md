---
title: "Daley Dose - Add Alternative"
description: ""
layout: default
---
# **ADD ALTERNATIVE WINDOW**

In the **Add Alternative** window, you can add an alternative option for the pharmacy in case the prescribed medication is not available.  

To view this window: **Home** > Select the medication you want to add an alternative option for > **Alt +**
  
![Daley Dose user interface alternative meds button](/assets/images/daley-dose-home-window-parts-alt.png)

## **NOTES**
---
- Your device must be connected to the internet to add medications. The Daley Dose database cross‑checks the entered patient’s diagnoses with the medications you are allowed to prescribe.  
- The application prevents you from adding alternative medication when the prescription is empty.  
- You cannot set the same medication as its alternative option.  
- The application auto‑completes generic and brand name suggestions for each medication by default. You can turn off this feature in the options.  

## **RELATED TOPICS**
---
- You must have the **Prescriber** role to view this window.  
  + See [**User Roles**](/daleydose/about-user-roles) for more information.  
- An **Administrator** or **Support** user can impose or remove a prescription restriction on a **Prescriber**.  
  + See [**Prescription Restrictions**](/daleydose/about-prescription-restrictions) for more information.

## **INTERFACE DETAILS**
---
![Daley Dose Add Alternative Window](/assets/images/daley-dose-add-alts-window.png)

The following table describes the fields in the **Add Alternative** window:

| **FIELD** | **DEFINITION** |
|-----------|----------------|
| **CURRENT** | Displays the selected medication for which you will create an alternative option.<br><br>**NOTE:** This is a read‑only field. |
| **GENERIC NAME** | Enter the medication’s generic name. |
| **BRAND NAME** | Enter the medication’s brand name.<br><br>**NOTES:**<br>– This field is optional.<br>– When you enter a brand name while the **Generic name** field is empty, the application automatically lists the entered brand name’s generic version in that field. |
| **DOSE** | Enter the medication’s dosage.<br><br>**NOTE:** The application disables this field when the entered medication does not come with dosage instructions. |
| **UNIT** | Displays the most common unit of measurement for the entered medication.<br><br>**NOTE:** This is a read‑only field. The application disables this field when the entered medication does not come with dosage instructions. |
| **AMOUNT** | Enter the medication quantity for the prescription. |
| **AUTO‑COMPLETE STATUS** | Displays whether the generic and brand name auto‑complete function is enabled. This is enabled by default. You can turn off this feature in the options.<br><br>**Status:**<br>– **Green:** The option is turned on.<br>– **Red:** The option is turned off.<br>– **Purple:** The option is turned off for all accounts by an **Administrator** or the owner of the corporate account. |

The following table describes the buttons in the **Add Alternative** window:

| **BUTTON** | **DEFINITION** |
|------------|----------------|
| **CANCEL** | Select to close the **Add Alternative** window without adding the currently entered information to the prescription.<br><br>**NOTE:** When you select this button, the application displays the confirmation message **"Are you sure you want to close this window without adding the medication?"** before closing. |
| **SAVE** | Select to close the **Add Alternative** window and add the currently entered information to the prescription.<br><br>**NOTE:** The application disables this button when at least one of the following fields is empty: **Generic name**, **Dose**, or **Amount**. |

## **SEE ALSO**
---
- [**Home Window**](/daleydose/window-home)
- [**How to add medications to a prescription**](/daleydose/prescription-add-meds)  
- [**How to delete medications from a prescription**](/daleydose/prescription-delete-meds) 
