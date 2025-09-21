---
title: "Daley Dose - Add Medication"
description: ""
layout: default
---

# **ADD ALTERNATIVE TO A MEDICATION**
---

![Daley Dose Add Alternative](/assets/images/daley-dose-home-window-parts-alt.png)

To add an alternative option to a medication entry in the current prescription, follow these steps:

1. Select the medication entry you want to create an alternative for, then select the **Add Alternative** button (**Alt+**) on the **Prescription** tab to view the [**Add Alternative** window](/daleydose/window-add-alternative).

2. In the **Add Alternative** window, enter either the generic or brand name of the medication in their respective fields.
   - The **Generic Name** field is mandatory, while the **Brand Name** field is optional.
   - You cannot enter the original medication entry as its own alternative.

3. If you enter a brand name while the **Generic Name** field is empty, the application automatically lists the brand name’s generic version in that field.
   - The application auto-completes generic and brand name suggestions for each medication.
   - You can turn off this feature in the options.

4. Enter the medication dosage.

5. Enter the amount of medication you want to prescribe.

6. Select **OK**.
   - When the pharmacy runs out of the prescribed medication, the pharmacist can provide the alternative instead.
   - The application disables the **OK** button when at least one of the following fields is empty: **Generic Name**, **Dose**, or **Amount**.

![Daley Dose user interface screenshot](/assets/images/daley-dose-add-alts-window.png)

## **PROBLEMS YOU MIGHT ENCOUNTER**  
---

### Error message when entering medication name: **"Medication Unknown"**  
- **REASON:** The medication name you are trying to add does not exist in the Daley Database.  
- **SOLUTION:** Ensure that the generic or brand name is correct. With the auto-complete feature, make sure at least the first 3 letters of the medication are correct.

### Error message: **"Unable to Contact Servers"**  
- **REASON:** The application cannot process your request because it needs to consult the Daley Database.  
- **SOLUTION:** Ensure that the internet connection remains consistent throughout the process and try again.

## **SEE ALSO**
---
- [**How to create a new prescription**](/daleydose/prescription-create-new)
- [**How to add medications to a prescription**](/daleydose/prescription-add-meds)
- [**How to delete medications from a prescription**](/daleydose/prescription-delete-meds) 
