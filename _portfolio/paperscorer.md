---
layout: single
title: "PaperScorer How-To Guide: Scanning and Uploading Student Answer Sheets"
og_image: /assets/images/og-paperscorer.png
sequence: 1
---

(in progress)

<div class="notice">
  <p><strong>Project Brief</strong></p>
  <ul>
    <li><strong>Audience:</strong> Teachers using PaperScorer for grading (spec work).</li>
    <li><strong>User Goal:</strong> To scan and upload student answer sheets to the PaperScorer application.</li>
    <li><strong>Problem:</strong> The procedure is complex, and there are many failure points.</li>
    <li><strong>Scope:</strong> This guide covers a recommended method for scanning and uploading batches of sheets in detail and briefly mentions alternatives.</li>
    <li><strong>Key Considerations:</strong></li>
      <ul>
        <li>Guide is scoped to scanning and uploading assessments, not creating assessments, to avoid overwhelming the user.</li>
        <li>Alternative methods for scanning and uploading are mentioned but not described in detail to avoid overwhelming the user.</li>
        <li>Error states are discussed in detail to account for variance in how students complete sheets and problems in transitioning from a physical medium to a digital medium.</li>
      </ul>
    <li><strong>Success Criteria:</strong> Teachers can scan and upload sheets to PaperScorer in less than 20 minutes while correcting all errors.</li>
    <li><strong>Next Iteration:</strong> After evaluating user feedback, revise until 100% of pilot teachers meet the success criteria.</li>
  </ul>
</div>

## Sample

This how-to guide explains how to scan and upload student answer sheets to PaperScorer. Meant for non-technical users, this guide shows how to accomplish this task quickly and efficiently, leaving more time for grading.   

## Prerequisites
* An assessment created in PaperScorer and corresponding student answer sheets printed out. PaperScorer provides instructions for [creating an assessment](https://help.paperscorer.com/article/180-creating-an-assessment) and [printing out student answer sheets](https://help.paperscorer.com/article/149-printing-an-assessment-for-a-class). 
* A scanner/copier or a mobile phone with a camera. If using a mobile phone, download the PaperScorer app from the App Store (iOS) or Google Play (Android). A scanner/copier is recommended for large batches of sheets.  
* If using a scanner/copier, and the scanner/copier cannot email files directly, a USB drive is required to transfer the data.  

## Preparation
First, make sure the student answer sheets are ready to be scanned. 
* Ensure the student answer sheets are rotated the same way as each other. 
* Check for any folds and unfold any you find. 
* Check for stray markings, which may affect processing. Either erase the stray markings or proceed and correct errors later. 
* If sheets are excessively ripped or otherwise damaged, you may need to pull them out and enter them separately. 

## Scanning 
PaperScorer provides three different methods for scanning student answer sheets. Uploading student answer sheets is discussed in the following section. The scanning method described below is recommended for large batches of sheets such as those from a class. The other two methods and their limitations are mentioned briefly at the end of this section for reference.    

### Recommended Scanning Method for Large Batches  
This scanning method involves using a scanner/copier to create a PDF of the sheets. There are two versions of this method, which are described below. For both ways, use the scanner/copier settings described below. 

| Setting | Value |
|---|---|
| File Format | PDF |
| Max File Size | 250 MB |
| Color | Black and White (Grayscale) |
| Resolution | 300 DPI |
| Orientation | Portrait |
| Mode | Single Page/Simplex |


#### USB Drive Version
1. Insert the USB drive into the scanner/copier.
2. Place the sheets in the feeder on top of the scanner/copier.

    **Tip:** 
    Sheets do not need to be sorted by section. You can enter all class sections as a single stack and the application will sort by section   later.
    {: .notice}
   
3. Select **Scan to USB** in the scanner/copier's user interface. The exact wording and procedure may vary by model. Use the scanner/copier settings mentioned above.
4. The scanner/copier will process the sheets and save the file to the USB drive.  
5. Once the file is saved to the USB drive, you are ready to upload the file to PaperScorer. See the **Uploading** section below for instructions.  

#### Email to Yourself Version
1. Place the sheets in the feeder on top of the scanner/copier.

    **Tip:**
    Sheets do not need to be sorted by section. You can enter all class sections as a single stack and the application will sort by section later.
    {: .notice}
   
3. Select **Email** in the scanner/copier's user interface. Enter your own email address as the recipient email address. The exact wording and procedure may vary by model. Use the scanner/copier settings described above. 
4. The scanner/copier will process the sheets and email the file to your email address. 
5. Once you receive the PDF by email, save the file to a location on your computer.  
6. You are now ready to upload the file to PaperScorer. See the **Uploading** section below for instructions. 

### Alternatives (Summary Only)

#### Direct Email: 
Scan the sheets as described above, but instead of using a USB drive or emailing to yourself, email the PDF directly to `scan@paperscorer.com`. PaperScorer will then process the PDF automatically.

**Caution:** 
With direct emails, failed pages are not easy to identify in PaperScorer. For large batches, use another method.     
{: .notice--warning}

#### Mobile App:
Open the PaperScorer mobile app and center a single sheet in the camera viewfinder. The app will then automatically take a photo of the sheet and upload it to PaperScorer.   

**Caution:** 
This method requires processing sheets individually. For large batches, use another method. 
{: .notice--warning}

## Uploading
To upload the PDF to PaperScorer, follow these steps:  

1. Navigate to `https://www.paperscorer.com` in your browser and click **Log In**.

   <img src="/assets/images/01_login_page.png"
     alt="PaperScorer Login Page image"
     class="doc-shot">
  
2. Click **Upload & Score**.

   <img src="/assets/images/02-upload-score.png"
     alt="PaperScorer Upload and Score button image"
     class="doc-shot--detail">
  
3. Click **Browse files**.

   <img src="/assets/images/03-browse-files.png"
     alt="Browse files button image"
     class="doc-shot--detail">
     
4. Select the file in the file picker.
5. Click **Upload**.
6. After you click **Upload**, you will see **Processing**. Processing may take 5–10 minutes depending on file size.
7. When processing is complete, you will see either **Success** or **Completed with errors**.

   <img src="/assets/images/04-success-errors-messages.png"
     alt="Success and completed with errors messages image"
     class="doc-shot--detail">

8. If the result is **Success**, you are ready to grade the sheets immediately. If the result is **Completed with errors**, you must correct the errors as described in the following section. Once corrected, you are ready to grade the sheets. 

## Correcting Errors
To correct errors, follow these steps:
1. Click the more options button to the right of the status bar.
   
   <img src="/assets/images/05-more-options-button.png"
     alt="More options button image"
     class="doc-shot--detail">
   
2. Click **View scanned pages**.

   <img src="/assets/images/06-view-scanned-pages.png"
     alt="View scanned pages button image"
     class="doc-shot--detail">

3. You will see a breakdown of how many sheets were scanned successfully and how many failed.
4. To correct the errors, you must find the sheets that failed. Scroll down in the window and find the scans that have a red status bar. Click the page number you want to view. 

   <img src="/assets/images/07-red-status-bar.png"
     alt="Red status bar and page number link image"
     class="doc-shot">
   
5. Once you have found the failed sheets, note the names of the affected students.

   <img src="/assets/images/08-names-affected-students.png"
     alt="Names of affected students image"
     class="doc-shot">

6. Pull out the relevant paper sheets from the stack. These paper sheets must be re-scanned.   

   **Tip:** 
   For a small number of affected sheets, using the PaperScorer mobile app is quick and easy.
   {: .notice}

7. If the affected sheets re-scan without issue, you are ready to begin grading. If sheets continue to fail, proceed to troubleshooting in the following section.   

## Troubleshooting

### Quick Checks (60 Seconds)
* Make sure you are logged in to the **correct PaperScorer account**. 
* Open the PDF file locally and make sure **it matches the physical sheets** (not blank or cropped).
* If the website page appears stuck, wait 1–2 minutes and **refresh the page**. 
* If the issue persists, switch to a **different browser** or use **incognito/private mode**. 

### Common Issues

| What You See | Likely Cause | What to Do |
|---|---|---|
| **File upload rejected** | Wrong file format, file too large, internet connection issues | Make sure file is **PDF** (not JPEG, PNG, etc.), **250 MB or smaller**, and the **internet connection is fast enough and stable** (use a speed-check website to check). | 
| Upload appears **stuck on processing** | Large file | Processing times of **5–10 minutes are normal for large files**. If needed, **upload file again**. |
| Status shows **Completed with errors** | Paper folds, damaged paper, stray markings | Pull out affected sheets, **correct problems if possible** (for example, unfold sheets), **rescan**. If needed, **grade affected sheets manually**. |
| **Direct email** from copier/scanner to PaperScorer **does not post anything** | Mistyped email address or processing error due to paper sheet damage/errors | Make sure **email address is typed correctly**. **Check physical sheet for damage/errors, fix** (for example, unfold folds and erase stray markings), and **rescan**. If needed, grade affected sheets **manually**. |
| **Mobile app scan fails** | Paper sheet damaged/has errors or glare from overhead lights interferes with scan | **Check physical sheet for damage, fix** (for example, unfold folds and erase stray markings), and **rescan**. Scan in an **environment protected from glare**, such as **under a table or desk**. If needed, grade affected sheets **manually**. |

### When and How to Escalate
#### When to Escalate
Consider escalating if:
* Multiple users encounter the same issue (may be a service issue).
* Uploads fail across different browsers, different files, or different copiers/scanners. 
* Scanning and uploading a teacher-produced test batch does not succeed. 

#### How to Escalate
* For PaperScorer issues, contact PaperScorer directly. 
    * [PaperScorer Help Center](https://help.paperscorer.com/)
    * [Contact Us](https://www.paperscorer.com/support)
* For connection issues or internal IT issues, contact the IT help line at `(000) 000-0000`. 
* For larger work issues resulting from PaperScorer or internal IT issues, contact the Dean of Academics at `(000) 000-0000 Ext. 0` or `deanofacademics@example.com`. 

## Tips
* Have students use No. 2 pencils when completing student answer sheets. No. 2 pencils minimize the risk of scanning issues. Consider distributing pencils to ensure the correct type is used. 

* Carrying around a stack of sheets in a bag prior to scanning them increases the risk of scan issues because the paper can become damaged. Consider scanning the sheets shortly after receiving them.

* If a small number of sheets fail to process, it is often quicker to grade them manually rather than troubleshoot. 

## Student Privacy
* Student answer sheets may contain confidential student information that is protected by FERPA. Make sure to delete the PDF and/or store the PDF/USB drive in accordance with school policy. 

## Next Steps
Once the student answer sheets are scanned and uploaded to PaperScorer, you are ready to begin grading. 




  
