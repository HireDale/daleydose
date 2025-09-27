---
title: "Daley Dose - Create Prescription"
description: ""
layout: default
---

# **CREATE A NEW PRESCRIPTION**
---
The Daley Dose application's main feature is the ability to create **digital prescriptions**. By using a secure, well-equipped application, prescribers around the world can maintain the highest standard of care for their patients.

![Daley Dose user interface create new](/assets/images/daley-dose-home-window-parts-create-new.png)

To create a new prescription, follow these steps:

1. Verify that the **Prescriber** fields are correct on the **Information Sidebar**.  

   The **Prescriber** fields are read‑only. The information displayed depends on the currently active user profile.

   An incorrect Prescriber name indicates that you are logged into the wrong account. Log out, then log back in using your credentials to continue.  
   
3. On the **Action Sidebar**, select **Create New**.  

   Creating a new prescription erases all current work loaded on the **Prescription** tab.

   Save, send, or print any ongoing prescriptions before continuing.

   If there are items on the current prescription, the application displays the confirmation message **"Are you sure you want to erase the current prescription?"**. The application erases all populated fields when you select **Yes**.  
   
5. Enter the patient’s information in the **Patient Name** fields.  

   Entering a **Patient Last Name** restricts **Patient First Name** options to those with an existing record in the database.  
   
7. Enter the issue date in the **Prescription Date** field.  

   If this field is empty when you finalize the prescription, the application fills it with the current date.  
   
9. (Optional) Enter the expected refill date in the **Refill Date** field.  
   
10. Add medications and notes. You can add up to 5 medications per prescription.  

   See [**How to add medications to a prescription**](/daleydose/prescription-add-meds) for more information.  
   
11. Finalize your work. From here, you can either print the prescription or send it to the database for processing.  

   See [**How to finalize and send out a prescription**](/daleydose/prescription-finalize) for more information.  

## **NOTES**
---
-  The application prevents adding medications and notes when the **Patient Name** fields are empty.
-  The application displays dates in [MM/DD/YYYY] format.

## **PROBLEMS YOU MIGHT ENCOUNTER**
---

### No response when selecting the **Create New** button  
- **REASON:** Only users with the **Prescriber** role can create prescriptions.  
- **SOLUTION:** Check whether you have the correct role. To request a role change, contact **Support** or an **Administrator**.

### Error message when entering a patient’s name: **"Patient Unrecognized"**  
- **REASON:** The application does not recognize the name entered in the **Patient Name** fields.  
- **SOLUTION:** Ensure that the patient’s profile on the **Daley Dose** website is up to date. The application requires a matching patient profile before you can prescribe medication.

### Error message when entering a date: **"Unable to Time Travel"**  
- **REASON:** The entered date is set before today’s date.  
- **SOLUTION:** Ensure that the entered prescription date or refill date is not set before today’s date.

### Error message while working: **"Unable to Contact Servers"**  
- **REASON:** The application cannot process your request because it needs to consult the **Daley Dose** database.  
- **SOLUTION:** Ensure that the internet connection remains consistent throughout the process, then try again.

## **SEE ALSO**
---
- [**How to add medications to a prescription**](/daleydose/prescription-add-meds)
- [**How to add alternatives to medication entries**](/daleydose/prescription-add-alts)  
- [**How to delete medications from a prescription**](/daleydose/prescription-delete-meds) 
- [**How to add, edit, and delete medication notes**](/daleydose/prescription-manage)  
- [**How to digitize a handwritten prescription**](/daleydose/prescription-digitize)
- [**How to finalize and send out a prescription**](/daleydose/prescription-finalize)
