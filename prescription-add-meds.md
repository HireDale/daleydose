---
title: "Daley Dose - Add Medication"
description: ""
layout: default
---

# **ADD MEDICATION TO A PRESCRIPTION**
---

![Daley Dose user interface screenshot](/assets/images/daley-dose-home-window-parts-add-meds.png)

To add medication to the current prescription, follow these steps:

1. Select the **Add Medication** button (green **Plus**) on the **Prescription** tab to view the [**Add Medication** window](/daleydose/window-add-medication).

2. In the **Add Medication** window, enter either the generic or brand name of the medication in their respective fields.  
   - The **Generic Name** field is mandatory, while the **Brand Name** field is optional.

3. If you enter a brand name while the **Generic Name** field is empty, the application automatically lists the brand name’s generic version in that field.  
   - The application auto-completes generic and brand name suggestions for each medication.  
   - You can turn off this feature in the options.

4. Enter the medication dosage.

5. Enter the amount of medication you want to prescribe.

6. Select **Add to List**.

7. Select **OK**.  
   - The application disables the **OK** button when at least one of the following fields is empty: **Generic Name**, **Dose**, or **Amount**.

![Daley Dose user interface screenshot](/assets/images/daley-dose-add-medication-window.png)

## **PROBLEMS YOU MIGHT ENCOUNTER**  
---

### The application prevents you from selecting the **Add Medication** button  
- **REASON:** The application disables the **Add Medication** button when the **Patient Name** fields are empty, the device has no internet connection, the current prescription already has 5 medications, or the user does not have a **Prescriber** role.  
- **SOLUTION:** Check whether any of the above conditions apply, and then try again.

### Error message when entering medication name: **"Medication Incompatible with Patient"**  
- **REASON:** The patient’s profile does not match the medication you are trying to prescribe.  
- **SOLUTION:** Ensure that the patient’s profile on the Daley Dose website is up to date. The application requires appropriate diagnoses to authorize the prescription of specific medications.

### Error message when entering medication name: **"Medication Unknown"**  
- **REASON:** The medication name you are trying to add does not exist in the Daley Database.  
- **SOLUTION:** Ensure that the generic or brand name is correct. With the auto-complete feature, make sure at least the first 3 letters of the medication are correct.

### Error message: **"Unable to Contact Servers"**  
- **REASON:** The application cannot process your request because it needs to consult the Daley Database.  
- **SOLUTION:** Ensure that the internet connection remains consistent throughout the process and try again.

## **SEE ALSO**
---
- [**How to add alternatives to medication entries**](/daleydose/prescription-add-alts)  
- [**How to delete medications from a prescription**](/daleydose/prescription-delete-meds) 
- [**How to add, edit, and delete medication notes**](/daleydose/prescription-manage)  
- [**How to finalize and send out a prescription**](/daleydose/prescription-finalize)
