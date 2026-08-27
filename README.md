# Phone-Data-Analyzer
This simple tool analyzes and visualizes your call and SMS history from an Android phone. This tool relies on the output of the __SMS Backup & Restore__ app (by SyncTech Pty Ltd), which can be found on the Google Play Store here:  
     https://play.google.com/store/apps/details?id=com.riteshsahu.SMSBackupRestore

# How It Works
Save the __Phone-Data-Analyzer.html__ file to your computer and open it in a browser. Use the __SMS Backup & Restore__ app to backup your call and message logs/history. (Do __NOT__ include attachments and media!) That creates a pair of XML files, a calls file and an SMS file. One at a time, drag & drop those files into the box on the webpage created by the __Phone-Data-Analyzer.html__ file and it will show you pretty graphs and stats about your calling and texting.

# Privacy
__Phone-Data-Analyzer__ does not share, transmit, save, copy, replicate, or in any way make your data available to anyone except you. When you backup your phone's data using the app, you have the choice of how to get those files to your computer. Your data stays in YOUR cloud storage and on YOUR computer. I can't speak for the __SMS Backup & Restore__ app, but __Phone-Data-Analyzer__ is not network aware and cannot send or share your data. I realize that it opens in a browser, but you don't even need to be connected to the Internet to use __Phone-Data-Analyzer__! At no time is any information sent anywhere you don't tell it to be.

# Instructions
__On Your Computer:__
1. Right-click the link above for __Phone-Data-Analyzer.html__ and select __Save Link As__
2. In the Save window, make sure it shows the file being saved as an HTML document, then click Save.
3. Once you've saved it, double click the file you saved to open it in your default browser.
4. Go to your phone and follow the instructions (below) for backing up your data and getting it to your computer.
5. Once you have a calls-xxxxxxxxx.xml file and a sms-xxxxxxxxxx.xml file (those X's will be a time stamp, such as 20260824081122. Your will reflect the date and time you ran the backup) you can drag and drop one of them onto into the __Phone-Data-Analyzer.html__ window. Be sure to drop it in the box!
6. Scroll through and read the information about your calls or texts. When you done look at that file, you can use the downward pointing arrow to open the drop-box again and drag and drop the other .xml file, changing the analysis info below it. Easy peasey lemon squeezey!

__On Your Android Phone:__
1. On your Android phone (iPhone is not supported) install the __SMS Backup & Restore__ app
2. Open __SMS Backup & Restore__ and tap __Get Started__
3. If asked, grant it permission to access your phone call logs, contacts and accounts, send notifications, make & manage calls, send and view SMS messages (all these are needed to backup your phone calls and SMS messages)
4. Tap __Set Up A Backup__, make sure both Messages and Call Logs are turned on, and tap __Advanced Options__ and turn off __Attachments and Media__. This is important. If you don't turn this off, your backups will be too large for the Phone Data Analyzer tool and it will crash.
5. Tap __Next__ then select where you want to the backup files to go. The simplest is Google Drive.
6. As you turn on the Google Drive selection, it will ask you to login (tap Log In)
7. When you tap __Log In__ it will ask about permissions, select the first option (Only access to files and folders opened or created with __SMS Backup & Restore__), and tap __OK__.
8. (Select which Google account you're going to use, if you have multiple on your phone)
9. Tap __Select A Folder__. You can use the 3-dot menu in the upper right to create a new folder. Once you're in the folder where you want your backups to go, tap __Use This Folder__. That will return you to the __Set Up__ screen, which will show the folder's name that you selected.
10. Leave the rest of the settings at their defaults, then tap __Save__. That will return you to the __Set Up Backup__ screen, and it will show which storage you've got setup. Tap __Next__.
11. Turn off the __Schedule Recurring Backups__ (if you don't want this to backup regularly)
12. Tap __Back Up Now__ to start the backup and you'll see a progress bar as it does it's work. It will say __Backup Complete__ when it is done. It can take a few minutes, so be patient.
13. Once it is done, you can set your phone aside. We're done with it. Move over to your computer, login to Google Drive and download the two .xml files you just created/backed-up.
14. Once you've downloaded your .xml files, you can drag and drop them onto the __Phone-Data-Analyzer.html__ web page to have your data analyzed.  

# Advanced Users - Ultimate Privacy
Save Your Data & View Your Analysis Right On Your Phone - No Cloud Storage Needed!
Instructions:
1. Open this webpage on your phone. Tap and save the above __Phone-Data-Analyzer.html__ to your Downloads folder (or wherever you want to save it).
2. Run the __SMS Backup & Restore__ app, just like above, except instead of choosing cloud storage (like Google Drive) for the destination of the backup, select the bottom option: Your Phone. (I know, it says it's not recommended, but we're not really using the app for a backup. We're using it for an export.)
3. When prompted for where to store it on your phone, do NOT select the first option (Internal App Folder), select the second option (You Own Folder). Then it will ask you to select a folder, and it will likely default to your Downloads folder, but the "Use This Folder" button at the bottom will be greyed out. (Modern Android 'secures' folders from apps.) So tap the little folder-with-a-plus-sign-in-it icon at the top to create a new folder. Name it something like Backup or Call Info. When you create it, it will automatically go into that folder. Now the "Use This Folder" button at the bottom is active. Press it, and now you've set the destination for your call and sms backup to be a folder on your phone. It may pop-up a permissions request, go ahead and approve the app's access to your new folder.
4. That puts you back at the "Configure Local Backup Location" screen. Tap OK. Then continue by tapping Next. It will ask if you're sure, tap Yes.
5. Next it will ask you to setup a schedule for the backup to run. Since we're not really using this as a backup, we don't want to schedule it. Tap Cancel, then it will ask if you're sure. Tap OK.
6. Now you're ready to run the backup. Tap Back Up Now at the bottom. It will create the files for you in the folder you told it to use.
7. When it's done, close the __SMS Backup & Restore__ app and go to your Files app.
8. In the Files app, navigate to your Downloads folder (or where you saved the __Phone-Data-Analyzer.html__ file) and tap on the __Phone-Data-Analyzer.html__ file to open the Analyzer in your browser.
9. When the browser opens, it shows the Analyzer and the Drag & Drop box. Tap the Drag & Drop box, which will open a file picker where you can navigate to the folder where you told the app to save your calls and sms backup files. In that folder tap either the calls or sms xml file and it will open in the Analyzer.
10. Review your info. When you're ready to analyze the other file, tap the drop-down for the Drag & Drop box and then tap the Drag & Drop box to open the file picker again. Then select your other file.

Using these instructions, your phone data never leaves your phone! Complete privacy.

# Screenshots
Before Loading Your Info:
<img width="1291" height="413" alt="Phone-Data-Alayzer-Blank" src="https://github.com/user-attachments/assets/6e8b66cc-fbf8-4c2f-8bd6-6b461de5dd86" />

Call Analysis:
<img width="1293" height="2214" alt="Phone-Data-Analyzer-Calls" src="https://github.com/user-attachments/assets/603682c1-58ab-4916-b316-f14b181f4a52" />

SMS Analysis:
<img width="1291" height="2112" alt="Phone-Data-Analyzer-SMS" src="https://github.com/user-attachments/assets/82346fb4-53fe-4fd5-9ac3-9d2196ac64b3" />

# FAQ:
  Q: Can you change the number of the Top 5 lists?  
  A: Yes! You can use the drop-down to select 5, 10, 25, or 50  

  Q: Can you turn off things on the graph?  
  A: Yes! The color boxes in the legend can be clicked to toggle that dataset on or off in the graph  

  Q: Can you see BOTH call and SMS data at the same time?  
  A: No, it's a one or the other situation. But you can switch back and forth pretty quickly by clicking the dropbox drop-down and dragging your SMS or call xml file over and dropping it in. It will refresh the page with the new data.  
