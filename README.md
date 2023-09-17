# mindDump
<p style="position: relative; overflow:auto">
  <img src="https://github.com/pmarcum/mindDump/blob/main/mindDump_banner_logo.png"
       width=300
       style="display:inline-block;padding-right:10px"
       alt="mindDump-banner-logo">
</p>

<b>mindDump</b> is a project management tool (a Google sheet) that tracks action items or follow-up activities from a meeting, with due dates (when assigned), and which are category-tagged for optimal organization.  This to-do list will also copy the items into your Google Tasks, organizing them under the same categories as in the spreadsheet and keeping them synced with the spreadsheet, if desired.  Items can be entered manually into the spreadsheet OR by using another tool (MeetingNotes, see github repository for access: https://github.com/pmarcum/meetingNotes), in which action items are highlighted in text and automatically copied into the mindDump spreadsheet and Google Tasks. 

The below is a link to the mindDump (a to-do list management tool) spreadsheet on Google Drive: 
https://docs.google.com/spreadsheets/d/1cfW_cp1gsgbELwJIBBmDUGQvKhly68gyPE2FZyzxOWg/copy

If you hit the "Copy" button that appears when you follow the above link, a copy of the spreadsheet will appear on the "My Drive" folder (at the top of the folder hierarchy) in your Google Drive. That copy, which will include the attached script that makes mindDump work, is yours to use for building your personal reference library. Ideally, you would move the file down into a folder designated for your project management activities. 

When you try to press either the help button or the calendar icon button that syncs the list with your Google Tasks, for the first time, you will instead be greeted with an alert that informs you that you need to authorize the script to write into your Google Tasks. Specifically, you will see the following, and should take the indicated action: 

"Authorization Required" --> click on the GREEN "Continue" <br>
"Choose an account" --> select the Google Account / email that you wish to use by clicking on it.<br>
"Google hasn't verified this app":  <br>
    --> scroll to the bottom and click on the small grey underlined "Advanced" in lower left corner.<br>
    --> scroll down to bottom and click on small grey underlined "Go to mindDump (unsafe)" at the very bottom.<br>
"mindDump wants to access your Google Account" --> scroll to the bottom and click the "Allow" button.<br>

To be able to enter items directly from meeting notes, you should also copy and install meetingNotes (see https://github.com/pmarcum/meetingNotes). 

To initialize mindDump, you need to do only 1 thing: 
(1) click on the "gmailsTasklistIds" tab at the bottom of the spreadsheet to bring up the gmailsTasklistIds page, and then replace the column headings "GENERAL", "PERSONAL", "EXAMPLE1", "EXAMPLE2", ... with your own set of desired task categories.  (I recommend retaining the "GENERAL" and "PERSONAL").  For example, my own task category labels are named after my research grant proposals (e.g., "ADAP2022", etc.).  You should also decide on color scheme for each category -- pick a color (background and font color) that is unique for each task category.  The color scheme will be used in other applciations of the software, so that easy association of tasks can be made. 

The email column will be automatically filled out by the script, and the cells under the column headings will also be filled out by the script. 

Feel free to contact me if you run into permission problems or if you notice any bugs as you use the code. 

         %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
         %%%%%%%%%%%     Thank you for your interest in mindDump!   %%%%%%%%%%%
         %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

         
================================
         Updates: 
================================
Latest version is 09152023

09/15/2023: 
- First release of mindDump. 

