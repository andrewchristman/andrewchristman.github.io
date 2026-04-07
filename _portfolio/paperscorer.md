---
layout: single
title: "PaperScorer How-To Guide: Scanning and Uploading Student Answer Sheets"
og_image: "https://andrewchristman.com/assets/images/og-paperscorer.png"
sequence: 1
excerpt: "Workflow guide with troubleshooting and escalation guidance."
---

(in progress)

<div class="notice">
  <p><strong>Project Brief</strong></p>
  <ul>
    <li><strong>Audience:</strong> Teachers using PaperScorer for grading (spec work).</li>
    <li><strong>User Goal:</strong> To scan and upload student answer sheets to the PaperScorer application.</li>
    <li><strong>Problem:</strong> The procedure is complex, and there are many failure points.</li>
    <li><strong>Scope:</strong> This guide covers a recommended method for scanning and uploading large batches of sheets in detail and briefly mentions alternatives.</li>
    <li>
    <strong>Key Considerations:</strong>
      <ul>
        <li>Guide is scoped to scanning and uploading assessments, not creating assessments, to avoid overwhelming the user.</li>
        <li>Alternative methods for scanning and uploading student answer sheets are mentioned but not described in detail to avoid overwhelming the user.</li>
        <li>Guide distinguishes between problems teachers can resolve themselves and problems that warrant escalation.</li>
      </ul>
    </li>
    <li><strong>Success Criteria:</strong> Teachers can scan and upload sheets to PaperScorer in less than 20 minutes while correcting all errors.</li>
    <li><strong>Validation:</strong> Test with first-time users against the success criteria.</li>
  </ul>
</div>

## Sample

This how-to guide explains how to scan and upload student answer sheets to PaperScorer. Meant for non-technical users, this guide shows how to accomplish this task quickly and efficiently, leaving more time for grading.   

## Prerequisites
* An assessment [created in PaperScorer](https://help.paperscorer.com/article/180-creating-an-assessment) and corresponding [student answer sheets printed out](https://help.paperscorer.com/article/149-printing-an-assessment-for-a-class). 
* A scanner/copier or a mobile phone with a camera. If using a mobile phone, download the PaperScorer app from the App Store (iOS) or Google Play (Android). A scanner/copier is recommended for large batches of sheets.  
* If using a scanner/copier, a USB drive is required if the scanner/copier cannot email files directly. 

## Preparation
First, make sure the student answer sheets are ready to be scanned. 
* Ensure the student answer sheets are rotated the same way as each other. 
* Check for any folds and unfold any you find. 
* Check for stray markings, which may affect processing. Erase the stray markings or proceed and correct errors later. 
* If sheets are excessively ripped or otherwise damaged, they may need to be pulled out and graded manually. 

## Scanning
PaperScorer provides three different methods for scanning student answer sheets. The scanning method described below is recommended for large batches of sheets such as those from a class. The other two methods and their limitations are mentioned briefly at the end of this section.  

### Recommended Scanning Method for Large Batches
This scanning method uses a scanner/copier to create a PDF of the sheets. There are two different versions of this method, which are described below. For both versions, use the scanner/copier settings provided in the table below. 

| Setting | Value |
|---|---|
| File Format | PDF or JPEG (use PDF for large batches) |
| Max File Size | 250 MB |
| Color | Grayscale |
| Resolution | 300 DPI |
| Orientation | Any (consistency makes processing marginally faster) |
| Mode | Single Page/Simplex |


#### USB Drive Version
1. Insert the USB drive into the scanner/copier.
2. Place the sheets in the feeder on top of the scanner/copier.

    **Tip:** 
    Sheets do not need to be sorted by section. You can enter all class sections as a single stack and the application will sort by section later.
    {: .notice}
   
3. Select **Scan to USB** in the scanner/copier's user interface. The exact wording and procedure may vary by model. Use the scanner/copier settings in the table above.
4. The scanner/copier will process the sheets and save the file to the USB drive.  
5. Once the file is saved to the USB drive, you are ready to upload the file to PaperScorer. Go to the **Uploading** section below for instructions.  

#### Email to Yourself Version
1. Place the sheets in the feeder on top of the scanner/copier.

    **Tip:**
    Sheets do not need to be sorted by section. You can enter all class sections as a single stack and the application will sort by section later.
    {: .notice}
   
2. Select **Email** in the scanner/copier's user interface. Enter your own email address as the recipient email address. The exact wording and procedure may vary by model. Use the scanner/copier settings in the table above. 
3. The scanner/copier will process the sheets and email the file to your email address. 
4. Once you receive the file by email, save it to a location on your computer.  
5. Once the file is saved, you are ready to upload the file to PaperScorer. Go to the **Uploading** section below for instructions. 

### Alternatives (Summary Only)

#### Direct Email
Scan the sheets as described above, but instead of using a USB drive or emailing to yourself, email the file directly to `scan@paperscorer.com`. PaperScorer will then process the file automatically.

**Caution:** 
With direct emails, failed pages are not easy to identify in PaperScorer. For large batches, use another method.     
{: .notice--warning}

#### Mobile App
Open the PaperScorer mobile app and center a single sheet in the camera viewfinder on the screen. The app will then automatically take a photo of the sheet and upload the data.   

**Caution:** 
This method requires processing sheets one-by-one. For large batches, use another method. 
{: .notice--warning}

## Uploading
To upload the file to PaperScorer, follow these steps:  

1. Navigate to `https://www.paperscorer.com` in your browser and click **Log In**.

   <img src="/assets/images/101-login-page.png"
     alt="PaperScorer Log In Page"
     class="doc-shot">
  
2. Click **Upload & Score**.

   <img src="/assets/images/102-upload-score.png"
     alt="Upload and Score Link"
     class="doc-shot--detail">
  
3. Click **Browse Files**.

   <img src="/assets/images/103-browse-files.png"
     alt="Browse Files Button"
     class="doc-shot--detail">
     
4. Select the file in the file picker.
5. Click **Upload**.
6. After you click **Upload**, you will see **Processing**. Processing may take 5–10 minutes or more depending on file size.
7. Once processing is complete, you will see either **Success** or **Completed with errors**.

   <img src="/assets/images/104-success-errors-messages.png"
     alt="Success and Completed with Errors Messages"
     class="doc-shot--detail">

8. If the result is **Success**, you are ready to grade the sheets. If the result is **Completed with errors**, you must correct the errors as described in the following section. Once errors are corrected, you are ready to grade the sheets. 

## Correcting Errors
To correct errors, follow these steps:
1. Click the more options button to the right of the status notification.
   
   <img src="/assets/images/201-more-options-button.png"
     alt="More Options Button"
     class="doc-shot--detail">
   
2. Click **View scanned pages**.

   <img src="/assets/images/202-view-scanned-pages.png"
     alt="View Scanned Pages Button"
     class="doc-shot--detail">

3. You will see a breakdown of how many sheets were processed successfully and how many failed.

   <img src="/assets/images/203-success-failure-breakdown.png"
     alt="Success and Failure Breakdown Message"
     class="doc-shot--detail">

4. To correct failed sheets, you must first identify them. Scroll down and find the sheets that have a red status notification. Click the page number indicating the sheet you want to view. 

   <img src="/assets/images/204-red-status-bar-click-page-number.png"
     alt="Red Status Notification and Page Number Link"
     class="doc-shot--detail">
   
5. Once you click the page number, note the name of the affected student.

   <img src="/assets/images/205-names-affected-students.png"
     alt="Sheet Scan with Name of Affected Student"
     class="doc-shot--detail">

6. Repeat until all failed sheets have been identified.  

7. Pull out the failed sheets from the paper stack. These failed sheets must be rescanned. 

    **Tip:** 
    For a small number of failed sheets, using the PaperScorer mobile app to rescan is quick and easy.
    {: .notice}

8. If the failed sheets rescan without issue, you are ready to begin grading. If the failed sheets continue to fail, either grade the sheets manually or try to correct the sheets by erasing any stray markings and unfolding any folds you find. In some cases, manual grading may be necessary. 

## Troubleshooting

### Quick Checks (60 Seconds)
* Open the PDF file locally and make sure it **matches the physical sheets** (not blank or cropped).
* If the website appears stuck, **wait 1–2 minutes** and **refresh the page**. 
* If the issue persists, switch to a **different browser** or use **incognito/private mode**. 

### Common Issues

| What You See | Likely Cause | What to Do |
|---|---|---|
| File is **grayed out** in the file picker | Wrong file format | Make sure file is **PDF** (not JPEG, PNG, etc.). |
| File upload is **rejected with a red banner** | File too large | Make sure file is **250 MB or smaller**. | 
| Upload appears **stuck on processing** | Large file | Processing times of **5–10 minutes or more** are normal for large files. If needed, upload file again. |
| Status shows **Completed with errors** | Stray markings, paper folds, damaged paper | Pull out affected sheets, **correct problems if possible** (for example, erase stray markings), **rescan** (described in detail above). If needed, grade affected sheets **manually**. |
| **Direct email** from scanner/copier to `scan@paperscorer.com` **does not post anything** | Mistyped email address or processing error due to stray markings, paper folds, damaged paper | Make sure email address is **typed correctly**. **Check** physical sheets for **damage/errors**, **fix** (for example, erase stray markings), and **rescan**. If needed, grade affected sheets **manually**. |
| **Mobile app scan fails** | Stray markings, paper folds, damaged paper, glare from overhead lights interferes with scan | **Check** physical sheets for **damage/errors**, **fix** (for example, erase stray markings), and **rescan**. Scan in an environment **protected from glare**, such as **under a table or desk**. If needed, grade affected sheets **manually**. |

### When and How to Escalate

#### When to Escalate
Consider escalating if:
* Multiple users encounter the same issue (may be a service issue).
* Uploads fail across different browsers, different files, or different scanners/copiers.
* Scanning and uploading a teacher-produced test batch does not succeed. 

#### How to Escalate
* For PaperScorer issues, contact PaperScorer directly. 
    * [PaperScorer Help Center](https://help.paperscorer.com/)
    * [Contact Us](https://www.paperscorer.com/support)
* For internal IT issues, contact the IT help line at `(000) 000-0000`. 
* For larger school issues, contact the Dean of Academics at `(000) 000-0000 Ext. 0` or `deanofacademics@example.com`. 

## Tips
* Have students use No. 2 pencils when completing student answer sheets. No. 2 pencils reduce the risk of scanning issues. Consider giving students pencils to make sure they use the correct type. 

* Carrying a stack of sheets around prior to scanning them increases the risk of scan issues because the paper can become damaged. Consider scanning sheets soon after receiving them.

* If a small number of sheets fail to process, it is often quicker to grade manually than troubleshoot. 

## Student Privacy
* Student answer sheets may contain confidential student information that is protected by FERPA. Make sure to delete or store the PDF in accordance with school policy. 

## Next Steps
Once the student answer sheets are scanned and uploaded successfully to PaperScorer, you are ready to begin grading. 



  
