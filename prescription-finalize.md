---
title: "Daley Dose - Finalize Prescription"
description: ""
layout: default
---

# **FINALIZE A PRESCRIPTION**  
---
![Finalize buttons](/assets/images/daley-dose-home-window-parts-finalize.png)

The **Generate** section of the **Action Sidebar** include the **Add Medical Signature**, **Print Copy**, and **Send Online** buttons. As a safety measure when dealing with medical prescriptions, these three buttons are disabled by the application until you have finalized your work.

After adding medications and notes to the prescription, select the **Finalize** button to lock the prescription entries in place and prepare the prescription for printing or online sending.

The application disables the **Finalize** button when there are errors in the current prescription. The application highlights fields with errors in red. You can also see an error message indicating the nature of the error on the same line as its source. You must resolve these issues or delete the associated entries before you can finalize your work.

![Main Screen with Errors](/assets/images/daley-dose-home-window-error.png)

## **ADD MEDICAL SIGNATURE**
---
The **Add Medical Signature** button adds the prescriber's professional information to the prescription. This includes their Medical License number, complete name, office address, contact information, and official digital signature. The application also adds the Daley Dose stamp of clearance on the Medical Signature, indicating that the application has checked, approved, and finalized the digital prescription on behalf of the prescriber.

To add a medical signature, select the **Medical Signature** button on a finalized prescription. Once you have added your medical signature, you can either print the prescription locally for a physical copy, or send the prescription online using the **Print Copy** and **Send Online** buttons, respectively.

### **NOTES**
---
   - This is a required field for finalization.  
   - You must have a medical signature template saved in your profile to use this functionality.
   - The application uses information saved in your profile when adding the medical signature. Make sure you update these regularly to prevent outdated information from being added into your prescriptions.
 
## **PRINT COPY**
---
The Print Copy button enables you to print the finalized prescription locally. This option is more useful on a clinic or office setting, where the patient can get the prescription printed out after a consultation. The downside for this option is that the pharmacy may run out of stock of the prescribed medication from the time you printed it until the patient arrives at a pharmacy branch. This would create conflicts and may prevent the patient from getting medication until a later date or a represcription with a different medication. This issue can be avoided by adding an alternative option during the prescription process.

See [**How to add alternatives to medication entries**(/daleydose/prescription-add-alts) topic for more information.

### **NOTES**
---
– This option is available only on devices with a confirmed connection to a printer.
– This feature is not available on the Daley Dose mobile app.

## **SEND ONLINE**
---

Finalize the prescription.  
   - Select **Send** to send the current prescription’s information to the Daley Database.  
   - The application sends the prescription to the patient via a secure, one-time-use QR code. The patient can use this QR code to fill the prescription at a partner pharmacy.  
   - Select **Print** to use a local printer connected to your device and create a hard copy of the patient’s prescription.

## **PROBLEMS YOU MIGHT ENCOUNTER**
---

### The application prevents you from selecting the **+ MD Sig** button  
- **REASON:** The application does not have your saved digital signature.  
- **SOLUTION:** Ensure that you have completed entering information in the **Medical Signature** panel on the **Profile** window.

### The application prevents you from selecting the **Send** button  
- **REASON 1:** The application does not have access to the internet.  
- **SOLUTION 1:** Ensure that your device is currently connected to the internet.  
- **REASON 2:** The application is still checking the Daley Database for confirmation.  
- **SOLUTION 2:** Wait a few minutes and try again. The application needs to confirm the patient name, diagnosis, and prescribed medications before finalizing.

### Error message: **"Patient Mobile Not Found"**  
- **REASON:** The patient has a saved profile on the Daley Database, but their phone cannot be contacted.  
- **SOLUTION:** Ensure that the patient’s mobile device has an internet connection. The application needs a solid connection to send the QR code that the patient can use to refill the prescription.

### Error message: **"Unable to Contact Servers"**  
- **REASON:** The application cannot process your request because it needs to consult the Daley Database.  
- **SOLUTION:** Ensure that the internet connection remains consistent throughout the process and try again.

## **SEE ALSO**
---
- [**How to create a new prescription**](/daleydose/prescription-create-new)  
