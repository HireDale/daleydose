---
title: ""
description: ""
layout: default
---

# **ADD MEDICATION TO A PRESCRIPTION**
---

To add medications to a prescription, follow these steps:

1. Select the **+ Meds** button on the left toolbar to add medication.

2. Enter either the generic or brand name of the medication in their respective fields.  
   - The **Generic Name** field is mandatory, while the **Brand Name** field is optional.

3. If you enter a brand name while the **Generic Name** field is empty, the application automatically lists the brand name’s generic version in that field.  
   - The application auto-completes generic and brand name suggestions for each medication.  
   - You can turn off this feature in the **Options** window.

4. Enter the medication dosage.

5. Enter the amount of medication you want to prescribe.

6. Select **Save**.  
   - The application disables the **Save** button when at least one of the following fields is empty: **Generic Name**, **Dose**, or **Amount**.

## **PROBLEMS YOU MIGHT ENCOUNTER**  
---

### The application prevents you from selecting the **+ Meds** button  
- **REASON:** The application disables the **+ Meds** button when the **Patient Name** field is empty, the device has no internet connection, the current prescription already has 5 medications, or the user does not have a **Prescriber** role.  
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
- [**Table of Contents**](/daleydose/help-files)
- [**Add Medication Window**](/daleydose/window-add-medication)  
- [**Add Alternative Window**](/daleydose/window-add-alternative)  
- [**How to create a new prescription**](/daleydose/prescription-create-new)  
- [**How to delete medications from a prescription**](/daleydose/prescription-delete-meds) 
