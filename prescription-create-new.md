---
title: ""
description: ""
layout: default
---

# **CREATE A NEW PRESCRIPTION**
---

To create a new prescription, follow these steps:

1. On the **Home** window, select **Create New**.  
   - Creating a new prescription erases all current work loaded on the window. Make sure to **Send** or **Print** any ongoing prescriptions before you continue.  
   - If there are items on the current prescription, the application displays the confirmation message **"Are you sure you want to erase the current prescription?"** The application erases all populated fields when you select **Yes**.

2. Enter the patient’s complete name in the **Patient Name** field.  
   - The application displays the patient’s name in [LAST, FIRST, MIDDLE] format.  
   - The application automatically formats the name after confirming with the Daley Database.  
   - You cannot add medications or notes when this field is empty.

3. Enter the issue date in the **Prescription Date** field.  
   - The application displays this in [MM/DD/YYYY] format.  
   - If this field is empty when you finalize the prescription, the application fills it with the current date.

4. (Optional) Enter the expected refill date in the **Refill Date** field.  
   - This step is optional.

## Problems you might encounter  
---

### No response when selecting the **Create New** button  
- **REASON:** Only users with the **Prescriber** role can create prescriptions.  
- **SOLUTION:** Check whether you have the correct role. To request a role change, contact **Support** or an **Administrator**.

### Error message when entering a patient’s name: **"Patient Unrecognized"**  
- **REASON:** The application does not recognize the name entered in the **Patient Name** field.  
- **SOLUTION:** Ensure that the patient’s profile on the Daley Dose website is up to date. The application requires a matching patient profile before you can prescribe medication.

### Error message when entering a date: **"Unable to Time Travel"**  
- **REASON:** The entered date is set before today’s date.  
- **SOLUTION:** Ensure that the entered prescription date or refill date is not set before today’s date.

### Error message while working: **"Unable to Contact Servers"**  
- **REASON:** The application cannot process your request because it needs to consult the Daley Dose Database.  
- **SOLUTION:** Ensure that the internet connection remains consistent throughout the process and try again.
